# Biophilic Intervention in Mental Wellbeing

**Final-year project (FYP)** — BSc Computer Science (Games Technology), Nottingham Trent University.

Immersive **Unreal Engine** VR scenes (OpenXR, Meta Quest 2 / PCVR Air Link) that simulate nature for short wellbeing sessions. Two contrasting environments: an icy Arctic setting and a domed garden. A small pilot (N = 15) recorded stress, mood, presence, cybersickness, and heart rate after six minutes of exposure.

**Presentation (YouTube):** [https://youtu.be/5-pKqxjzwYs](https://youtu.be/5-pKqxjzwYs)

This is the same engine stack as [CorsiVR](https://github.com/NWAFORTY/VR): Unreal Engine + OpenXR.

## Tech stack

| | |
| --- | --- |
| Engine | Unreal Engine (OpenXR) |
| Hardware | Meta Quest 2, PCVR (Air Link), 75 Hz |
| Evaluation | PSS-10, PANAS-style affect, presence, cybersickness, Coospo chest-strap HR |
| Author | Tobenna Nwafor (N1205091) · Supervisor: James Lewis |

## Evaluation (pilot)

Not a clinical trial. Convenience sample, **N = 15**.

- Sessions ~**6 minutes**, post-session questionnaires (no pre-exposure psychometrics).
- Heart rate: start, minimum, peak, end, mean BPM.
- Aim: **feasibility** and a reproducible data pipeline, not therapeutic proof.
- Limits: fixed scene order, short exposure, tethered-streaming artefacts, non-clinical recruitment.

Study sheet: `biophilic_vr_data_entry.csv` (`n001`–`n015`).

## Repository contents

The Unreal project and demo video are too large for GitHub (zip and `finalDemo.mp4` are ~1 GB each). This repo holds the report, plan, and data. The playable build is on YouTube.

| | |
| --- | --- |
| [Presentation](https://youtu.be/5-pKqxjzwYs) | FYP demo / presentation |
| `N1205091_report.docx` | Final report |
| `N1205091_Project_Planning_Document.pdf` | Planning document |
| `N1205091_source/.../biophilic_vr_data_entry.csv` | Pilot data |

## Related

- [CorsiVR](https://github.com/NWAFORTY/VR) — Unreal Engine 5.7 OpenXR memory game (module VR project)
