# CLAUDE.md

This is the working contract for AI assistance in `Productside/Productside-Resources`.

`CONSTITUTION.md` outranks this file. If the two conflict, the Constitution wins.

## What this repository is

A curated index of Productside's public learning resources. The `README.md` is the primary landing page for visitors, and `resources/catalog.yaml` is the structured catalog behind it.

**It is public.** Every file is world-readable by anyone, permanently. There is no draft state.

## Who reads it

Product managers evaluating Productside: prospects, clients, learners, and future hires. Many are not programmers. Several are deciding whether to buy. The README is doing marketing work, so it must be accurate as well as appealing.

## Non-negotiable: Productside is a services firm, not a software company

Productside's client agreements are written for **services**. Describing published materials as "code" or "software" invites counterparties to treat Productside as a software vendor, which attaches software security questionnaires and warranty terms to a training agreement.

Describe repository contents as **digital takeaways and examples that demonstrate and extend Productside's teaching and advisory services**: classes, workshops, webinars, consulting, advisory engagements, and lead generation.

| Term not to use | Term to use instead |
|---|---|
| code, codebase | materials, resources, digital takeaways, files |
| software | *(omit; say "the platform" when you mean GitHub itself)* |
| scripts | prompts, skills, templates |
| your developer | whoever set up the tool, your technical contact |
| app, application | tool |
| deliverable, product | takeaway, example, material |

**Never add a roadmap item, feature promise, or capability claim that reads as a commitment to build or maintain software.** A Scrapling crawler was once advertised in this README's roadmap. It was removed in July 2026 because it read as a software commitment from a company whose contracts say it does not build software. Do not reintroduce that class of claim.

## Naming the people Productside serves

*Students*, *participants*, and *learners* all refer to the people in a class, workshop, or webinar. When a rule enumerates whose data is protected, include **learners** alongside students and participants.

## Legal entity

**280 Group LLC, dba Productside.** Copyright lines and formal legal notices name the entity. Body text may say Productside.

## Voice

- professional and practical, never hype
- plain English over jargon
- claims must be verifiable; if a number or outcome appears, it must be real and sourced
- **no em dashes as clause separators in prose.** Use periods, commas, colons, or parentheses. Em dashes are acceptable only in the `**Term** — definition` list format

## The catalog is hand-maintained

`resources/catalog.yaml` is deliberately curated by hand, not generated. If a resource changes on productside.com, update the catalog to match. Do not propose automating this, and do not describe automation of it in any public file.

## When making changes

1. **Assume it is permanent.** Deleting a file does not remove it from history.
2. **Verify every outbound link.** This repository is a front door; a broken link is a bad first impression.
3. **Only graduated material.** Nothing is published here that was not built and proven internally first, then cleaned and approved.
4. **Never publish Training Deliverables, Foreground IP, or Client IP.** See `CONSTITUTION.md` for why each is excluded.
5. **Keep the footer legal links current** with `LICENSE`, `TRADEMARKS.md`, and the organization legal index.
6. **Human review before merge.** Always.

## Detailed guidance

The full internal manual lives in the private `productside-launchkit` Project. Chapter `02-09 Positioning, Licensing, and Terms` covers the reasoning behind the vocabulary and licensing rules; `01-05 Choosing Where Work Lives` covers how material graduates from private to public.
