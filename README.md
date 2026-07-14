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

Reference source deck, kept outside the repo:

`C:\Users\jie.wang\Documents\xwechat_files\a27246266_9b52\msg\file\2026-06\SLG山头讨论_20250923.pdf`

Raw decks and extracted full text should not be committed unless explicitly approved.

## Repo Structure

- `context/`: distilled working context and category notes.
- `workflows/`: reusable agent workflows for future category analysis.
- `templates/`: deck / memo templates.
- `prompts/`: prompts for starting a new AI thread with the right context.
- `sources/`: source manifest only; no raw confidential files by default.

Key context notes:

- `context/agent_brief.md`: first-read entry point for routing SLG questions across context files, stable conclusions, volatile claims, and answer protocols.
- `context/topic_index.md`: catalog of major topics, when to use each note, and which files to read.
- `context/decision_log.md`: record of major framework decisions, status, rationale, and implications.
- `context/slg_deck_digest.md`: distilled thesis and teardown framework for the SLG source deck.
- `context/slg_deck_page_by_page_walkthrough.md`: page-by-page walkthrough of the SLG source deck, kept as a digest rather than a transcript.
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
