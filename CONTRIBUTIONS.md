# Open source contributions

This page lists my open source contributions. The newest item is at the top. Each link shows the current status.

## Merged

| Date merged | Project | Contribution | Link |
| --- | --- | --- | --- |
| 2026-10-13 | AWS CDK CLI | Nested evaluators now share one `ListStackResources` list per stack (issue #2039) | [PR #2040](https://github.com/aws/aws-cdk-cli/pull/2040) |
| 2026-10-11 | AWS Durable Execution SDK for JavaScript | A fix for two serialization round-trip inconsistencies in `waitForCondition` (issue #877) | [PR #974](https://github.com/aws/aws-durable-execution-sdk-js/pull/974) |
| 2026-10-10 | Qwik | Fix the default excluded `/manifest.json` path of the Netlify Edge adapter (issue #8113) | [PR #9187](https://github.com/QwikDev/qwik/pull/9187) |

## All contributions

| Date | Project | Contribution | Link |
| --- | --- | --- | --- |
| 2026-10-14 | AWS CDK CLI | Template parsing accepts duplicate keys in JSON templates, as CloudFormation does (issue #1911) | [PR #2043](https://github.com/aws/aws-cdk-cli/pull/2043) |
| 2026-10-14 | cognito-at-edge | With `csrfProtection` enabled, the post-login redirect now uses the requested path instead of a doubled host (issues #120 and #108) | [PR #154](https://github.com/awslabs/cognito-at-edge/pull/154) |
| 2026-10-13 | Renovate | A fix for issues not found when Renovate runs as a GitHub App bot: issues are now filtered by author in code (issue #44730) | [PR #47013](https://github.com/renovatebot/renovate/pull/47013) |
| 2026-10-13 | Vuetify | Measurements of the cost of the proposed change in #23266 on `createVuetify`: memory 562-593 MB to 178-187 MB, check time 3.8 s to 1.4 s (issue #23005) | [Comment](https://github.com/vuetifyjs/vuetify/issues/23005#issuecomment-6143458137) |
| 2026-10-12 | Vue | A fix for the slow type check with `defineModel` and a `void` `defineEmits` signature (issue #14323). whyts found the cause. vue-tsc: 80 s to 0.56 s | [PR #15851](https://github.com/vuejs/core/pull/15851) |
| 2026-10-12 | AWS CDK CLI | Nested evaluators now share one `ListStackResources` list per stack (issue #2039). Merged | [PR #2040](https://github.com/aws/aws-cdk-cli/pull/2040) |
| 2026-10-11 | ZenStack | Measurements of the type cost of `update()` from 3.6.4 to 3.9.7: two regressions, in 3.7.0 and 3.9.0 (issue #2854) | [Comment](https://github.com/zenstackhq/zenstack/issues/2854#issuecomment-6106510035) |
| 2026-10-11 | tRPC | A fix for TS2589 in `Serialize` with recursive JSON types such as `Prisma.JsonValue` (issue #6997). whyts found the cause | [PR #7660](https://github.com/trpc/trpc/pull/7660) |
| 2026-10-09 | node-redis | Measurements of type-check memory for cluster and client unions from 4.7.0 to 6.3.0, and a test of variance annotations (issue #2975) | [Comment](https://github.com/redis/node-redis/issues/2975#issuecomment-6081025083) |
| 2026-10-09 | Hono | A fix for TS2589 in `JSONParsed` with recursive JSON types (issue #2399). whyts found the cause. The fix keeps the `.d.ts` output at 762 bytes, where a depth limit gives 313,638 bytes | [Issue #5543](https://github.com/honojs/hono/issues/5543) |
| 2026-10-08 | Qwik | Fix the default excluded `/manifest.json` path of the Netlify Edge adapter (issue #8113). Merged | [PR #9187](https://github.com/QwikDev/qwik/pull/9187) |
| 2026-10-07 | Rush (microsoft/rushstack) | Rush alerts no longer break `--json` and `--quiet` output (issue #5228) | [PR #6118](https://github.com/microsoft/rushstack/pull/6118) |
| 2026-10-07 | TypeORM | A fix for TS2589 in `QueryDeepPartialEntity` with self-containing JSON types (issue #8559). whyts found the cause | [PR #12943](https://github.com/typeorm/typeorm/pull/12943) |
| 2026-10-07 | AWS Durable Execution SDK for JavaScript | A fix for two serialization round-trip inconsistencies in `waitForCondition` (issue #877). Merged | [PR #974](https://github.com/aws/aws-durable-execution-sdk-js/pull/974) |
| 2026-10-07 | TanStack Form | A fix for TS2589 in `DeepKeys` and `DeepValue` with self-referencing types (issues #1474 and #1484). Measured with whyts: 7.4 s to 0.06 s of Check time | [PR #2422](https://github.com/TanStack/form/pull/2422) |
| 2026-10-07 | Lighthouse | Root cause and a fix proposal for a null SEO score when `/robots.txt` returns 304 or 300 (issue #17268). The maintainers fixed it in [#17294](https://github.com/GoogleChrome/lighthouse/pull/17294) | [Comment](https://github.com/GoogleChrome/lighthouse/issues/17268#issuecomment-6032216277) |
| 2026-10-06 | TypeScript | Measurements and a root cause for slow auto-imports with large package exports (issue #62230) | [Comment](https://github.com/microsoft/TypeScript/issues/62230#issuecomment-6017645478) |
| 2026-10-05 | TypeScript | A fix for linked editing in incomplete JSX property tags with attributes (issue #56669) | [PR #64643](https://github.com/microsoft/TypeScript/pull/64643) |
| 2026-10-05 | TypeScript | Tests for an installed JSX runtime package, sent to the author of the fix for issue #64445 | [PR #1](https://github.com/sh011/TypeScript/pull/1) |

## My own projects

- [whyts](https://github.com/musatoktas/whyts): Find out why your TypeScript project is slow.
