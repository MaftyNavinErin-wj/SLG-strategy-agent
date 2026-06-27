# 无尽冬日 / Whiteout Survival Mechanics Notes

Status: first-pass public-source synthesis  
Access date: 2026-06-27
Latest refresh: 2026-06-27

## One-Line Read

无尽冬日是一个以生存题材降低 SLG 进入门槛的 Casual COK Like。它先用炉火、生存、幸存者、建筑和轻量 PVE 建立情境，再把玩家推进联盟、集结、跨服/跨州战争和活动日历，最终用英雄、兵种、建筑、科技、火晶/高阶成长和联盟荣誉承接长期 LTV。

## Core Fantasy

The player is not initially framed as a classical king or warlord. The early fantasy is "keep the settlement alive in extreme cold." This matters because it changes onboarding:

1. Furnace survival gives the base-building loop a natural reason.
2. Survivors and facilities make resource production legible before war pressure appears.
3. Heroes are both expedition leaders and combat power carriers.
4. Alliance gradually shifts the identity from settlement manager to state/server competitor.

Design implication: the game does not replace SLG depth with casual survival. It uses survival to soften the first hours, then exposes the same hard SLG obligations: growth discipline, alliance schedule, rally participation, state competition, and payer-led hierarchy.

## Early Loop

The early loop is:

1. Upgrade furnace and facilities.
2. Keep resource production and survivor jobs running.
3. Clear exploration / expedition content with heroes.
4. Train infantry, lancer, and marksman troops.
5. Join an alliance for help, rewards, rallies, and protection.
6. Follow event calendar to convert activity into speedups, shards, resources, and status.

The furnace is the symbolic and practical center. Other facilities hang off it as growth unlocks. This makes power progression easier to explain than a pure city-hall model because the central object is emotionally tied to survival.

## City, Economy, And Growth

Important building categories:

1. Central progression: furnace and level-gated facilities.
2. Resource production and storage.
3. Troop production: infantry, lancer, marksman camps.
4. Combat support: command center, infirmary, embassy/alliance-related structures.
5. Research and training infrastructure.
6. Hero and recruitment systems.

Design role:

1. Building queues and timers create the classic SLG monetization surface.
2. Resources and speedups connect daily activity to paid acceleration.
3. Infirmary and troop loss rules decide how painful PVP is.
4. Alliance help reduces friction while increasing social dependence.

Player behavior:

1. Early players chase furnace level because it gates almost everything.
2. Mid-game players optimize troop tiers, research, heroes, and event rewards.
3. Late-game players coordinate around state events, alliance war, and high-power builds.

## Heroes

Heroes carry multiple layers:

1. Exploration / PVE progression.
2. Expedition or march leadership.
3. Rally joining and rally leading.
4. Troop-type specialization.
5. Generation-based release cadence.
6. Shards, star levels, gear/widgets, and exclusive enhancements.

The important SLG design point is that heroes are both content and monetization. A new hero generation can refresh the meta without resetting the whole server. It also creates spender differentiation:

1. Low spenders usually focus on a small number of efficient heroes.
2. Mid spenders chase event heroes and selected shards.
3. High spenders max current-generation rally leads and hero gear.

Open verification:

1. China-version hero release timing versus global version.
2. Exact current best heroes by state age.
3. Whether rally joiner hero order and expedition skills differ in local player consensus from wiki descriptions.

## Troops And Combat

Basic troop families:

1. Infantry: front-line durability.
2. Lancer: offensive / formation middle role.
3. Marksman: back-line damage role.

Combat depth comes from:

1. Troop tier and quantity.
2. Hero stats and skills.
3. Research and chief gear.
4. Rally leader quality.
5. Joiner troop composition and skill contribution.
6. Buff timing from events, alliance tech, pets/gear in applicable versions.

This is still closer to COK-like power comparison than 率土-like path strategy. Most strategic agency is before battle: who leads, who joins, what troops are sent, when buffs are used, and whether the alliance can coordinate attendance.

Player-facing pain points to track:

1. Rally leader gap creates strong whale centrality.
2. Incorrect joiner heroes or wrong troop mix can lower alliance efficiency.
3. PVP injury/loss rules determine whether ordinary players dare to fight.
4. Battle reports need interpretation; many players ask for formation advice rather than doing formula work.

## Alliance System

The alliance is the real retention structure after onboarding.

Core functions:

1. Help speed up construction/research.
2. Shared gifts and event rewards.
3. Rally organization for beasts, objectives, and PVP.
4. Alliance tech and territory/battle participation.
5. Social protection and account-status identity.

Alliance roles:

1. Whale rally leader.
2. R4/R5 scheduler and disciplinarian.
3. Active joiner / attendance player.
4. Scout/info player.
5. Resource/support player.

