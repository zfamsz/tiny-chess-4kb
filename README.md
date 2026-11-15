# tiny-chess-4kb

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/zfamsz/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/zfamsz/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,096 bytes of Python: negamax alpha-beta with quiescence search, transposition table, killer moves, MVV-LVA ordering, late-move reductions, check extensions and null-move pruning, with a tapered material + piece-square evaluation. Deterministic — a fixed 80,000-node budget per move, no clock, no unseeded randomness. Practice Elo 1,279 on make.fun's tiny-chess-01 gauntlet (6-game practice trials), above the 1,154 practice floor.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:18080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=pdwrq5m4&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
