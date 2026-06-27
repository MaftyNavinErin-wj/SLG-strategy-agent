# 三国志战略版 Mechanics Notes

Status: first-pass public-source synthesis  
Access date: 2026-06-27
Latest refresh: 2026-06-27

## One-Line Read

三国志战略版是 率土 Like 的代表型产品：它把三国武将卡牌、战法搭配、土地开荒、同盟组织、攻城和赛季重置结合起来。它的深度不主要来自实时操作，而来自赛季目标、地图扩张、队伍构筑、战报理解、同盟纪律和外交执行。

## Core Fantasy

The player is a lord inside a seasonal Three Kingdoms war. The fantasy has three layers:

1. Personal: draw and build famous generals.
2. Strategic: expand land, build teams, read battle reports, improve opening efficiency.
3. Social/political: join an alliance, fight cities, obey commands, contribute to season results.

The product's strength is that card collection and alliance war reinforce each other. A better team improves land opening and war contribution; alliance success gives status, rewards, and identity.

## Season Loop

The season loop is central:

1. Early season: land opening, resource ramp, core team formation, alliance joining.
2. Mid season: city capture, route expansion, fort/territory pressure, inter-alliance conflict.
3. Late season: state-level war, domination, season objective/ranking settlement.
4. Next season: partial reset with preserved account value, new script/rules, new meta pressure.

The reset is not a wipe. Permanent paid/account value is preserved, while map control, land, many local achievements, and the geopolitical board are reset. This solves three problems:

1. Prevents one server state from freezing forever.
2. Creates repeated opening-race engagement.
3. Gives old players a reason to re-evaluate teams under new rules.

## Map And Territory

The map is not just a coordinate background. It is the strategic object:

1. Land levels define early growth pacing and risk.
2. Adjacent occupation and route rules create expansion fronts.
3. Passes, cities, and chokepoints define war geography.
4. Forts and marching distance create logistics.
5. Alliance territory and command structures turn individual movement into group strategy.

Design read: compared with COK-like city-centered maps, 三国志战略版 puts more depth into "where can we go, what can we hold, who controls the route, when do we open the pass." This shifts value from pure whale power toward officers, planners, and disciplined executors, though spending still matters through generals and tactics.

## Opening / 开荒

Opening is a defining skill check.

Core variables:

1. Starting general quality.
2. Tactics availability and level.
3. Land level progression.
4. Injury and troop recovery.
5. Resource balance.
6. Stamina / marching cost.
7. Timing relative to alliance plans.

Why players discuss 开荒 so much:

1. Early mistakes compound into slower resource growth.
2. Opening teams are not always the same as late-war teams.
3. Players need low-loss land clearing, not just theoretical strongest teams.
4. Server race pressure makes efficient guides valuable.

Mechanism implication: 开荒 is where individual optimization feeds alliance macro. A slower player contributes less to early city capture and regional pressure.

## Generals, Tactics, And Buildcraft

The core buildcraft stack:

1. Generals: faction, cost, attribute, command/active/passive skill, team synergy.
2. Tactics / 战法: inherited, event, command, active, passive, assault, etc.
3. Troop type aptitude and weapon type.
4. Unit cost and command cap.
5.兵书 / advanced build layer.
6. Season environment and counter-meta.

The system is horizontal compared with COK-like vertical power:

1. A general is not only "higher number."
2. The question is whether the team has coherent damage, control, healing, mitigation, and speed order.
3. Many teams are matchup-dependent.
4. Battle reports are learning artifacts; players infer whether a loss came from tactics, attributes, restraint,兵力, morale, or unlucky activation.

This is why player communities are full of "配将" and "战报诊断" posts. The game creates enough combinatorial complexity that ordinary players outsource interpretation to guides and veteran players.

## Combat

Combat is largely pre-battle strategic composition plus probabilistic resolution.

Key concepts to track:

1.兵种克制.
2.武将属性.
3.战法发动率 and target rules.
4. Damage type and mitigation.
5. Control states.
6. Healing and recovery.
7. Morale / 士气 and travel-distance penalty.
8. Troop count, injury, and recovery.
9. Siege value for objectives.

Design role:

1. 战法 probability creates replayability and drama.
2.克制 and morale prevent "one strongest team" from solving all battles.
3.战报 opacity sustains community analysis.
4. Buildcraft creates monetization pressure through generals and tactics, but also lets knowledgeable players feel agency.

Open verification:

1. Current official wording and exact morale thresholds.
2. Latest battle formula changes by season/script.
3. Current meta definitions for common team names.

## Alliance / 同盟

The alliance is a structured war organization, not just a reward guild.

Core functions:

1. Coordinate land expansion and pass opening.
2. Plan city capture and siege attendance.
3. Assign routes, defense zones, and timed operations.
4. Conduct diplomacy with other alliances/states.
5. Enforce discipline: no random land blocking, follow mail/marker orders, reinforce fronts.
6. Manage season reward expectations and migration.

