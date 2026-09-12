# LunFengChen fork

Maintainer: LunFengChen

Upstream: https://github.com/vectorize-io/hindsight/tree/main/hindsight-integrations/coding-agents

This repository is the xfdsh preinstall source. It is not the upstream Vectorize product repo.

## Local patch baked in

`dist/dsh.js` pipes git stderr. Opening a non-git workspace no longer prints:

```
fatal: not a git repository (or any of the parent directories): .git
```

## Default in xfdsh

xfdsh still defaults Hindsight to a local daemon. Cloud remains optional in `~/.hindsight/coding-agent.json`.
