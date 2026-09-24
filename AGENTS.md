# Project Fawzi — MedFlow Etymology Asset Pack Handoff

This repository supports the MedFlow **Etymology Course / The Shape Code** production workflow.

## Locked production direction
- Preserve the approved navy/gold Workshop visual system.
- Do not trigger a global redesign or switch to generic white layouts.
- Prefer real anatomy + analogy side-by-side where useful.
- Keep the official MedFlow identity/logo.
- Audit against source, patch only faulty slides, regenerate only faulty slides, then merge the strongest result.
- Chapter 1 / Module 1 remains the immediate completion lane.

## Asset scope
The current pack covers 12 root families:
Arcus, Sagitta, Falx, Trochlea, Serra, Malleus/Malleolus, Incus, Stapes/Stapedius, Stylos, Vomer, Xiphos, and Clavis/Clavicula.

`IMAGE_MANIFEST.csv` is the machine-readable map. `CROP_AND_USE_RULES.md` contains composition/crop constraints.

## Safety
- Do not replace approved assets globally just because a new generator produces a different style.
- Do not duplicate the same image across multiple slide roles unless intentionally documented.
- Preserve anatomical recognizability and full key structures required by the crop rules.
- Do not commit private API keys or local-only credentials.

## Agent workflow / zero-cost rule
Use a branch for changes, keep the task narrow, and validate manifest/path consistency locally. Do not open Pull Requests, add GitHub Actions, enable billing, credits, premium overages, or paid APIs. Push only the branch and report changed files, validation performed, unresolved visual/content risks, and commit hashes. ChatGPT reviews pushed branches directly through GitHub.
