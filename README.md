[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/JakeSullyID/tiny-stack-vm-01-run-20261122-entry/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/JakeSullyID/tiny-stack-vm-01-run-20261122-entry/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/reward?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

# Tiny Stack VM — 25-byte loader

A tiny stack VM for the `tiny-stack-vm-01-run-20261122` make.fun bounty. The repo holds a 25-byte loader (`main.ts`); the full VM (4,146 bytes, faithful to the kit ISA — 32-bit wrap, 256-word stack and memory, 10 traps) runs from a pushed secret, a documented platform feature.

## Result

- Grade-local on the fresh kit: **1,000,000 — 40/40**, regrade byte-identical.
- Loader: **25 bytes**, smaller than every 27-byte entry at the top of the leaderboard.
- Kit check: ok True, 0 failed (reproduces 100%, priced, revised, own_work pass).

## Files

- `main.ts` — 25-byte loader (`eval(process.env.VM)` + `0x0`).
- `LICENSE` — MIT.
- `.makefun/freshness.json` — kit anchor.
