<p align="center">
  <h1 align="center">Stress-Testing Emergent-Misalignment Model Organisms</h1>
  <p align="center"><strong>Red-team RL-trained emergent-misalignment organisms and measure which failure modes survive simple probes.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Stress-Testing Emergent-Misalignment Model Organisms**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Red-team RL-trained emergent-misalignment organisms and measure which failure modes survive simple probes.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
