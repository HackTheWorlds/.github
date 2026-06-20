<div align="center">

<img src="https://avatars.githubusercontent.com/u/281476914?s=200&v=4" width="88" alt="Hack the World(s)" />

<br />

# Hack the World(s)

**24 hours to rethink AI.**

`JEPA` `DINO-WM` `WORLD MODELS` `SELF-SUPERVISED` `PLANNING`

[![site](https://img.shields.io/badge/hacktheworlds.fr-000000?style=flat-square)](https://hacktheworlds.fr)
[![repo](https://img.shields.io/badge/eb__jepa-1a1a1a?style=flat-square&logo=github)](https://github.com/HackTheWorlds/eb_jepa)
[![live](https://img.shields.io/badge/2026_edition-19→20_JUN-1a1a1a?style=flat-square)](https://hacktheworlds.fr)

</div>

<br />

```diff
+ LLMs predict tokens.
+ World models understand space, time, causality.
- That's the gap we're hacking on.
```

## // about

LLMs are good at completing text. They're bad at understanding **what happens next**.

**Hack the World(s)** is a 24-hour, no-sleep hackathon built around **world models** — systems that build an internal representation of reality instead of just predicting the next token. The architecture at the center of it: **JEPA** (*Joint-Embedding Predictive Architecture*), designed by **Yann LeCun**, who's also backing this edition directly.

No reconstructing pixels. No brute-force generation. Predict in **representation space**, the way a brain does — and use that to plan.

Run by **ESIEE Paris**, **Mines Nancy / ACADI**, and **Institut PR[AI]RIE**. Backed by **AI Factory France**.

<br />

## // by the numbers

```
┌──────────────┬──────────────┬──────────────┬──────────────┐
│     24h      │     100      │      25      │   H100 GPU   │
│  non-stop    │  hackers     │    teams     │   cluster    │
└──────────────┴──────────────┴──────────────┴──────────────┘
```

Teams of 4, picked from the best engineering schools and universities in France. Everyone gets a pass for **VivaTech**, Europe's biggest tech show. No sleep schedule provided.

<br />

## // the stack

The technical core of this edition is **[`eb_jepa`](https://github.com/HackTheWorlds/eb_jepa)** — an open-source library for Energy-Based Joint-Embedding Predictive Architectures, built out of **Meta AI Research (FAIR)**.

Teams train and plan on top of it — image, video, and action-conditioned JEPA — distributed across an HPC cluster via Slurm. Bring your own seed, fight for your own GPU hours.

```python
# what the 25 teams are actually doing this weekend
for team in teams:
    model = JEPA(predict="representations", not_="pixels")
    model.train(gpu=cluster.allocate(team))
    plan = model.plan(horizon="the next 24 hours")
```

<br />

## // timeline

```
FRI 19 ───────────────────────────────────────────────
  morning   →  VivaTech, free roam
  13:30     →  opening keynote · Philippe Baptiste
  13:45     →  opening keynote · Yann LeCun
  16:15     →  convoy to ESIEE Paris · GPUs go live
  19:00     →  ⚡ clock starts. 24h on the board.

SAT 20 ───────────────────────────────────────────────
  19:00     →  demos → jury → closing ceremony
```

<br />

## // edition 2026 — live now

This edition is running **right now**, June 19–20, 2026. The clock started at 19:00 on the 19th and stops at 19:00 on the 20th.

Results, winning teams, and project writeups land here and on [hacktheworlds.fr](https://hacktheworlds.fr) right after the closing ceremony. Check back tonight.

<br />

## // run by

| | |
|---|---|
| 🎓 | [ESIEE Paris](https://www.esiee.fr) |
| ⛏️ | [Mines Nancy / ACADI](https://mines-nancy.univ-lorraine.fr) |
| 🧠 | [Institut PR[AI]RIE](https://www.prairie-psai.fr) |
| ⚡ | Infra by [OpenGate](https://opengate.space) |

Patronage: **Philippe Baptiste**, French Minister for Higher Education, Research & Space.
Sponsorship: **Yann LeCun**, Turing Award · ESIEE Paris alumnus · Executive Chairman, AMI Labs.

<br />

<div align="center">

<sub>📍 ESIEE Paris, Noisy-le-Grand · 🌐 hacktheworlds.fr · ✉️ contact@hacktheworlds.fr</sub>

<sub>© 2026 Hack the World(s)</sub>

</div>
