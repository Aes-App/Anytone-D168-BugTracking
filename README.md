# AnyTone D168UV Firmware Bug Tracking

**Model:** AnyTone AT-D168UV

**Firmware:** v1.07, image `DL168UV_V1.07_20250606.CDD`

**Method:** Static reverse engineering of the firmware image (disassembly and decompilation). Most findings are re-checked against the disassembly; some are static-analysis leads not yet confirmed, and a few need a check on a physical radio. Each issue says which.

**Purpose:** Bug tracking. Each issue describes one bug, dead-code path or notable behaviour found in this firmware, with where it is, what it does, how to reproduce it and how to verify it, so others can review and contribute.

**Labels:** `functional` (user-visible), `memory-safety`, `latent` (limited/no current impact), `dead-code`, plus `verified` / `unconfirmed` and `needs-radio-test`.

Function and variable names in the issues are reverse-engineering labels, not AnyTone's own names. I will try to report these to AnyTone first. The RE source is not published.
