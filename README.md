# Optimal Cutoff — The Secretary Problem

When choosing from `n` sequential options with no going back, the optimal strategy is to reject the first `n/e ≈ 37%` as a baseline, then take the next option that beats all of them. This gives a **~37% chance of picking the best** — the theoretical maximum.

The notebook derives and verifies this result via Monte Carlo simulation, cutoff sweep, and exact analytical formula.

## Setup

```bash
pip install matplotlib
```
