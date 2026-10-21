# exo-interfaces

Definitions of every value, connector, signal, message, and mounting that one EXO team provides and another depends on. One file per interface, numbered I-01 to I-10.

| Field | Value |
| --- | --- |
| Owner | Project Leads; the leads of each affected team review changes |
| Program | IEEE EXO, Phase 1 (unilateral prototype) |
| Current version | v0.1 (scaffold) |

## Layout

```
I-01 ... I-10  one file per interface
can/           CAN message definitions (I-02, I-03)
connectors/    Pinouts
_template.md   Starting point for a new interface
```

After an interface freezes at its listed design review, changes need approval from every affected team lead.

## How changes are made

Branch from `main`, open a pull request, get one approval from the code owner, merge. See `CONTRIBUTING.md`.

## Safety

1. No powered actuator moves until the bench stop path has been demonstrated and the Project Leads have confirmed it.
2. Nobody wears any part of the device, including the battery belt, until the Project Leads confirm written approval.
3. No on-body sensor data, and no data from anyone wearing part of the device, goes into Drive or GitHub.
4. No lithium-ion pack assembly until a reviewed build procedure exists.
5. Lab work in ENG 208 requires the lab safety courses to be complete.
6. Never commit passwords, tokens, keys, or Wi-Fi credentials. Use an ignored file and a committed example file.
7. Nothing at battery pack voltage is connected to an actuator until the Project Leads confirm in writing that the actuator's allowed input voltage covers a full pack.
