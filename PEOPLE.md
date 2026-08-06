# People

Employee roster for libnudget.

Employee IDs follow the scheme `LN-001`, `LN-002`, and so on — a simple,
zero-padded, sequential number. The prefix `LN` is the company; the number
is assigned in order of joining; leading zeros keep the IDs sortable.

New employees take the next unused number in the sequence. Never skip or
reuse a number.

## Roster

| Employee ID | Name | GitHub | Role |
| --- | --- | --- | --- |
| LN-001 | bniladridas | [@bniladridas](https://github.com/bniladridas) | Founder · Maintainer |
| LN-002 | gpucomm-hq | [@gpucomm-hq](https://github.com/gpucomm-hq) | Maintainer |

## Issuing the next ID

The next ID to assign is found by taking the highest existing number and
adding one, then zero-padding to three digits. The next free ID is
**`LN-003`**.

To add a person, add a row above with their ID, name, GitHub handle, and
role, then update the "next free ID" note.