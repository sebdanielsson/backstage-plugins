---
'@dweber019/backstage-plugin-endoflife': patch
---

Declare the dependencies that the plugin only got through hoisting. `@types/react` is now an optional peer dependency, since the published type definitions use React types. `component-emitter`, `propagating-hammerjs` and `uuid` are now dependencies, since `vis-timeline` and `vis-data` require them as peers. `endOfLifeApiRef` is now typed with `ApiRef` from `@backstage/core-plugin-api`, so the published type definitions no longer import the undeclared `@backstage/frontend-plugin-api`.
