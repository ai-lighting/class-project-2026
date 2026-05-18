# Class Project 2026 — Lighting Design & Engineering

A contribution to the RMIT Lighting Engineering and Design Group's 2026 class project.

## What's in here

A hypothetical car-dealership lighting project used as the basis for student work covering interior, exterior, emergency and daylight design under Australian / New Zealand standards.

This repository contains the project brief, supplied Relux scenes, CAD references and the results / assessment workbook.

## Project files

| File / folder | Purpose |
|---|---|
| `Class Project 2026 - Brief.html` | Project brief (open in a browser). The canonical document. |
| `2026 Project*.rdf` | Supplied Relux scenes (split into three sub-projects to reduce hardware load). |
| `Car Dealership *.dwg` | Reference CAD drawings of the building and site. |
| `.gitignore` | Excludes the local `Archive/` folder (historical files, backups, working drafts) from version control. |

## Submission

Students submit a Relux export file (`.recad`) named:

```
Surname_StudentID_DealershipLighting.recad
```

Submission and online recording provisions will be added as the project progresses. Until then files are shared through the project channel.

## Compliance tooling

- **AS/NZS 1158** (exterior) is verified using the Compliance Calculator, fed by the `.recad`.
- **NCC Section J7** (lighting energy) is also read from the `.recad` by the Compliance Calculator. Luminaires must carry correct wattage data in the Relux model.
- **AS/NZS 1680.1** (interior), **AS/NZS 2293.1 / .3** (emergency and exit signs) are evaluated against the Relux outputs and the per-space assessment summary.
- **AS/NZS 4282:2023** (obtrusive outdoor light) is referenced only and not required as a deliverable for this iteration.

## Standards referenced

- AS/NZS 1680.1 — Interior and workplace lighting
- AS/NZS 1158.3.1 — Lighting for roads and public spaces (Category P)
- AS/NZS 2293.1 and 2293.3 — Emergency lighting and exit signs
- AS/NZS 4282:2023 — Control of obtrusive outdoor light (referenced)
- NCC Section J — Energy efficiency (Part J7 lighting)

## Status

Working draft. The brief, results workbook and supporting tools are being iterated on through the project. Expect structural changes as the online submission system comes online.