Design read: 无尽冬日 can recruit casual users, but the alliance converts them into scheduled users. The more valuable player is not only the highest spender; it is also the player who attends events on time and follows rally instructions.

## Event Calendar

Representative events and their design roles:

1. Crazy Joe: alliance defense and attendance check.
2. Bear Hunt / hunting events: damage race, rally discipline, hero/troop optimization.
3. Foundry Battle: alliance-vs-alliance objective battlefield, temporary war concentration.
4. State of Power / SvS: state-vs-state preparation and war climax.
5. Hall of Chiefs / growth races: spending and hoarding rhythm.

Event design function:

1. Converts long timers into short social appointments.
2. Makes alliance leaders necessary.
3. Gives non-whales a visible job: join, reinforce, defend, fill rallies.
4. Creates pack timing and resource hoarding behavior.
5. Lets the server/state periodically define enemies and heroes.

## Server / State Ecology

The game uses state age, hero generations, event unlocks, and state-vs-state conflict to manage progression. Instead of a full 率土-style seasonal reset, it leans on:

1. State lifecycle.
2. Cross-state war.
3. Event cadence.
4. New hero generations and growth ceilings.
5. Alliance reorganization and account trading ecology.

Tieba signals worth tracking:

1. Account sales and valuation appear frequently, implying mature-server churn and power-as-asset thinking.
2. Alliance conflict and leadership disputes are likely more important to retention than pure PVE content.
3. Formation and hero advice posts indicate that mechanics are opaque enough to require community interpretation.

## Monetization Surfaces

Main surfaces:

1. Speedups and resources.
2. Building/research/troop acceleration.
3. Hero acquisition and shards.
4. Hero gear/widgets and exclusive progression.
5. Chief gear/charm or equivalent commander stat systems.
6. Event packs and rank races.
7. Cosmetic/status purchases where applicable.

Monetization is vertical and hierarchical. The player can understand the power ladder quickly: stronger hero, higher troop tier, better gear, more troops, better buffs. This supports whale leadership and alliance dependence.

## Current / Latest Public Snapshot, 2026-06-27

This section is intentionally separate from the stable mechanism model because 无尽冬日 live data changes by server age, region, and hero generation.

Current public materials to prioritize:

1. WhiteoutData / Whiteout Survival Wiki for structured mechanics: heroes, facilities, troops, Crazy Joe, Foundry Battle, and State of Power.
2. TapTap and Chinese community guides for 国服 player vocabulary, alliance event priorities, spending tiers, and current server complaints.
3. Official/global announcements for feature names and timing, but only when they link to full patch notes or explain rules directly.

Latest public-mechanism themes:

1. Later-server progression is increasingly about layered vertical growth after basic furnace/building progress: Fire Crystal / Flame Tech, higher troop tiers, Helios Troops where applicable, hero generations, chief/hero gear, and event-limited materials.
2. Hero generation timing matters more than a static "best hero" list. A recommendation must first identify state age and currently unlocked generation.
3. Alliance events remain the practical center of play. Bear Hunt, Crazy Joe, Foundry Battle, and State of Power are not side content; they are where attendance, rally discipline, buff timing, and hierarchy become visible.
4. Current player advice often separates rally leaders from rally joiners. This matters because a low/mid spender should optimize for efficient joiner contribution rather than pretending to play the same build as a whale lead.
5. 国服 and global-version timing may diverge. Use global wiki for structure, but verify local hero/event timing before giving precise advice.

Answering rule for current questions:

1. If asked "which hero should I train" or "what lineup is best," first ask or infer: server age, hero generation, spend level, target mode, and whether the player is rally lead or joiner.
2. If asked "what should an alliance do," focus on calendar discipline, rally-lead concentration, joiner education, buff timing, and event reward allocation.
3. If asked about monetization pressure, separate permanent vertical stats from event-timed acceleration and limited-resource bottlenecks.

## What To Know For Q&A

When answering product or design questions, use this mental model:

1. Do not describe 无尽冬日 as just "SLG plus survival skin." The survival layer is an onboarding and substitution strategy.
2. The strategic center is alliance scheduling and rally hierarchy, not tactical map routing.
3. The furnace is the onboarding anchor; the alliance is the retention anchor; SvS/state events are the endgame anchor.
4. Depth comes less from individual tactical mastery and more from social discipline, growth planning, event optimization, and spender hierarchy.
5. Its category importance is that casual entry and broad UA can still be converted into high-LTV COK-like depth.

## Open Questions For Next Pass

1. Current China server event unlock timeline by day/state age.
2. Exact hero generation table and best-value heroes by spending tier.
3. Current rally joiner optimization rules used by Chinese players.
4. Injury/death rules across common event types.
5. Pack ladder and first-month spend pressure by system.
6. Current 国服 versus global hero generation and event unlock timeline.
