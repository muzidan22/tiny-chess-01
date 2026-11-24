# tiny-chess-01

A deterministic chess engine in 4 KB of Python 3.13 (stdlib only) for the
make.fun bounty "Build the strongest chess engine in 4 KB of Python".

`main.py` is the packed entry point (LZMA, produced with the bounty kit's
`compress` command). `src.py` is the readable source it was packed from.

0x88 board, PVS + transposition table + killer moves + quiescence, fixed
node budget per move, no clock, no randomness.
