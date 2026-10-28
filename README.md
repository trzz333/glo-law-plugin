# GLO Law

GLO Law gives Claude a free U.S. legal research library for people working the legal system without a lawyer, and for the families, reentry programs and defenders who help them.

This plugin has two parts:

- **The GLO Law connector** (`https://mcp.glolaw.org/mcp`): read-only tools over nearly 11 million court opinions, U.S. Code and state statute sections, state regulations and the Code of Federal Regulations, and department of corrections policies. Every answer carries a note on its source and how far its coverage reaches.
- **The `glo-law-research` skill**: teaches Claude which GLO Law tool fits which question, how to chain them, and how to report coverage limits honestly.

## Install

In Claude, add GLO Law from the directory. The plugin listing installs the connector and the skill together.

## What it sends and fetches

The plugin runs no local code. Claude sends your research queries (case names, keywords, citations, statute or policy numbers, and any brief text you ask it to check) to `mcp.glolaw.org`, operated by Eden Bound LLC. GLO Law takes a Google sign-in and doesn't log your searches. Privacy policy: https://glolaw.org/privacy

## Limits

GLO Law is a research tool, not legal advice. Case law runs through the snapshot date each response states. No tool says whether a case is "good law". An empty result is not proof that something doesn't exist.

Support: info@glolaw.org
