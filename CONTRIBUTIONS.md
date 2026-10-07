# Open source contributions

This page lists my open source contributions. The newest item is at the top. Each link shows the current status.

| Date | Project | Contribution | Link |
| --- | --- | --- | --- |
| 2026-10-07 | Rush (microsoft/rushstack) | Rush alerts no longer break `--json` and `--quiet` output (issue #5228) | [PR #6118](https://github.com/microsoft/rushstack/pull/6118) |
| 2026-10-07 | TypeORM | A fix for TS2589 in `QueryDeepPartialEntity` with self-containing JSON types (issue #8559). whyts found the cause | [PR #12943](https://github.com/typeorm/typeorm/pull/12943) |
| 2026-10-07 | AWS Durable Execution SDK for JavaScript | A fix for two serialization round-trip inconsistencies in `waitForCondition` (issue #877) | [PR #974](https://github.com/aws/aws-durable-execution-sdk-js/pull/974) |
| 2026-10-07 | TanStack Form | A fix for TS2589 in `DeepKeys` and `DeepValue` with self-referencing types (issues #1474 and #1484). Measured with whyts: 7.4 s to 0.06 s of Check time | [PR #2422](https://github.com/TanStack/form/pull/2422) |
| 2026-10-07 | Lighthouse | Root cause and a fix proposal for a null SEO score when `/robots.txt` returns 304 or 300 (issue #17268) | [Comment](https://github.com/GoogleChrome/lighthouse/issues/17268#issuecomment-6032216277) |
| 2026-10-06 | TypeScript | Measurements and a root cause for slow auto-imports with large package exports (issue #62230) | [Comment](https://github.com/microsoft/TypeScript/issues/62230#issuecomment-6017645478) |
| 2026-10-05 | typescript-eslint | Tests that check the source order of visitor keys (issue #11282) | [PR #12971](https://github.com/typescript-eslint/typescript-eslint/pull/12971) |
| 2026-10-05 | TypeScript | A fix for linked editing in incomplete JSX property tags with attributes (issue #56669) | [PR #64643](https://github.com/microsoft/TypeScript/pull/64643) |
| 2026-10-05 | TypeScript | Tests for an installed JSX runtime package, sent to the author of the fix for issue #64445 | [PR #1](https://github.com/sh011/TypeScript/pull/1) |

## My own projects

- [whyts](https://github.com/musatoktas/whyts): Find out why your TypeScript project is slow.
