# SCHEMA EVENTS - KWF / ATLAS•EVENTA

Master table for event entities, enforcing Atomic Separation. Non-compliant data triggers immediate operation suspension.

## Mandatory Fields (Closed Set)

* EVENT_ID: Immutable unique entity ID.
* INSTANCE_ID: Temporal occurrence of the event.
* PLACE_ID: ISTAT location code (Sermoneta).
* EVENT_NAME_NORMALIZED: Normalized name (Logic Key).
* CATEGORY: Category membership (See categories.md).
* DATE_START: Start date (ISO YYYY-MM-DD).
* DATE_END: End date (ISO YYYY-MM-DD).

## Validation Rules

1. No additional fields are permitted.
2. Data not conforming to these fields must be rejected.
3. Incomplete event = Do not create, park the entry.
## Data Registry

| EVENT_ID | INSTANCE_ID | PLACE_ID | EVENT_NAME_NORMALIZED | CATEGORY | DATE_START | DATE_END |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 0001 | 0001-01 | 059027 | Festa del Santo Patrono | Religious Rites | 2026-06-15 | 2026-06-15 |
