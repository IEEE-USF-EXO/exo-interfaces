# exo-interfaces

Definitions of every value, connector, signal, message, and mounting that one EXO team provides and another depends on. One file per interface, numbered as in the Master Log.

| Field | Value |
| --- | --- |
| Owner | Project Leads; the leads of each affected team review changes |
| Program | IEEE EXO, Phase 1 (unilateral prototype) |
| Current version | v0.1 (scaffold) |

## Layout

```
I-01 ... I-07  one file per interface
can/           CAN message definitions (I-02, I-03)
connectors/    Pinouts
_template.md   Starting point for a new interface
```

After an interface freezes at its listed design review, changes need approval from every affected team lead.

## How changes are made

Branch from `main`, open a pull request, get one approval from the code owner, merge. See `CONTRIBUTING.md`.
