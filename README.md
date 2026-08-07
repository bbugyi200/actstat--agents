# SASE Agent Hoods

Deterministic, owner-sharded snapshots and canonical prompt archives published by SASE.

![Project-scoped agent hoods pass through explicit privacy consent into an owner-sharded agents sidecar, where deterministic sync publishes prompts, chats, commits, states, and browsable owner, machine, hood, family, and agent pages.](assets/agents-directory-map.png)

**Owners:** 1 · **Machines:** 1 · **Hoods:** 10 · **Runs:** 28

## Prompt And Artifact Archive

`prompts/<YYYYMM>/<name>.md` stores committed run prompts. Prompt documents link back to their plan when one exists, link to the published agent page, and keep authored `@...` references readable while making staged artifacts clickable.

`artifacts/<YYYYMM>/<sha12>-<basename>` stores copied prompt-linked artifact bytes. The `sha12` prefix is the first twelve hexadecimal characters of the file's SHA-256 digest. Version-control-backed references link to hosted repository blobs instead of duplicating bytes here.

## Users

| User | Machines | Hoods | Runs |
|---|---:|---:|---:|
| [bbugyi200](users/bbugyi200/README.md) | 1 | 10 | 28 |
