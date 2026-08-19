---
name: source-library-research
description: Search the workspace high-quality source library and turn it into verified research briefs, topic lists, claim-evidence-limit tables, or X drafts. Use when the user asks for sources, RSS research, cross-disciplinary discovery, fact checking, topic selection, research briefs, or source-backed X content.
category: analysis
symbolName: books.vertical.fill
seedVersion: 1
---

# Source Library Research

Use the shared source library as a discovery index, then verify every publishable claim at its current original source.

## Library location

Read these workspace-root files before substantive use:

1. `high-quality-source-library/START_HERE_AGENT.md`
2. `high-quality-source-library/manifest.json`
3. `high-quality-source-library/source_catalog.json`
4. `high-quality-source-library/human_guide_zh.md` when the task touches health, psychology, business, growth, copyright, or publication safety

Use `source_library.xlsx` for human browsing and the OPML files for subscription workflows. Prefer `source_catalog.json` for machine filtering.

Two add-on layers sit beside the main catalog. Read them only when the task needs them:

- `high-quality-source-library/visual_frontier_projects/visual_sources.json` (136 entries, snapshot 2026-08-18) for paper demo videos, interactive demos, personal portfolios, and visual-discovery platforms. `visual_score` measures visual density; `evidence_score` measures strength as factual proof. They are independent — a high `visual_score` never substitutes for evidence.
- `high-quality-source-library/visual_frontier_projects/courses/course_sources.json` (167 entries, snapshot 2026-08-19) for university, institutional, and individual courses. `visual_strength`, `project_strength`, and `evidence_strength` are three independent axes. 40 entries are marked `is_resource_curator` — those are discovery directories, not courses; follow their links to a specific course page. Read `courses/LEARNING_PATHS.md` for sequenced paths and `courses/RESOURCE_CURATORS.md` only when hunting new course leads.

Course and visual entries carry the same verification duty as the main catalog: confirm open status, cost, dates, instructor, and licence at the current course or project page before publishing anything about them. Only 11 unique valid feeds exist across the course layer; the remaining entries are platform entrances, not subscribable feeds.

## Source responsibility

Assign each selected source one role. Do not let a weaker role silently carry a stronger claim.

1. **Evidence source**: original research, systematic reviews, official records, primary data, databases, laws, judgments, or first-party documentation.
2. **Explanation source**: expert institutions, researchers, or high-quality journalism that explains evidence.
3. **Opinion source**: a named author's interpretation. Attribute it explicitly.
4. **Lead source**: discovery only. Follow its links to the original material.
5. **Inspiration source**: structure, visual language, or creative reference. Do not use it as factual proof.

Use this default order: evidence → explanation → opinion → lead → inspiration.

## Workflow

### 1. Shape the question

Identify the topic, audience, desired output, freshness requirement, geography, and any safety or copyright boundary. Infer reasonable defaults instead of asking unless the missing choice materially changes the result.

### 2. Filter the catalog

Filter by `category`, `subcategory`, `citation_role`, `priority`, `score`, `feed_status`, and `x_use`. Read `why`, `verify_note`, and `validation_note` before selecting a source.

Treat rankings and scores as reading priority, not proof of truth.

### 3. Build a source mix

For a factual output, start with at least one evidence source. Add explanation sources for accessibility and opinion sources only when the perspective itself matters. Use lead and inspiration sources to widen discovery, never to close verification.

Prefer a small, strong source set over a long unranked list.

### 4. Re-verify on the live original

Open the current article, paper, dataset, official page, law, judgment, or first-party documentation. Re-check:

- author or issuing institution
- publication and update date
- claim context and definitions
- sample, method, units, and comparison baseline
- limitations and counter-evidence
- current link status
- copyright and media-use conditions

For “latest,” “today,” “current,” prices, policies, statistics, rankings, or research progress, live verification is mandatory.

Do not cite a catalog row, RSS address, feed status, snippet, or score as evidence.

### 5. Produce the requested output

#### Research brief

- Reader benefit
- Core finding with confidence
- Evidence
- Explanation or context
- Limits and counterpoints
- Recommended next action
- Current original-source links

#### Topic list

For each topic include:

- angle
- why it matters now
- target reader
- best evidence source
- best explanation source
- verification still needed
- suitable output format

#### Claim–evidence–limit table

| Claim | Role | Current original source | Evidence | Limit / uncertainty | Status |
|---|---|---|---|---|---|

Mark status as `verified`, `partially verified`, or `unverified`.

#### X draft

State the useful thing first. Keep facts, explanation, and opinion visibly distinct. Put specific original links on their own lines when links are required. Run the workspace `x-post-copy-standard` skill before final copy for `@KeWai386772`.

Do not write RSS URLs into the post body as if they were evidence.

## Karpathy subset wording

Use this exact meaning: **“Karpathy shared HN 2025 RSS starter set.”**

The 92 entries were converted to OPML by emschwartz from Michael Lynch's 2025 Hacker News personal-blog ranking and then shared by Karpathy. Do not say Karpathy personally reviewed, selected, or endorsed every source.

## Sensitive domains

For psychology and health, prioritize guidelines, systematic reviews, professional institutions, and original studies. Do not turn population findings into individual diagnosis or treatment advice.

For personality, cognition, and emotional-intelligence measures, check validity and cultural applicability.

For business and growth cases, identify survivorship bias, incentives, base rates, and conditions that may not transfer.

For law, distinguish jurisdiction, authority level, effective date, and whether a source is legislation, regulation, guidance, judgment, commentary, or news.

## Completion gate

A result is ready only when:

- selected sources have explicit citation roles;
- each publishable factual claim has a current original source;
- freshness and limitations have been checked;
- unverifiable claims are removed or labeled;
- links point to specific originals rather than directory entries or feeds;
- any public copy has passed the relevant copy and media review skills.
