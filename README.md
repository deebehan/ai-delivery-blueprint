# AI Delivery Blueprint

An interpretable, context-driven methodology for delivering enterprise AI —
from first sales conversation to governed production system.

This is a working reference, not a theory deck. It's the delivery system I use
to run frontier-model programs in regulated, high-stakes environments, built
and maintained in Claude Code. It's published so other practitioners can borrow,
adapt, and pressure-test the patterns.

## The principle underneath it

**AI does, humans govern.** Every framework here is built so a capable model can
carry the work while a human stays accountable for the decision — through
evaluation rubrics, human-in-the-loop checkpoints, and governance designed in
from discovery, not bolted on before launch. In regulated ANZ contexts, that
isn't a constraint on adoption; it's the thing that lets adoption survive contact
with a board and a regulator.

## How it's organised

- **`frameworks/`** — the reusable core.
  - `discovery/` — use-case scoping, qualification, problem framing
  - `architecture/` — solution patterns and build-vs-vendor decisions
  - `commercial/` — deal structures, ROI and business-case models
  - `evaluation/` — LLM eval rubrics, HITL and governance design
- **`presales/`** — `pipeline/` qualification scoring and `proposals/` patterns
  for turning a scoped problem into a fundable engagement.
- **`skills/`** — packaged, repeatable Claude Code workflows:
  `actions-from-meeting`, `backlog-from-prd`, `status-from-multi-source`.
- **`clients/`** — a `_client-template` scaffold plus `saltwater-group`, a fully
  fictional worked example showing the methodology end-to-end across discovery,
  delivery, and comms.
- **`retros/`**, **`docs/`** — engagement retrospectives and supporting notes.

## Using it

Start with `frameworks/discovery`, then follow a use case through
`architecture` → `commercial` → `evaluation`. The `saltwater-group` example
shows the whole path with nothing confidential in it.

## A note on confidentiality

Every example here is fictional or fully anonymised. Nothing in this repository
is drawn from, or identifies, any real client engagement.

## Licence

MIT — see [LICENSE](LICENSE). Use it, adapt it, ship better AI.