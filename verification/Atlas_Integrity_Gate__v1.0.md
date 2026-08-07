---
title: "Verification — Atlas Integrity Gate"
artifact_type: "Checklist"
version: "v1.1"
status: "ACTIVE"
last_updated: "2026-08-07"
tags: ["verification", "checklist", "citation", "metadata"]
---

# Pass/Fail Gate: Atlas Integrity

## A) Canonical landing discipline
- [ ] Each work page lists a **Zenodo DOI** as the cite-this landing — version DOI for an exact release, concept DOI for the corpus
- [ ] Series index lists the Zenodo **concept** DOI
- [ ] GitHub is described as version history, not a primary publication venue
- [ ] Where no DOI has been minted, the page says so plainly rather than showing a placeholder

## B) Metadata parity
- [ ] Title spine matches across Zenodo, the GitHub landing page, and `CITATION.cff`
- [ ] Author string matches exactly
- [ ] Keyword spine ordering matches across volumes in a series

## C) PDF hygiene
- [ ] Searchable/selectable text
- [ ] Title + author line on page 1
- [ ] References section present
- [ ] Stated licence in the PDF front matter matches the repository `LICENSE`

## D) Identifier resolution
- [ ] Every DOI on the page resolves, and shows the expected title and authors
- [ ] Version DOIs are distinguished from the concept DOI and not used interchangeably
- [ ] ORCID record lists the work

## E) Anti-duplication
- [ ] No competing primary PDFs across multiple landing pages
- [ ] This index links to source repos; it does not host their release assets

## F) Public-surface hygiene
- [ ] No internal project tags, confidentiality classes, author codes, or timezones in front matter
- [ ] No internal identifiers or file paths
- [ ] No links to private or non-existent repositories
