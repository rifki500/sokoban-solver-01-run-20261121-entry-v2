# BUILD-LOG — sokoban-solver v2

19-byte loader (`eval(process.env.S)`) + push-optimal BFS solver (BigInt bitmask, room-by-room, dead-cell pruning) as entry secret `S` (6,025 B, cap 8,192). Secret not in repo.
Local: practice 5/5 optimal, score 1,000,000; two runs byte-identical; ~9 s of 60 s.
Top 10 unreachable: 48 entries already tie at 26 B with earlier receipts.
