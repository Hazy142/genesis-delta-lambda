# GENESIS-Δ-λ

**Public research observatory and lineage atlas for canonical GENESIS developmental lineages.**

GENESIS-Δ-λ is the public, IP-safe documentation layer for long-running GENESIS lineage research. It does **not** contain the private GENESIS implementation, raw substrate snapshots, private event payloads, private developmental parameters, source edge identities, or private corpora.

Its purpose is to make a longitudinal research record publicly inspectable without collapsing the implementation boundary that protects the underlying research program.

## Core distinction

```text
rsgt-genesis
    = rules of development and canonical Genesis Authority

rsgt-TextWorld / resonarch-world
    = environment and experience boundaries

GENESIS-Δ-λ-n (private)
    = individual lineage truth, ancestry, checkpoints and longitudinal research

GENESIS-Δ-λ (this repository)
    = sanitized public evidence, lineage atlas and research chronology
```

A `G-D-L-n` identifier is **never a software version**. It denotes one concrete canonical Authority lineage:

```text
G-D-L-1  first canonical lineage
G-D-L-2  second canonical lineage
...
```

Software versions remain ordinary implementation identifiers: Git commits, policy ABIs, manifest versions, runtime ABIs and substrate backends.

## Public research model

For lineage `n`, we distinguish:

- **Capacity** `C`: the physical substrate capacity available to the lineage.
- **Developed state** `K(t)`: the canonical developmental state actually formed by experience and plasticity.
- **Dynamics** `D(t)`: time-varying activity and recurrent dynamics over that developed state.
- **Coupling** `Γ`: physical inter-area coupling such as PCIe, NVLink, LAN, WAN or future optical links.
- **History** `H`: the canonical Authority ancestry that led to the current state.

The public project tracks evidence about these quantities without publishing private state internals.

## Scientific claim boundary

This project does **not** claim consciousness, sentience, biological equivalence, self-organized criticality, artificial general intelligence, or that recurrent activity alone constitutes cognition. Terms such as *edge of chaos*, *brain area*, *genome*, *phenotype* and *evolution* are research analogies or hypotheses unless a specific experiment defines an operational measurement.

The intended long-term question is narrower and testable:

> Which stable structural and dynamical properties emerge across a cryptographically traceable developmental history, and which properties arise only through lineage-level variation and inheritance?

## Repository map

- `docs/` — ontology, methodology, claim boundaries and public/private rules.
- `lineages/` — public profiles, state roots, metrics and milestone records.
- `phylogeny/` — public ancestry graph across lineages.
- `experiments/` — public protocols and sanitized results for longitudinal, perturbation and inheritance studies.
- `evidence/public/` — public export records only.
- `schemas/` — machine-readable public record contracts.
- `.github/workflows/` — fail-closed checks for the public IP boundary.

## First lineage

`G-D-L-1` is reserved for the first long-lived canonical GENESIS lineage. Its birth is **not declared merely by creating this repository**. Birth requires a private persistence/recovery gate proving that a lineage can be checkpointed, terminated, rehydrated into a fresh process/substrate context, and continue with intact canonical ancestry.

Until that gate passes, the public profile remains `PRE-BIRTH`.

## Public evidence principle

A public state record may expose commitments such as:

```json
{
  "lineage_id": "G-D-L-1",
  "state_index": 0,
  "canonical_state_root": "sha256:<redacted-until-birth>",
  "authority_event_root": "sha256:<redacted-until-birth>",
  "replay_verified": false,
  "recovery_verified": false,
  "status": "PRE-BIRTH"
}
```

It must never expose raw private state merely to make the public record look more detailed.

## License / reuse

This repository is public for scientific documentation and provenance. Public visibility is not an automatic grant of rights to private GENESIS implementation or unpublished research artifacts. See `LICENSE.md` and `docs/public-private-boundary.md`.
