# LunFengChen fork

Maintainer: LunFengChen

Upstream: https://github.com/vectorize-io/hindsight/tree/main/hindsight-integrations/coding-agents

This repository is the xfdsh preinstall source. It is not the upstream Vectorize product repo.

## Local patch baked in

`dist/dsh.js` pipes git stderr. Opening a non-git workspace no longer prints:

```
fatal: not a git repository (or any of the parent directories): .git
```

## Default

This fork defaults `serverMode` to `daemon`. Memory lives in `~/.hindsight`. Cloud or a self-hosted URL remains optional in `~/.hindsight/coding-agent.json`.
