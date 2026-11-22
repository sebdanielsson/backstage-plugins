---
'@dweber019/backstage-plugin-tips': patch
---

Annotate `tipsConfigRef` with `ApiRef` from `@backstage/core-plugin-api` so the published type definitions no longer import the undeclared `@backstage/frontend-plugin-api`, and declare `@types/react` as an optional peer dependency, since the published type definitions use React types.
