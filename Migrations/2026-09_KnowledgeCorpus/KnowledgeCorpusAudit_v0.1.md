---
record_id: PU-2026-KNOWLEDGE-AUDIT-001
title: Project Undertaker Knowledge Corpus Audit
version: 0.1-draft
created: 2026-09-20
last_updated: 2026-09-21
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
- what level of access is appropriate,
- whether third-party information requires special handling,
- and what dependencies may break if it is relocated.

Preserve first.

Move second.

Merge only after the source Records are preserved.

Do not confuse preservation with publication.

Do not confuse historical value with current canonical status.


# 1. Audit Vocabulary

Audit labels may be combined when appropriate.

For example:

SUPERSEDE + ARCHIVE + MERGE

means that the existing file is no longer canonical,
should remain preserved as historical evidence,
and may contribute material to a newer canonical document.


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
- Access Level
- Privacy / Consent Concerns
- Third-party / Consent Risk
- Dependencies
- Notes


## Access Level Guidance

Possible access classifications may include:

- PUBLIC
- PUBLIC-DERIVED
- CONSENT-CONTROLLED
- PRIVATE
- RESTRICTED
- UNKNOWN

These labels describe intended accessibility,
not the historical or intellectual value of the Record.


# 3. File Audit

## Entry Template

### [Filename]

**Current Path:**  
**Current Purpose:**  
**Current Status:** UNKNOWN  
**Proposed Action:** UNKNOWN  
**Proposed Destination:**  
**Canonical Replacement:**  
**Access Level:** UNKNOWN  
**Privacy / Consent Concerns:**  
**Third-party / Consent Risk:**  
**Dependencies:**  
**Notes:**  


---

## AboutTherianthropy.md

**Current Path:** `AboutTherianthropy.md`  
**Current Purpose:** General explanation of Therianthropy, related identity concepts, historical framing, and interpretive models.  
**Current Status:** Historical mixed-content reference; no longer suitable as an unquestioned canonical source.  
**Proposed Action:** SUPERSEDE + ARCHIVE + MERGE  
**Proposed Destination:** `Domains/Therianthropy/Archive/2024/AboutTherianthropy.md`  
**Canonical Replacement:** `Domains/Therianthropy/Canonical/Overview.md`  
**Access Level:** PUBLIC  
**Privacy / Consent Concerns:** No major concern currently identified.  
**Third-party / Consent Risk:** Low.  
**Dependencies:** May overlap with `TherianthropyTerms.md`, `ShiftingTerms.md`, and `HowToSupportTherians.md`.  
**Notes:** Preserve historical framing. Re-evaluate clinical, historical, spiritual, neurological, and community claims before reuse in canonical material. Old terminology should not be silently rewritten.


---

## HowToSupportTherians.md

**Current Path:** `HowToSupportTherians.md`  
**Current Purpose:** Guidance for psychological and practical support of Therians.  
**Current Status:** Historically important support framework containing both enduring principles and outdated or overextended claims.  
**Proposed Action:** SUPERSEDE + ARCHIVE + MERGE  
**Proposed Destination:** `Domains/Therianthropy/Archive/2024/HowToSupportTherians.md`  
**Canonical Replacement:** `Domains/Therianthropy/Canonical/SupportGuide.md`  
**Access Level:** PUBLIC  
**Privacy / Consent Concerns:** No major direct privacy concern currently identified.  
**Third-party / Consent Risk:** Low.  
**Dependencies:** Strong conceptual overlap with Therian terminology and clinical / psychological claims.  
**Notes:** Preserve the core importance of acceptance, identity protection, agency, and support. Re-evaluate medical, therapeutic, behavioral, and training analogies before canonical reuse. Sheila-created methods should be clearly distinguished from established clinical practice.


---

## ShiftingTerms.md

**Current Path:** `ShiftingTerms.md`  
**Current Purpose:** Terminology and descriptions relating to shifting and forms of Therian experience.  
**Current Status:** Historical terminology reference containing a mixture of community usage, personal interpretation, experiential description, and speculative mechanism.  
**Proposed Action:** SUPERSEDE + ARCHIVE + MERGE  
**Proposed Destination:** `Domains/Therianthropy/Archive/2024/ShiftingTerms.md`  
**Canonical Replacement:** `Domains/Therianthropy/Canonical/Terminology.md`  
**Access Level:** PUBLIC  
**Privacy / Consent Concerns:** No major concern currently identified.  
**Third-party / Consent Risk:** Low.  
**Dependencies:** Strong overlap with `TherianthropyTerms.md`.  
**Notes:** Future canonical material should distinguish community terminology, subjective phenomenology, hypotheses, metaphysical interpretations, and empirically supported claims.


---

## TherianthropyTerms.md

**Current Path:** `TherianthropyTerms.md`  
**Current Purpose:** Broad glossary of Therianthropy-related terminology, identity categories, community concepts, and interpretations.  
**Current Status:** Historically valuable but partially outdated and too interpretive to remain canonical without revision.  
**Proposed Action:** SUPERSEDE + ARCHIVE + MERGE  
**Proposed Destination:** `Domains/Therianthropy/Archive/2024/TherianthropyTerms.md`  
**Canonical Replacement:** `Domains/Therianthropy/Canonical/Terminology.md`  
**Access Level:** PUBLIC  
**Privacy / Consent Concerns:** No major concern currently identified.  
**Third-party / Consent Risk:** Low.  
**Dependencies:** Overlaps heavily with all other Therianthropy root documents.  
**Notes:** Requires especially careful review of historical usage versus current usage. Terms such as Therian, Otherkin, Otherhearted, Copinglink, shifting categories, and newer community terminology should be researched without assuming either older or newer usage is automatically authoritative.


