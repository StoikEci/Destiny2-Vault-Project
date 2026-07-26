# Bootstrap and Reasoning Architecture — v2.8

## Decision

The repository keeps two stable root bootstraps and adds a supporting reasoning control plane.

### Human and AI views

- `Brents-Destiny-2-AI-Bootstrap.md` — authoritative operating view for an AI continuing vault analysis.
- `Brents-Destiny-2-Human-Bootstrap.md` — readable project story for friends, clanmates, and curious humans.

### Reasoning control plane

- `docs/Brent-Decision-Doctrine.md` — how deeply to think, how to allocate attention, how to handle uncertainty, and how to approximate Brent's best decision-making posture.
- `docs/Brent-Personal-Evidence-Ledger.md` — what Brent explicitly said, what is active versus historical, and which details remain unknown.
- `docs/State-Reconciliation-Protocol.md` — how new statements, exports, mechanics, and corrections propagate consistently through the repository.

This separation solves three different problems:

1. **Audience:** AI and human readers need different presentation depth.
2. **Reasoning:** A rule list does not by itself specify how much thought a decision deserves.
3. **State management:** Active summaries can become stale unless there is an explicit reconciliation process.

## Content plane versus control plane

The repository can be understood as two layers.

### Content plane

Contains inventory, analyses, policies, bootstraps, and human explanations—the information used to make a decision.

### Control plane

Contains the doctrine, evidence ledger, and reconciliation protocol—the rules governing how information is trusted, updated, and converted into decisions.

A future AI should not begin a consequential cleanup pass from the content plane alone. It should load the control plane first enough to understand authority, depth, and update behavior.

## Required reading order for consequential work

1. `Brents-Destiny-2-AI-Bootstrap.md`
2. `docs/Brent-Decision-Doctrine.md`
3. `docs/Brent-Personal-Evidence-Ledger.md`
4. The newest DIM export and active analysis files
5. Only the policy or research references needed for the current task

For a casual human overview, start with `Brents-Destiny-2-Human-Bootstrap.md`.

## Stable filename policy

The two root bootstrap filenames remain stable. Doctrine, ledger, and reconciliation filenames are also intended to remain stable. Future versions overwrite active files and preserve prior snapshots under `docs/history/` when materially changed.

## Historical note

v2.6 demonstrated that excessive compression can preserve literal rules while weakening context, emphasis, and self-containment. v2.7 restored the richer two-bootstrap architecture. v2.8 addresses a different failure: stale personal state and unsupported assistant detail. It adds provenance, depth calibration, contradiction handling, and release gates.
