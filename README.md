# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/GAD2412/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/GAD2412/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of pure Python: tapered piece-square evaluation with mop-up, PVS alpha-beta with a transposition table, null-move pruning, late-move reductions, killers and a quiescence search, all under a fixed node budget so every move is deterministic. A small table, found by playing every book opening against every house engine offline, picks for each game the evaluation variant that wins it fastest.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=z1s7h5w8&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
