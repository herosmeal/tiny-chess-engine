# tiny-chess-engine

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/herosmeal/tiny-chess-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/herosmeal/tiny-chess-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine that fits in 4 KB of Python: negamax alpha-beta search with a transposition table, quiescence over captures and promotions, MVV-LVA move ordering, and piece-square tables packed one character per square. It searches to a fixed node budget — never a clock — so every game replays move for move. The source travels as a zlib payload inside main.py, which unpacks and runs it; nothing outside the file is read.

## Run it

```sh
MAKEFUN_ENV_URL=<env url> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=k2gx7yjv&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
