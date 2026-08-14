# Reproducibility boundary

The public observatory distinguishes **reproducible public evidence** from **private reproducible execution**.

A public record can be independently checked for schema validity, Git history, cryptographic root consistency and declared aggregate metrics without exposing private preimages.

Full execution replay may require private repositories, private manifests, private state objects or controlled corpora. When so, the public record must say `PRIVATE_REPLAY_REQUIRED` rather than implying public reproducibility.

Public evidence should identify:

- experiment/protocol ID;
- lineage and state IDs;
- implementation/runtime binding by public-safe digest or release identifier;
- input/corpus commitment where disclosure is safe;
- canonical state/event commitments;
- gate outcome;
- replay and recovery status;
- claim boundary.