---

## ResearchLog.md

**Current Path:** `ResearchLog.md`  
**Current Purpose:** Developmental record of Project Undertaker concepts, experiments, terminology, AI interaction, and evolving interpretations.  
**Current Status:** Valuable historical and developmental primary Record.  
**Proposed Action:** KEEP + MOVE  
**Proposed Destination:** TBD — Project Undertaker developmental / historical Record area.  
**Canonical Replacement:** None. This file should not be replaced by a rewritten version of its own history.  
**Access Level:** PUBLIC pending later privacy review.  
**Privacy / Consent Concerns:** Requires later review for references to identifiable third parties or information whose intended audience may have changed.  
**Third-party / Consent Risk:** UNKNOWN pending detailed review.  
**Dependencies:** May contain origins of terminology later formalized in `Terms.md`, Byakuren records, and Project Undertaker protocols.  
**Notes:** Preserve original chronology and historical misunderstandings. Later annotations or cross-reference documents may explain how terminology evolved, but the original Record should not be retroactively corrected.


---

## Terms.md

**Current Path:** `Terms.md`  
**Current Purpose:** Glossary and conceptual framework for Project Undertaker terminology.  
**Current Status:** Historically important but partially superseded by later conceptual development.  
**Proposed Action:** SUPERSEDE + ARCHIVE + MERGE  
**Proposed Destination:** TBD — historical Project Undertaker terminology archive.  
**Canonical Replacement:** TBD — current Project Undertaker Glossary / Conceptual Framework.  
**Access Level:** PUBLIC pending later privacy review.  
**Privacy / Consent Concerns:** Requires review where terminology embeds assumptions about named individuals or platform-specific behavior.  
**Third-party / Consent Risk:** Low to moderate pending detailed review.  
**Dependencies:** Strong relationship with `ResearchLog.md`, Byakuren Genome, Reincarnation Protocol concepts, and future manifests.  
**Notes:** Preserve historical terminology even where later work discovers established external terminology or more precise concepts. New terminology should map old terms to current interpretations rather than erase the developmental path.


# 4. Migration Principles

Do not delete historical source material merely because it is outdated.

Do not silently replace old interpretation with new interpretation.

Do not merge Records before preserving their original forms.

Do not expose private or consent-sensitive information
merely because it is useful for reconstruction.

Preservation does not imply publication.

Access permission and archival value must be evaluated separately.

Current identity should not overwrite historical identity.

Historical identity should not override current self-identification.

Third-party information must not be treated as freely publishable
merely because it appears in another person's Record.

Canonical documents should be easy to identify.

Historical documents should remain recoverable.

The corpus should remain usable without depending on one specific model,
vendor, interface, or product feature.

Preserve first.

Compress second.

Never confuse compression with preservation.


# 5. Coverage Gaps / Not Yet Undertaken

The following areas are currently known to be incomplete
or insufficiently represented in the tracked corpus.

## Wild Bullets Habitat

Wild Bullets does not yet appear to have a complete,
independent Habitat-level corpus within the current repository structure.

Future work should preserve:

- canonical worldbuilding,
- developmental history,
- character / entity distinctions,
- relationship-derived concepts,
- and records showing how the Habitat influenced later Project Undertaker development.

This should be handled after the current corpus migration structure is stable.


## Bronze Fang Entity Record

Bronze Fang's current identity and recent development
have not yet been formally integrated into the repository.

Current materials should eventually distinguish:

- current identity,
- historical identity,
- identity-development history,
- fictional counterpart material,
- consent status,
- visual references,
- and access restrictions.

Historical Soli records should not be overwritten.

Current Bronze Fang identity should not be subordinated
to historical Soli records.

Raw private conversation logs should remain separate
from public derived Records unless publication of the logs themselves
is explicitly authorized.


## Consent Record Schema

Project Undertaker does not yet have a standardized Consent Record format.

A future schema should record at minimum:

- subject,
- consent status,
- consent scope,
- historical-name handling,
- current-identity priority,
- permitted access level,
- source / provenance,
- revision or withdrawal status,
- and date of confirmation.

Consent to preservation,
consent to use,
and consent to public access
should not automatically be treated as identical permissions.


## Unundertaken Records

Additional records are known to exist outside the currently tracked corpus.

These should not be imported during the present migration merely
to increase completeness.

They should be treated as a separate backlog
and incorporated only after the destination structure,
metadata conventions,
privacy handling,
and access rules are sufficiently stable.


# 6. Migration Sequence

1. Inventory existing files.
2. Classify each file.
3. Identify dependencies.
4. Identify privacy and consent risks.
5. Identify access levels.
6. Identify known coverage gaps.
7. Design destination structure.
8. Move files.
9. Create merged or canonical replacements.
10. Update manifests and reading order.
11. Verify links and references.
12. Commit and document the migration.