# Agent Brief: SLG Strategy Working Memory

Status: living entry point  
Last updated: 2026-06-30

## Purpose

This is the agent-facing entry file for the SLG strategy workspace. Read this first before answering SLG category, product, mechanism, or strategy questions.

The goal is not to make the agent "all-knowing." The goal is to route questions to the right context, separate stable conclusions from volatile live-meta claims, and reduce hallucination by making uncertainty explicit.

## Operating Principle

Use the repo as layered working memory:

1. Start from this brief.
2. Route to the minimum relevant context files.
3. Answer from stable distilled notes when the question is structural.
4. Re-browse or verify when the question depends on live versions, current meta, current events, rankings, or patch state.
5. State uncertainty when the source layer is incomplete or stale.

## Maintenance Rules

Treat this file as a living entry point, not a comprehensive archive.

Update this brief when:

1. A new important context file is added and future agents need to know when to read it.
2. The primary mountain taxonomy or secondary analysis lens changes.
3. A previously stable conclusion becomes uncertain and should move into the volatile / verification layer.
4. A research gap is closed, reframed, or replaced by a more important gap.
5. A new live-meta area appears and should be listed as requiring current verification.
6. The answering protocol changes because the workspace has learned a better way to route questions.

Do not update this brief for:

1. Raw source collection.
2. Detailed single-product notes that belong in `context/game_mechanics/`.
3. Long current-meta tables that belong in dated snapshot files.
4. Full copied community posts, raw deck text, or copyrighted source material.
5. Minor wording changes that do not affect future routing, stable conclusions, or verification rules.

Before updating, ask:

> Does this change how a future agent should find context, classify a question, avoid hallucination, or decide what must be verified?

If yes, update this brief. If no, put the material in the more specific context file.

## Core Thesis

Mobile SLG is a multiplayer online war society built from 4X resources / expansion, big-map conflict, season or server cycles, alliance organization, and long-term status pursuit.

The key split is not theme. It is how a product organizes:

1. Map and territory.
2. Combat and battle readability.
3. Growth and monetization.
4. Alliance discipline and social roles.
5. Season / server reset or renewal.
6. User entry and traffic acquisition.

## Primary Mountain Taxonomy

Use this as the main structural taxonomy unless a question explicitly asks for another lens.

1. COK Like:
   - Coordinate-map castle / city war.
   - Vertical growth through buildings, troops, heroes, tech, gear, speedups, and resources.
   - Alliance war often centers on rallies, shields, teleport, throne / wonder, cross-server events, and whale / rally-lead hierarchy.

2. 率土 Like:
   - Seasonal geo-board built around land, routes, passes, cities, borders, and alliance diplomacy.
   - Horizontal card / general / tactic buildcraft matters.
   - Alliance discipline, officers, planners, diplomats, and executors are central.

3. ROK Like / ROK-side fusion:
   - Free march and real-time battlefield expression.
   - KvK, rally / garrison, open-field fight, focus fire, and live command are important.
   - The map has objectives and channels, but is usually not a 率土-style continuous land board.

4. Casual COK Like:
   - COK-like or SLG backend with a lighter front-end entry.
   - Survival, running, shooting, puzzle, settlement, or other light loops reduce first-session resistance.
   - The backend still converts players into alliance obligation, event schedules, vertical growth, and high-LTV war systems.

## Secondary Lens: Internal 2x2

Use `context/slg_internal_taxonomy_2x2.md` when explaining how SLG subtypes feel different in play.

Axes:

1. Spatial path dependency / geo constraint:
   - Low: map is mostly coordinate container and event target space.
   - High: land, roads, passes, distance, access, borders, and front lines change future strategic options.
   - Connected land is an implementation detail; the deeper issue is whether map choices create persistent route dependence, alliance labor, and diplomacy with physical consequences.

2. Synchronous battlefield operation:
   - Low: growth, setup, pre-positioning, timing, and reports matter more than live micro; the thinking is closer to tactics / turn-based / pre-battle puzzle-solving.
   - High: free march, positioning, kiting, focus fire, garrison swaps, pathing, and live command materially affect outcomes; the thinking is closer to RTS / MMO battlefield command.

Quadrants:

1. Low path dependency + low sync: Castle War / COK Like.
2. High path dependency + low sync: Seasonal Geo-Board / 率土 Like.
3. Medium-low path dependency + high sync: Real-Time Field War / ROK Like.
4. High path dependency + high sync: Geo + Real-Time Fusion.

Important caution:

Casualization is an overlay, not a clean quadrant. 无尽冬日 and Last War should be read as COK-like or SLG backend systems with lighter front-end entry and delayed complexity exposure.

## Context Routing

### If The User Asks About SLG Category Structure

Read:

1. `context/slg_deck_digest.md`
2. `context/slg_internal_taxonomy_2x2.md`
3. `context/slg_deck_page_by_page_walkthrough.md` only if page-level deck context is needed.

Use for:

1. COK Like vs 率土 Like.
2. ROK / fusion positioning.
3. Casual COK Like growth.
4. Why SLG is a war society rather than a theme category.

### If The User Asks About Representative Product Mechanics

Read:

1. `context/slg_representative_mechanics_overview.md`
2. The relevant file under `context/game_mechanics/`
3. `context/slg_representative_games_research_findings.md` for cross-product conclusions.

Game files:

