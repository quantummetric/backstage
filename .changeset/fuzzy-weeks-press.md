---
'@backstage/plugin-circleci': patch
---

Added an optional ESLint rule - no-top-level-material-ui-4-imports - in CircleCI plugin which has an auto fix function to migrate the imports and used it to migrate the Material UI imports for `plugins/circleci`.