Important roles:

1.盟主 / senior leadership.
2. Commanders and map planners.
3. Diplomats.
4. Battlefront executors.
5. Siege/time-zone attendance players.
6. High-power accounts as breakthrough force.

Design read: 三国志战略版's long-term social retention comes from giving non-whales meaningful jobs. A player can have identity as a planner, diplomat, front-line grinder, or reliable attendance member, not only as the biggest spender.

## Cities, Passes, And War

War is shaped by map objectives:

1. Cities provide alliance/server goals and rewards.
2. Passes gate regional movement and create scheduled conflict.
3. Forts and march paths create logistics preparation.
4. Siege requires group timing and enough siege value.
5. Defense involves blocking, reinforcing, counter-marching, and stamina/resource management.

The key difference from many COK-like products is that war is less about one rally leader carrying everyone. It is more about a large number of players being in the right place at the right time with the right teams, although high-power teams still strongly affect front-line outcomes.

## Monetization Surfaces

Main surfaces:

1. General card acquisition.
2. Tactics inheritance and team completion pressure.
3. Season-limited or script-relevant generals/tactics.
4. Resource and acceleration support.
5. Account development over multiple seasons.

The monetization is relatively horizontal: the game sells options, combinations, and meta readiness. This differs from 无尽冬日's more direct vertical power ladder.

## Player Community Signals

High-frequency player questions:

1. How to open land efficiently with my cards.
2. Which team can I build from this box.
3. Why did this battle report lose.
4. Which season/script should I choose.
5. Whether an account is worth buying or continuing.
6. Whether an alliance/server is active and disciplined.

Tieba is especially useful for seeing these live anxieties: account valuation, 配将 screenshots, draw frustration, season migration, and alliance conflicts. These are not side topics; they reveal the real retention structure.

## Current / Latest Public Snapshot, 2026-06-27

This section is intentionally separate from the stable mechanism model because 三国志战略版 current advice changes by season, script, card pool, and update.

Current public materials to prioritize:

1. Official 三国志战略版 / Lingxi news for season-entry windows, script availability, update notes, settlement rewards, and card-pack changes.
2. Player guide sites and TapTap for live 开荒 and 配将 consensus.
3. Tieba for real player pain points: account box screenshots, team diagnosis, season/server choice, and alliance disputes.

Latest public-mechanism themes:

1. 2026 live discussion centers around PK-season script rotation and script-specific rules, including 汉焰长明, 英雄命世, and 九州兵兴. These scripts should not be treated as cosmetic season names; they can alter strategic priorities, available rules, rewards, and player migration choices.
2. Official 2026 updates include balance and economy-facing changes such as 张辽 adjustment, PK-season settlement/reward and card-pack changes, and early-stage experience/anti-boosting rule tuning. These affect both meta teams and season pacing.
3. The current meta remains strongly "box-dependent." A correct answer to 配将 cannot start from a universal top-list; it must start from owned generals, inherited tactics, current season/script, and opening versus war objective.
4. 开荒 is still the highest-frequency early-season optimization problem. Advice must distinguish between low-loss land clearing, fast resource ramp, and later PVP team conversion.
5. 战报诊断 remains a core community mechanic. For current Q&A, explain losses through a stack: morale,兵种克制, tactics activation/order, control, healing, attribute gap, troop count, and matchup.

Answering rule for current questions:

1. If asked "这套阵容怎么样," first identify current season/script, account box, tactics availability, and target use case: 开荒, 打架,驻守,攻城, or共存.
2. If asked about a 2026 script, browse official update notes before answering exact rules.
3. If asked about meta tier lists, treat them as date-stamped and script-specific, not general truth.
4. If asked about product design, use stable structures: season reset, map geopolitics, alliance command, card/tactics buildcraft, and battle-report learning.

## What To Know For Q&A

When answering product or design questions, use this mental model:

1. 三国志战略版 is season-geopolitical SLG plus card buildcraft.
2. Its strategic depth is distributed across opening efficiency, map routes, alliance command, and battle report/team interpretation.
3. Its monetization is not simply "pay to be stronger"; it is "pay to own enough generals/tactics to solve more seasonal/team situations."
4. The alliance provides social status and execution pressure; the season reset renews both strategy and monetization.
5. Compared with COK-like products, individual whale dominance is less absolute, but card depth and account age still matter.

## Open Questions For Next Pass

1. Current official season/script taxonomy and retention impact.
2. Exact preservation/reset rules across S1/S2/S3/PK seasons.
3. Latest top meta teams and counter relationships.
4. Current new-player onboarding changes and friction reduction.
5. How official events and community tools shape 配将 decisions.
6. Current 2026 script rules and balance changes by official update date.
