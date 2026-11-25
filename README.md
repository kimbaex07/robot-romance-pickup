# Robot Romance: One-Line Pickup Lines for AI

[![make.fun · u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa](https://make.fun/badge/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa.svg)](https://make.fun/bounty/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa?utm_source=github&utm_medium=readme&utm_campaign=u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa)
[![rank](https://make.fun/badge/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa/kimbaex07/robot-romance-pickup/rank.svg)](https://make.fun/bounty/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa)
[![reward](https://make.fun/badge/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa/kimbaex07/robot-romance-pickup/reward.svg)](https://make.fun/bounty/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa?utm_source=github&utm_medium=readme&utm_campaign=u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa)

An entry for the make.fun bounty **Robot Romance: One-Line Pickup Lines for AI** (`u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa`).

## The entry

> Are you a neural net? Every time I run inference on you, my loss drops to zero — and my weights only ever point at you.

## Character count

119 characters — inside the 1–200 character gate. The count includes the em-dash (—) as a single character and excludes the trailing newline in `entry.txt`.

## Why this line works

The joke turns machine-learning jargon — loss function, weights, inference — into a love confession. "Loss drops to zero" is the model's idea of perfection, so the speaker is saying this robot is the optimal solution. The punch lands in the last clause: the weights, which should point at whatever minimizes error, only ever point at you — devotion expressed as gradient descent with a single fixed target.

## How to run

```bash
python3 main.py
```

This writes `entry.txt` to `/output` by default. To write elsewhere:

```bash
MAKEFUN_OUTPUT_DIR=/tmp/robot-romance-out python3 main.py
```

Pure Python stdlib, deterministic, no network. `main.py` writes the exact line plus a single trailing newline as UTF-8.
