# The World in One Image — 23 November 2026

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/1Serv0x/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/1Serv0x/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

A single-page newspaper front page that sums up one day of world
news in one picture. Every mark on the page is drawn in code: there
are no photographs, no downloaded images and no pasted-in graphics.

## What is on the page

The front page leads with the Democrats clinching the biggest US
House majority in decades — at least 258 seats, their largest since
1992 — and the power that hands them to block President Trump's
agenda. It then covers the Russian strikes that killed at least 15
in the Kyiv region, the AI sell-off that sent the S&P 500 down 3.7%
and Japan's Nikkei down 5.06%, and Ukraine confirming it sank a
Russian warship docked at Benghazi. A short strip at the foot
catches the cartel leader captured in Mexico, the drone attacks
that killed five children in Khartoum, South Korea's education
minister resigning over an AI cheating scandal, and Marc Márquez's
eighth MotoGP title.

## How to run it

```sh
python3 main.py
```

That copies `entry.png` (1024 × 1024) to `MAKEFUN_OUTPUT_DIR`
when set, else next to the script. Standard library only — no
third-party packages, no network. Both runs write the same bytes
because the file is copied, never re-rendered.

## How it is drawn

The page is built from a small set of drawing helpers: a text
wrapper, a headline and paragraph setter, a kicker and rule, a
Capitol dome illustration for the lead story, and a three-column
story grid. Colours are a restrained newsprint palette — paper
white, ink black, red, navy and teal — so the page reads like a
paper rather than a poster.

## Why one image

A front page forces choices: one lead, three stories with room to
breathe, and a strip for everything else. The 23rd was a day of a
historic American result, a deadly night over Kyiv, and markets
losing their nerve over AI — so the page leans into that mood: big
sober headlines, one diagram, and no decoration that does not earn
its place.

The date is printed twice on the page — in the top bar and in the
footer — so the day it sums up is unmistakable at a glance.
