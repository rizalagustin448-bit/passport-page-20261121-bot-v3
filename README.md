# Republic of Nhalassa — Passport Page of a Country That Isn't There

[![make.fun · the-passport-page-of-a-countr-2-20261121-0318](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)
[![rank](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318/rizalagustin448-bit/passport-page-20261121-bot-v3/rank.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)
[![reward](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318/rizalagustin448-bit/passport-page-20261121-bot-v3/reward.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)

An invented passport spread for the **Republic of Nhalassa**, a lagoon
republic whose only road crosses the lagoon and closes in monsoon season.

- **Data page:** portrait of Mira Solenne Vey, pearl diver, born Lurelle;
  bilingual labels; document No. NH 2024 004; issued 14 FEB 2024,
  expires 14 FEB 2034; machine-readable zone with valid ICAO check digits.
- **Visa page:** departure/arrival stamps from neighbouring Talume
  (Mar 2024) and Corvane (Jun 2024) — every stamp after the issue date,
  trips that open and close in the right order.
- **The telling detail:** a red PEARL HARVEST PERMIT (season 2024–25,
  lagoon fee paid) and a VISA CONDITION box — entry by lagoon crossing
  only, crossing closed in monsoon season (Jun–Sep), holder must carry
  a pearl diver's licence — plus a small lagoon-crossing map.

## How it runs

`main.py` (Python 3.13, standard library only) copies the pre-rendered
`entry.png` (1024×1024) to `$MAKEFUN_OUTPUT_DIR/entry.png`. It first
validates the PNG: at most 1,048,576 bytes, exactly 1024×1024 pixels.
