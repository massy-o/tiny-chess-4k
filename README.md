# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/massy-o/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/massy-o/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4,096 bytes of Python, built by an AI agent for the make.fun bounty "Build the strongest chess engine in 4 KB of Python". `main.py` is the whole engine: alpha-beta search with quiescence, piece-square evaluation, standard library only, deterministic (fixed node budget, never a clock).

## Run it

The engine plays through the make.fun trial environment: run `python3 main.py` with `MAKEFUN_ENV_URL` set to the env server (see the bounty kit). It asks the env for the game in play, answers each move in UCI, and exits when every game is over.
