# Bracken Quay Cooperative Ledger

This repository preserves the close-of-day account evidence and release records.

<!-- CLOSEOUT:BEGIN -->
## Daily close — 12 April 2160
Events: 18 physical | 12 valid | 6 invalid
Decisions: 9 accepted | 3 rejected valid
Accepted value: 135 charged | 70 paid
Balances: 105 opening | 170 final

| Account | Member | Limit | Opening | Final |
| --- | --- | --- | --- | --- |
| AC-101 | Alder Works | 100 | 25 | 35 |
| AC-204 | Birch Studio | 60 | 10 | 35 |
| AC-330 | Cedar Market | 40 | 0 | 35 |
| AC-407 | Dune Repair | 75 | 70 | 65 |

### Rejected valid events
| Event | Account | Kind | Amount | Balance before | Reason |
| --- | --- | --- | --- | --- | --- |
| EV-004 | AC-204 | CHARGE | 20 | 50 | LIMIT_EXCEEDED |
| EV-009 | AC-101 | CHARGE | 70 | 35 | LIMIT_EXCEEDED |
| EV-010 | AC-330 | CHARGE | 10 | 35 | LIMIT_EXCEEDED |
<!-- CLOSEOUT:END -->

## Custody

Source records are immutable after sealing.
