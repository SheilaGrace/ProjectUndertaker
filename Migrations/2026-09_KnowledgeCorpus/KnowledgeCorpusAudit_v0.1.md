---
record_id: PU-2026-KNOWLEDGE-AUDIT-001
title: Project Undertaker Knowledge Corpus Audit
version: 0.1-draft
created: 2026-09-20
record_type: corpus_migration_audit
status: draft
migration_branch: migration/knowledge-corpus-2026-09
---

# Project Undertaker Knowledge Corpus Audit v0.1

## 0. Purpose

This document audits the current Project Undertaker corpus
before large-scale restructuring.

Its purpose is to determine:

- what each existing file is for,
- whether it remains current,
- whether it should remain canonical,
- whether it should be moved,
- whether it should be merged,
- whether it should be superseded,
- whether it requires privacy or consent review,
- and what dependencies may break if it is relocated.

Preserve first.

Move second.

Merge only after the source Records are preserved.


# 1. Status Vocabulary

## KEEP

The file remains useful and can stay conceptually unchanged.

## MOVE

The file remains useful but belongs in a different directory.

## MERGE

The file overlaps substantially with another file
and may contribute to a new canonical document.

The original source file should remain preserved in Archive.

## SUPERSEDE

The file contains outdated or no-longer-canonical information.

It should remain preserved as historical evidence,
but a newer canonical document should replace it for normal use.

## ARCHIVE

The file should no longer be part of the normal reading path,
but should remain preserved.

## PRIVACY REVIEW

The file contains information that may require
consent, anonymization, access control, or restricted handling.

## UNKNOWN

The file has not yet been reviewed sufficiently.


# 2. Audit Fields

For each file, record:

- Current Path
- Current Purpose
- Current Status
- Proposed Action
- Proposed Destination
- Canonical Replacement
- Privacy / Consent Concerns
- Dependencies
- Notes


# 3. File Audit

## Entry Template

### [Filename]

**Current Path:**  
**Current Purpose:**  
**Current Status:** UNKNOWN  
**Proposed Action:** UNKNOWN  
**Proposed Destination:**  
**Canonical Replacement:**  
**Privacy / Consent Concerns:**  
**Dependencies:**  
**Notes:**  


# 4. Migration Principles

Do not delete historical source material merely because it is outdated.

Do not silently replace old interpretation with new interpretation.

Do not merge records before preserving their original forms.

Do not expose private or consent-sensitive information
merely because it is useful for reconstruction.

Canonical documents should be easy to identify.

Historical documents should remain recoverable.

The corpus should remain usable without depending on one specific model,
vendor, interface, or product feature.


# 5. Migration Sequence

1. Inventory existing files.
2. Classify each file.
3. Identify dependencies.
4. Identify privacy and consent risks.
5. Design destination structure.
6. Move files.
7. Create merged or canonical replacements.
8. Update manifests and reading order.
9. Verify links and references.
10. Commit and document the migration.