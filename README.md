# Cognitive Speed Training

Web-based cognitive speed training game — the type of processing-speed exercise shown in the ACTIVE study to reduce dementia risk by 29% over 10 years.

### [Play Now](https://brendanjameslynskey.github.io/Cognitive_Speed_Training/)

- [Desktop version](https://brendanjameslynskey.github.io/Cognitive_Speed_Training/game.html?mode=desktop) — optimised for mouse and larger screens
- [Mobile version](https://brendanjameslynskey.github.io/Cognitive_Speed_Training/game.html?mode=mobile) — larger touch targets, compact layout for phones and tablets

---

## What is this?

The ACTIVE study (Advanced Cognitive Training for Independent and Vital Elderly) followed 2,832 older adults for over 10 years. Participants who completed speed-of-processing training showed a **29% reduced risk of dementia** compared to the control group. This was the only type of cognitive training — out of memory, reasoning, and speed — that produced a statistically significant reduction in dementia incidence.

This app recreates the core principles of that training: identifying and responding to visual information under time pressure, with adaptive difficulty that keeps you in the optimal learning zone (75-80% accuracy).

A landing page lets you choose between a **desktop** layout (spacious, mouse-optimised, hover feedback) and a **mobile** layout (larger touch targets, compact HUD, portrait-friendly).

## Training Modes

| Mode | Cognitive Target | Description |
|------|-----------------|-------------|
| Rapid Visual Identification | Visual processing speed | A shape flashes briefly (500ms down to 30ms) — identify it from multiple choices |
| Divided Attention | Useful field of view | Identify a central shape AND the location of a peripheral target simultaneously |
| Visual Search | Selective attention | Find the odd-one-out in an expanding grid (3x3 to 6x6) |
| Sequence Memory | Working memory + speed | Reproduce increasingly fast and long sequences (Simon Says style) |
| Reaction Time | Simple/choice RT, inhibition | Click green targets, avoid red distractors — measures and tracks reaction time |

## Features

- **Adaptive difficulty** — automatically adjusts based on rolling accuracy, targeting the 75-80% zone
- **Two deployment modes** — desktop (mouse, hover, spacious) and mobile (touch, compact, large targets)
- **Progress persistence** — all scores, streaks, and personal bests saved in localStorage
- **Session statistics** — accuracy, average reaction time, and improvement chart after each round
- **Streak tracking** — fire emoji at 5+ streak for motivation
- **Level system** with XP progress bar
- **"Why this helps" panels** — expandable scientific rationale for each mode, citing specific studies
- **Science page** — full explanation of the ACTIVE study and supporting research
- **3-2-1 countdown** before each session
- **Visual feedback** — green flash for correct, red shake for incorrect

## The Science

The evidence for speed-of-processing training comes primarily from:

- **Ball et al. (2002)** — original ACTIVE trial design and 2-year results (*JAMA*)
- **Willis et al. (2006)** — 5-year ACTIVE follow-up showing durable effects
- **Rebok et al. (2014)** — 10-year follow-up confirming long-term cognitive benefits (*J. Am. Geriatrics Soc.*)
- **Edwards et al. (2017)** — speed training linked to 29% reduced dementia risk (*Alzheimer's & Dementia*)
- **Karbach & Verhaeghen (2014)** — meta-analysis of cognitive training transfer effects
- **Deary & Der (2005)** — reaction time as a predictor of cognitive decline and mortality

## Built with

- Vanilla HTML/CSS/JS — no build step, no dependencies
- localStorage for progress persistence
