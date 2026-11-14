# Burnside Theorem Atlas

An interactive map of theorems, lemmas and open problems around the Burnside problem
in group theory: https://burnside.pahlevanyan.org

- Click a node to read its statement, source and verification status.
- "Show proof path" highlights everything a result depends on.
- The right panel lists hypotheses checked by a small Prolog prover; each proof is
  drawn on the graph as a numbered path, and unproved ones stop at the open problem
  they depend on.

Every item carries a status: `checked` (two sources agree), `transcribed` (one
source), `machine_verified` (our own computation), `elementary` (short proof in the
knowledge base), `from_memory` (not yet verified) or `disputed`. Treat unverified
items accordingly.

This repository holds only the built page (`index.html`). It is generated from a
separate knowledge base.
