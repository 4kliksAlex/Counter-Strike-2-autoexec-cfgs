---
title: CS2 Autoexec autoexec Library from 4kliksAlex (YouTube@2kliksAlex)
---

# *Turbocharge Your Gaming* ;)

Usage: Put these files in the `<Your CS2(CSGO) directory>\game\csgo\cfg\` or your own account\'s equivalent `cfg` folder.

# Design Philosophy

All executions of `autoexec_...` files (exec `_AUTOEXEC\...\autoexec_...`) are done in `autoexec.cfg`.

## File Managemenst

Repeated command lists shall be put in and called from a standalone `cfg` file.

Concatenate files if repeated code won't be created.

## Naming

`cfg`s with **only** `alias`es are `lib cfg`s.

**Only** `cfg`s with `bind`s are `setup cfg`s.