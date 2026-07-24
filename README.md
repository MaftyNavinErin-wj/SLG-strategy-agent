# SLG Strategy Agent

This repo is a working memory and workflow scaffold for building "mountain discussion" strategy materials for game categories, starting with mobile SLG.

The goal is not generic market research. The target output should help Tencent IEG BD / strategy discuss:

1. Why a category exists.
2. How its internal "mountains" / sub-paradigms are defined.
3. Which products and teams changed the paradigm.
4. Where future opportunities may come from.
5. What coverage, research, and diligence should happen next.

## Current Focus

Starting category: SLG mobile games.

Primary internal benchmark deck, explicitly approved for this private repo:

`sources/reference_decks/derrick_slg_mountain_20250923.pdf`

This deck represents the September 2025 IEG SLG mountain baseline. New research should state whether it confirms, refines, or conflicts with that baseline. Raw decks and extracted full text should otherwise not be committed unless explicitly approved.

## Repo Structure

- `context/`: distilled working context and category notes.
- `workflows/`: reusable agent workflows for future category analysis.
- `templates/`: deck / memo templates.
- `prompts/`: prompts for starting a new AI thread with the right context.
- `sources/`: source manifests, public-research indexes, and explicitly approved internal benchmark material.

Key context notes:

- `context/agent_brief.md`: first-read entry point for routing SLG questions across context files, stable conclusions, volatile claims, and answer protocols.
- `context/topic_index.md`: catalog of major topics, when to use each note, and which files to read.
- `context/decision_log.md`: record of major framework decisions, status, rationale, and implications.
- `context/slg_deck_digest.md`: distilled thesis and teardown framework for the SLG source deck.
- `context/slg_deck_page_by_page_walkthrough.md`: page-by-page walkthrough of the SLG source deck, kept as a digest rather than a transcript.
- `context/derrick_deck_benchmark.md`: authority, page map, and discrepancy protocol for using the September 2025 IEG view as a benchmark rather than an unquestioned truth.
- `context/slg_framework_deepening_and_thesis_agenda.md`: current simplified architecture: Tier 0 AGR, Tier 1 structural support, Tier 2 local optimization, plus theme and entry / UA as adjacent research modules.
- `context/slg_output_hypotheses.md`: output-layer hypotheses for activity, monetization, payer structure, retention, and ecology, benchmarked against the deck's conclusions and numbers.
- `context/slg_representative_games_research_findings.md`: current synthesis of research method conclusions and representative product findings.
- `context/slg_representative_mechanics_overview.md`: first-pass mechanism comparison for representative SLG products, currently 无尽冬日, 率土之滨, 三国志战略版, and 三国谋定天下.
- `context/slg_internal_taxonomy_2x2x2.md`: working 2x2x2 for SLG power constraints: body attrition / repeated-use cost, geo dependency / spatial reach, and season reset / temporal persistence, with vertical-horizontal power and monetization treated as downstream outcomes.
- `context/grand_strategy_4x_live_service_tensions.md`: working note on why PC / console grand strategy and 4X design only partially merge with mobile SLG live-service logic.
- `context/game_mechanics/`: per-game public-source mechanism notes.
- `sources/public_research/`: public source indexes and reliability notes.

Key workflows:

- `workflows/mountain_discussion_agent_workflow.md`: broad category / mountain discussion workflow.
- `workflows/slg_mechanics_research_workflow.md`: reusable workflow for deep SLG mechanism research and current-meta handling.

## Working Principle

Analyze a category through:

`category definition -> historical sources -> mountain split -> market structure -> product mechanics -> user / traffic -> team capability -> future opportunities -> coverage implications`
