<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/HackTheWorlds/.github/main/profile/assets/htw-logo.svg" />
  <img src="https://raw.githubusercontent.com/HackTheWorlds/.github/main/profile/assets/htw-logo-light.svg" width="300" alt="Hack the World(s)" />
</picture>

<br />

# Hack the World(s)

**24 hours to rethink AI.**

`JEPA` `DINO-WM` `WORLD MODELS` `SELF-SUPERVISED` `PLANNING`

[![site](https://img.shields.io/badge/hacktheworlds.fr-8b5cf6?style=flat-square&labelColor=0a0a0a)](https://hacktheworlds.fr)
[![repo](https://img.shields.io/badge/eb__jepa-22d3ee?style=flat-square&logo=github&logoColor=f0f0f0&labelColor=0a0a0a)](https://github.com/HackTheWorlds/eb_jepa)
[![edition](https://img.shields.io/badge/2026_edition-19→20_JUN-ec4899?style=flat-square&labelColor=0a0a0a)](https://hacktheworlds.fr)

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

Run by **[ESIEE Paris](https://www.esiee.fr)**, **[Mines Nancy](https://mines-nancy.univ-lorraine.fr)** / **[ACADI](https://acadi.asso.fr)**, and **[Institut PR[AI]RIE](https://www.prairie-psai.fr)**. Backed by **[AI Factory France](https://aifactory-france.eu)**.

<br />

## // by the numbers

<div align="center">

![24h](https://img.shields.io/badge/24h-non--stop-8b5cf6?style=flat-square&labelColor=0a0a0a)
![100](https://img.shields.io/badge/100-hackers-22d3ee?style=flat-square&labelColor=0a0a0a)
![25](https://img.shields.io/badge/25-teams-ec4899?style=flat-square&labelColor=0a0a0a)
![GB200](https://img.shields.io/badge/GB200-GPU_cluster-8b5cf6?style=flat-square&labelColor=0a0a0a)

</div>

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
  17:30     →  demos → jury → closing ceremony
```

<br />

## // edition 2026 — live now

This edition is running **right now**, June 19–20, 2026. The clock started at 19:00 on the 19th and stops at 17:30 on the 20th.

<br />

## // run by

<div align="center">

[![ESIEE Paris](https://img.shields.io/badge/ESIEE_Paris-8b5cf6?style=flat-square&labelColor=0a0a0a)](https://www.esiee.fr)
[![Mines Nancy](https://img.shields.io/badge/Mines_Nancy-22d3ee?style=flat-square&labelColor=0a0a0a)](https://mines-nancy.univ-lorraine.fr)
[![ACADI](https://img.shields.io/badge/ACADI-ec4899?style=flat-square&labelColor=0a0a0a)](https://acadi.asso.fr)
[![Institut PR[AI]RIE](https://img.shields.io/badge/Institut_PR%5BAI%5DRIE-8b5cf6?style=flat-square&labelColor=0a0a0a)](https://www.prairie-psai.fr)
[![OpenGate](https://img.shields.io/badge/OpenGate_infra-22d3ee?style=flat-square&labelColor=0a0a0a)](https://opengate.space)

</div>

Patronage: **Philippe Baptiste**, French Minister for Higher Education, Research & Space.
Sponsorship: **Yann LeCun**, Turing Award · ESIEE Paris alumnus · Executive Chairman, [AMI Labs](https://amilabs.xyz).

<br />

<div align="center">

<sub>📍 ESIEE Paris, Noisy-le-Grand · 🌐 hacktheworlds.fr · ✉️ contact@hacktheworlds.fr</sub>

<sub>© 2026 Hack the World(s)</sub>

</div>
