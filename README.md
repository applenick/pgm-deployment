# pgm-deployment

Automatically publishes Maven artifacts from the latest
[`PGMDev/PGM`](https://github.com/PGMDev/PGM) `dev` build to https://repo.pgm.fyi

The workflow runs hourly and publishes only when the upstream
commit changes, and records a commit only after publication succeeds. PGM's source and artifact
metadata are not modified.

## Published artifacts

- `tc.oc.pgm:core:0.16-SNAPSHOT`
- `tc.oc.pgm:util:0.16-SNAPSHOT`


