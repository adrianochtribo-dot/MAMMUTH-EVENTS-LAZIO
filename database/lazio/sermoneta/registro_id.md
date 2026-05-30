# REGISTRY ID - KWF / ATLAS•EVENTA

Authoritative sequential ledger for entity uniqueness.

## Operational Rules
* EVENT_INDEX: Sequential numerical ID (Start: 1).
* CONSTRAINT: Creation of skipped, duplicated, or reordered IDs is strictly prohibited.
* AUTHORITY: In case of ambiguity, initiate HARD-STOP and manual reconciliation.
* CURRENT STATUS: Last valid ID = 1.
