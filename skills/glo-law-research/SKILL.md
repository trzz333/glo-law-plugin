---
name: glo-law-research
description: Use when the person asks for U.S. legal research with the GLO Law tools — finding or reading a court opinion, checking a citation or brief, looking up a statute or state regulation, searching department of corrections policies, or counting a Kansas or federal court deadline — especially for pro se litigants and people in reentry.
---

# Legal research with GLO Law

The GLO Law tools are read-only. They search a dated mirror of CourtListener case law plus separate snapshots of statutes, regulations and corrections policies. They never say whether a case is still good law.

## Pick the tool by the question

- A case by name: `search`. A reporter citation such as "289 Kan. 642": `citation`.
- Exact words in opinions: `fts` (no stemming, so try word variants). A concept: `semantic_search`, which covers only part of the corpus and can return 503 when its service is down.
- Read a case: `cluster` for the case record, `opinion` for full text. Similar wording: `similar`.
- What a case cites, or who cites it: `citations` (add `with_passages` for the citing court's own sentences). How later courts described it: `parentheticals`.
- Whether a later court overruled, reversed or vacated it: `treatment`. Every citation in a pasted brief: `brief_check`.
- A statute or regulation by citation: `statute`. By words: `statute_search` (pass `jurisdiction` or `source`, or results mix states). Opinions citing a federal statute section: `statute_citing`.
- Prison or corrections policies by number or keyword: `corrections_policy`. These are internal policies, not law.
- A court or grievance deadline from a date: `deadline` (Kansas K.S.A. 60-206, KDOC grievances K.A.R. 44-15-101b, FRCP 6, FRAP 26, 28 U.S.C. 2107(a)).
- What a source covers, its citation forms and counts: `sources`.

## Report honestly

- Quote each response's `note` and `coverage_note` limits when they bear on the answer: the case-law end date, a regulation's `as_of`, partial coverage.
- An empty result means GLO Law didn't find it, never that it doesn't exist.
- `treatment` and `brief_check` report only negative history a court stated, in that court's words. No result there means nothing; say so.
- Quote courts' own words for holdings and parentheticals. Don't paraphrase a quotation as if it were one.
- Show citations exactly as the court wrote them. An unresolved citation is "not in the current snapshot", not a different case.
- Say the person should read the source themselves and that this is research, not legal advice.

## Problems with GLO Law

Point the person to https://glolaw.org/feedback?from=connector. No tool sends feedback.
