# Gravit Open Network Foundation

Open protocols and reference code for **verifiable decisions**: a claim — by a person, a
system or an autonomous AI agent — is accepted only with evidence that anyone can re-check,
and every decision is a reproducible artefact.

Swiss non-profit association (Verein), Zürich · [gravit.world](https://gravit.world) ·
[gravit.space](https://www.gravit.space)

## Reproduce our results in five minutes

```bash
git clone https://github.com/gravit-open-network-foundation/gravit-eval-pack
cd gravit-eval-pack && make eval
```

Every published number is computed by code and checked byte for byte in CI.

## Specifications (IETF Internet-Drafts)

- [draft-gravit-gevp-08](https://datatracker.ietf.org/doc/draft-gravit-gevp/08/) — GEVP, the mechanism: how evidence is verified
- [draft-gravit-verifiable-epistemic-decision-00](https://datatracker.ietf.org/doc/draft-gravit-verifiable-epistemic-decision/00/) — VEDS, the policy: what a verified decision must guarantee

Internet-Drafts are individual submissions; they are not endorsed by the IETF.

## Code

| Repository | What it is |
|---|---|
| [verifier](https://github.com/gravit-open-network-foundation/verifier) | Reference verifier (Python + Rust port): no aggregation laundering, Ed25519-signed evidence, 3-of-5 registry trust root, 40 golden vectors |
| [gravit-eval-pack](https://github.com/gravit-open-network-foundation/gravit-eval-pack) | One command to reproduce conformance, an adversarial benchmark and Sybil experiments |
| [gravit-grover](https://github.com/gravit-open-network-foundation/gravit-grover) | Consensus engine (classical, Grover-inspired amplification) with reproducible Sybil experiments |
| [gravit-canon](https://github.com/gravit-open-network-foundation/gravit-canon) | Canonical specification repository |
| PoCs: [AllUnity](https://github.com/gravit-open-network-foundation/gravit-allunity-poc), [Sygnum](https://github.com/gravit-open-network-foundation/gravit-sygnum-poc), [EasyMM](https://github.com/gravit-open-network-foundation/gravit-easymm-poc) | Proofs of concept; partner interfaces simulated, test keys only |

## How we work

- Every change is reviewed and approved by a second person who is not its author.
- Every number in a README must be reproduced by code in CI.
- History is never rewritten: corrections are added, not erased.
- Keys in public repositories are test keys; the root key ceremony is planned.

Code is Apache-2.0 unless stated otherwise.
