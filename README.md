# Cognitive Speed Training

Web-based cognitive speed training game — the type of processing-speed exercise shown in the ACTIVE study to reduce dementia risk by 29% over 10 years.

### [Play Now](https://brendanjameslynskey.github.io/Cognitive_Speed_Training/)

---

## What is this?

This is a free, browser-based implementation of the type of cognitive speed training that has been shown to reduce dementia risk. It is based on the Useful Field of View (UFOV) paradigm developed by Karlene Ball and colleagues, and on the broader findings of the ACTIVE (Advanced Cognitive Training for Independent and Vital Elderly) study.

The ACTIVE study was a landmark randomised controlled trial involving 2,832 older adults followed for over 10 years. Participants who received speed-of-processing training showed a **29% reduced risk of dementia** compared to the control group (Edwards et al., 2017). This was the only type of cognitive training in the study — out of speed, memory, and reasoning training — that demonstrated this protective effect.

This application provides five training modes, each targeting a different cognitive function relevant to processing speed, attention, and cognitive control. Difficulty adapts automatically to keep you in the optimal learning zone (around 75-80% accuracy), just as in the clinical research protocols.

## Training Modes

| Mode | Cognitive Target | Description |
|------|-----------------|-------------|
| Rapid Visual Identification | Visual processing speed | Identify a briefly flashed shape from multiple options. Display time decreases as you improve. |
| Divided Attention | Divided attention & UFOV | Identify a central object while simultaneously locating a peripheral target. |
| Visual Search | Selective attention & scanning | Find the odd item in a grid that grows larger as you improve (3x3 to 6x6). |
| Sequence Memory | Working memory & speed | Remember and reproduce increasingly long and fast sequences. |
| Reaction Time | Reaction time & inhibition | Click targets as fast as possible while avoiding distractors (go/no-go). |

## Features

- **Adaptive difficulty** — automatically adjusts to maintain optimal challenge level (~75-80% accuracy)
- **Progress tracking** — scores, streaks, personal bests, and accuracy history stored in localStorage
- **Scientific explanations** — each mode includes an expandable "Why this helps" panel citing specific research
- **Session statistics** — accuracy, reaction times, and improvement trends after each round
- **Level system** — XP-based progression to track long-term improvement
- **Accessible design** — large click targets, high contrast, clear typography, no audio dependencies
- **No installation** — runs entirely in the browser, no accounts or sign-ups

## The Science

The evidence for speed-of-processing training comes primarily from the ACTIVE study:

- **2,832 participants** randomised to speed, memory, reasoning, or control groups
- **10-year follow-up** showed lasting cognitive benefits
- **29% reduced dementia risk** in the speed training group (Edwards et al., 2017)
- **Only speed training** (not memory or reasoning) showed this protective effect
- **Dose-response relationship** — more sessions correlated with greater benefit
- **Transfer to daily life** — participants reported fewer difficulties with everyday activities (Willis et al., 2006)

The mechanism centres on expanding the "useful field of view" — the area from which you can extract visual information in a single glance. This engages the frontoparietal attention network, which shows early vulnerability in preclinical dementia.

### Key References

- Ball, K., et al. (2002). Effects of cognitive training interventions with older adults. *JAMA*, 288(18), 2271-2281.
- Willis, S. L., et al. (2006). Long-term effects of cognitive training on everyday functional outcomes. *JAMA*, 296(23), 2805-2814.
- Rebok, G. W., et al. (2014). Ten-year effects of the ACTIVE cognitive training trial. *Journal of the American Geriatrics Society*, 62(1), 16-24.
- Edwards, J. D., et al. (2017). Speed of processing training results in lower risk of dementia. *Alzheimer's & Dementia: Translational Research & Clinical Interventions*, 3(4), 603-611.
- Karbach, J., & Verhaeghen, P. (2014). Making working memory work. *Psychological Science*, 25(11), 2027-2037.
- Deary, I. J., & Der, G. (2005). Reaction time, age, and cognitive ability. *Aging, Neuropsychology, and Cognition*, 12(2), 187-215.

## Built with

- Vanilla HTML/CSS/JS — no build step, no dependencies
- localStorage for progress persistence
