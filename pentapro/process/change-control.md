# PROCESS · Change Control

PentaPRO is the repository's canonical specification and change workflow. Keep the five-pillar baseline in `pentapro/` and material proposed or in-progress changes in `pentapro/changes/<name>/`.

For each material change, state the outcome, scope, exclusions, and affected subprojects. Record observable success and failure scenarios in PRODUCT, design and contracts in PROJECT, operating effects in PRODUCTION, feasible checks and actual revision-bound evidence in PROOF, and owners, decisions, tasks, and next action in PROCESS. Link shared records rather than duplicating their content.

For user-facing behavior shared by Android and the landing page, include both subprojects in one change and specify acceptance scenarios for both. A platform-only scope or intentional difference must be explicit. Keep project artifacts in English; localized app strings use their target language.

Routine, reversible edits may use the local contract and a focused check. A specification draft, review, or accepted change does not by itself authorize implementation, product acceptance, release, or distribution. Archive a change only after its accepted outcome is reconciled into affected pillars and the required evidence is recorded.
