# SLG Mechanics Research Workflow

Use this workflow when the goal is to make the agent understand a representative SLG deeply enough to answer mechanism, product, and design questions.

This is not generic market research. The output should explain how systems lock together: player fantasy, growth, combat, map, alliance, event/season loop, monetization, and community knowledge.

## Research Objective

For each game, build three layers of understanding:

1. Stable mechanism model: what the game is structurally.
2. Current live snapshot: what is changing by version, season, hero generation, or meta.
3. Q&A operating rules: what must be verified before answering exact player advice.

## Source Strategy

### 1. Use Public Sources Only

Do not bypass login, anti-scraping, paywalls, or private communities. Do not archive raw copyrighted posts or answers. Store URLs, distilled claims, reliability notes, and open questions.

### 2. Prioritize Sources By Use Case

| Source Type | Best For | Reliability Pattern |
| --- | --- | --- |
| Official site / patch notes | rules, schedules, season names, feature releases | high for facts, low/medium for strategy |
| Game wiki / structured databases | system taxonomy, hero/general data, event structure | high for structure, medium for live balance |
| TapTap / guide sites | player practice, opening guides, lineup advice | medium; date and version required |
| Zhihu / industry analysis | product model, design interpretation, market logic | medium; verify mechanisms elsewhere |
| Tieba / forums | live anxieties, account ecology, alliance disputes, pain points | medium for sentiment, low for exact rules |
| Gameplay / screenshots | actual client behavior and UX | high if current and reproducible |

### 3. Separate Stable From Volatile

Stable:

1. Mountain type.
2. Core loop.
3. Growth structure.
4. Social structure.
5. Monetization surfaces.
6. Design role of systems.

Volatile:

1. Current hero generation.
2. Current generals / tactics meta.
3. Current season script rules.
4. Event unlock timeline.
5. Balance changes.
6. Pack value and spender recommendations.

Volatile claims must be date-stamped and rechecked before use.

## Mechanism Teardown Template

For each game, write the following sections.

### 1. One-Line Read

State the product's structural identity in one sentence.

Example:

`无尽冬日 is a survival-themed Casual COK Like that converts broad casual traffic into alliance-centered SLG depth.`

### 2. Core Fantasy

Answer:

1. Who does the player become?
2. What does the first session make emotionally clear?
3. What is the long-term status pursuit?
4. How does the fantasy support monetization and social obligation?

### 3. Early Loop

Trace the first meaningful cycle:

1. What does the player upgrade or occupy?
2. What resource gates appear?
3. What combat/PVE validates growth?
4. When does alliance become necessary?
5. What is the first hard bottleneck?

### 4. Growth And Economy

Map:

1. Main progression gates.
2. Resource bottlenecks.
3. Time gates.
4. Paid acceleration.
5. Permanent versus seasonal value.
6. Where free players can still optimize.

### 5. Combat And Reports

Identify whether combat depth comes from:

1. Raw power comparison.
2. Pre-battle team buildcraft.
3. Map context.
4. Timing and buffs.
5. Rally hierarchy.
6. Battle-report interpretation.
7. Live tactical control.

### 6. Map / Event / Season Structure

For COK-like products:

1. Server or state lifecycle.
2. Cross-server/cross-state war.
3. Event calendar.
4. Rally objectives.
5. Power inflation management.

For 率土-like products:

1. Land and adjacency.
2. Passes, cities, chokepoints.
3. Season reset.
4. Script/rule changes.
5. Alliance route and diplomacy.

### 7. Alliance And Social Roles

Document:

1. Why players must join.
2. What leaders/officers actually do.
3. What non-whales contribute.
4. How discipline is enforced.
5. Whether roles are system-visible or only socially assigned.
6. How alliance identity survives churn or reset.

### 8. Monetization

Separate:

1. Vertical power: levels, troops, gear, speedups, stats.
2. Horizontal options: generals, tactics, team possibilities.
3. Timed pressure: events, rankings, season openings.
4. Social pressure: alliance expectations and war readiness.
5. Status pressure: server rank, rally lead, officer identity.

### 9. Community Knowledge

Record what players repeatedly ask:

1. Opening / 开荒.
2. Team / 配将.
3. Battle report diagnosis.
4. Spending value.
5. Account value.
6. Alliance/server choice.
7. Churn complaints.

These questions reveal where the game is opaque and where community labor becomes part of the product.

## Comparison Rules

Do not compare only by theme. Compare by structural differences:

1. User entry: casual, historical theme, survival, card fantasy, profession fantasy.
2. Main board: city/server, seasonal land map, objective battlefield.
3. Growth model: vertical ladder versus horizontal combinations.
4. Combat agency: rally leader, team theory, map route, profession/logistics.
5. Alliance role: reward guild, event body, geopolitical army, formalized roles.
6. Reset model: event cadence, state lifecycle, season reset, script iteration.
7. Monetization: acceleration, cards, tactics, hero generations, gear, role optimization.

## Current-Advice Rules

Before answering exact live advice:

1. Ask or infer server age / season / script.
2. Ask or infer owned heroes/generals/tactics.
3. Identify spend tier.
4. Identify role: rally lead, joiner, opener, fighter, defender, logistics, alliance officer.
5. Identify target mode.
6. Browse current sources if the answer depends on a patch, meta, hero generation, or profession balance.

## Output Standard

Each researched product should produce:

1. `context/game_mechanics/<game>_mechanics.md`
2. A dated current snapshot when live data matters.
3. Source-index entries with reliability notes.
4. Open questions for the next pass.
5. A short Q&A mental model.

## Quality Bar

A mechanism conclusion is useful only if it answers:

1. What player behavior does this system create?
2. Which bottleneck does it impose?
3. How does it connect to alliance/social structure?
4. How does it monetize?
5. What can a non-whale still optimize?
6. What must be verified before giving current advice?

