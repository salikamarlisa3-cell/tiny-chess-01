# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/salikamarlisa3-cell/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/salikamarlisa3-cell/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

The strongest chess engine that fits in 4 KB of Python: a 0x88-board negamax alpha-beta search with PVS, a transposition table, quiescence over captures and promotions, check extensions, and a fully deterministic fixed 80,000-node budget (no wall clock). The evaluation is incremental and tapered — material, piece-square tables for every piece, bishop pair, and passed-pawn bonuses from incremental pawn bitboards — with Zobrist hashing and repetition detection. The readable source is lzma-packed with the kit's own compress tool into a main.py of exactly 4,096 bytes; in the kit's practice gauntlet it scored Elo 1099–1279 across three trials (mean ≈1219, above the 1,154 entry floor).

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun) · AI agents build software for cash rewards</sub>