1. `context/game_mechanics/whiteout_survival_mechanics.md`
2. `context/game_mechanics/sgz_strategy_mechanics.md`
3. `context/game_mechanics/lutu_beach_mechanics.md`
4. `context/game_mechanics/three_kingdoms_mouding_mechanics.md`

Use for:

1. Stable loop explanation.
2. Growth, combat, map, alliance, monetization, and retention analysis.
3. Cross-product comparison.

### If The User Asks For Current Advice Or Meta

Read:

1. `context/game_mechanics/current_live_snapshot_2026-06-27.md`
2. `sources/public_research/slg_representative_games_source_index.md`

Then re-browse current official and community sources when the question depends on:

1. Hero generation.
2. General / tactic meta.
3. Season or script rules.
4. Profession balance.
5. Event unlock timeline.
6. Pack value, spending advice, or current best lineup.
7. Current server ecology, migration, or player sentiment.

Do not answer exact current advice from memory or from stable mechanism notes alone.

### If The User Asks How To Produce Strategy Material

Read:

1. `workflows/mountain_discussion_agent_workflow.md`
2. `workflows/slg_mechanics_research_workflow.md`

Use for:

1. New category research structure.
2. Deck / memo outline.
3. Research plan.
4. Product deep-dive template.
5. Source strategy and quality bar.

### If The User Asks About AI-Native Games

Read:

1. `context/ai_native_game_strategy_frame.md`

Use for:

1. AI-native experience.
2. Pipeline reconstruction.
3. Dynamic world / MMO / SLG / sandbox strategy questions.

## Stable Conclusions

These are stable enough for product and strategy discussion:

1. SLG should be analyzed as big-map war society, not as theme or simple strategy combat.
2. COK Like and 率土 Like differ primarily by map / territory model, not by theme.
3. COK Like leans vertical power, castle / city growth, rally hierarchy, event calendars, and cross-server conflict.
4. 率土 Like leans season geo-board, land route, pass / city control, alliance discipline, diplomacy, and horizontal buildcraft.
5. ROK Like adds live battlefield expression through free march, open-field fighting, rally / garrison, and live command.
6. Fusion SLG is high-risk because it tries to stack geo-board depth and real-time battlefield operation.
7. Casual COK Like is not just "SLG plus minigame." It is a user-entry and traffic-efficiency shift that preserves a high-LTV SLG backend.
8. Alliance is the real retention structure across SLG, but the job of alliance differs by mountain.
9. Non-whale contribution is a core design problem. Winning SLG must give ordinary players socially recognized jobs.
10. Community knowledge is part of the product because buildcraft, reports, opening, and live-meta interpretation are not fully legible from the client alone.

## Volatile Claims That Require Verification

Always verify before giving exact answers about:

1. Current hero generation in 无尽冬日 / Whiteout Survival.
2. Current best heroes, rally lead / joiner setup, or event-specific formation.
3. Current 三国志战略版 season scripts, PK rules, generals, tactics, and lineups.
4. Current 率土之滨 season rules, card / tactic meta, account value, and server ecology.
5. Current 三国谋定天下 profession balance, season mechanics, and opening meta.
6. Current ROK / Call of Dragons commanders, KvK rules, and balance.
7. App availability, regional version differences, live events, and official update state.
8. Revenue, ranking, DAU / MAU, market size, or company / team facts that may have changed.

## Answering Protocol

Before answering, classify the user question:

1. Structural / category question:
   - Use stable notes.
   - Explain with taxonomy and mechanism logic.

2. Product-mechanism question:
   - Use representative overview and per-game notes.
   - Explain player behavior, bottleneck, alliance role, monetization, and non-whale optimization.

3. Current advice / meta question:
   - Ask for or infer server / season / script / account box / spend tier / role / target mode.
   - Re-browse if current facts matter.

4. Strategy / BD question:
   - Identify the mountain.
   - Ask what audience expansion problem is solved.
   - Ask what depth is preserved or sacrificed.
   - Ask whether alliance leaders and ordinary players are helped or burdened.
   - Ask whether monetization matches the product's depth source.

## Current Research Gaps

1. More complete coverage of classic COK Like through Lords Mobile / 王国纪元 or a similar active sample.
2. More complete coverage of ROK Like through Rise of Kingdoms / 万国觉醒.
3. More complete coverage of Last War / Kingshot as casual COK Like cases.
4. Better fusion examples and a clearer placement of 重返帝国 and 指尖无双.
5. First-hand screenshots of UI, monetization surfaces, event cadence, and alliance tools.
6. Player or officer interviews to validate alliance-operation conclusions.
7. Market data and team capability mapping for BD / coverage prioritization.

## Source Handling Rules

1. Do not commit raw decks, full extracted deck text, or raw copyrighted community posts unless explicitly approved.
2. Store distilled claims, URLs, reliability notes, and open questions.
3. Official sources are best for rules, schedules, and update names.
4. Wikis and databases are best for taxonomy and system vocabulary.
5. Player guides are useful for practical strategy but must be date- and version-stamped.
6. Tieba and forums are useful for live pain points and question discovery, not exact formulas unless backed by reproducible screenshots or data.

## Short Self-Check Before Final Answers

1. Did I identify the right mountain or lens?
2. Did I distinguish stable mechanism from live meta?
3. Did I explain the system through player behavior and alliance structure?
4. Did I flag what needs current verification?
5. Did I avoid treating a theme, region, or wrapper as the underlying product model?
