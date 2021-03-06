# Changelog

## `2.1.3`

:bug: Bugfix:

  - Fix models not being observable after `add`

## `2.1.2`

:bug: Fixes:

  - Added `transform-runtime`

## `2.1.1`

:bug: Fixes:

  - Removed need for a runtime by using babel's `transform-async-to-generator`

## `2.1.0`

:rocket: New features:

  - Add `isRequest` for models (it was already in `Collection`).
  - Add `primaryKey` so you can use a different key than `'id'`.

:wrench: Tooling:

  - Add `prettier-standard`
  - Add flow linting
  - Set test coverage
