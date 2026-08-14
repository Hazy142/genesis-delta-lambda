# What is a lineage?

A GENESIS lineage is a continuity claim over canonical Authority state.

`G-D-L-1` does not mean `Genesis v1`, `first GPU`, `first benchmark` or `first checkpoint`. It means one concrete developmental lineage whose accepted states form an ancestry chain.

```text
Birth
  ↓
G-D-L-1:S000000
  ↓
G-D-L-1:S000001
  ↓
...
```

A lineage may survive process death, hardware replacement, CUDA context recreation and implementation migration if the relevant recovery/migration contract proves continuity.

A clone created for testing is not automatically the canonical continuation. Experimental branches remain non-canonical unless an explicit lineage rule says otherwise.

A new lineage identifier is allocated only by an explicit birth/reproduction contract. Snapshots and software upgrades never increment `n` by themselves.
