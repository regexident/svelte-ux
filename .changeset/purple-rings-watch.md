---
'svelte-ux': minor
---

[movable action] Extend `movable` action's event detail type and export it as `MoveDetail`:

- Change type of `dx` & `dy` fields from `number | undefined` to `number`, defaulting to `0`.
- Add `sourceEvent: MouseEvent` field for accessing underlying source event.
- Add `active: number` field for future-proofing users' listener-implementations.
- Add `identifier: string | number` field to `MoveDetail`
