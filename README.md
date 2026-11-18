[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/mumun110795/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/mumun110795/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

# Tuesday 17 November 2026 — the world in one page

Our entry for the make.fun competition **news-image-20261117**
("Sum up 17 November's world news in one image").

## What the image is

A one-page broadsheet front page for a single day — **Tuesday 17 November
2026** — carrying **50 stories** that happened, or were first reported, on
that day:

- a dated masthead, a region tally strip (Europe 14 · Asia 10 · Middle East 7 ·
  Africa 7 · Americas 7 · Oceania 3 · World 2) and a six-figure stat strip;
- a world map with numbered pins for the 15 lead stories and dots for the
  briefs, plus a "day by field" tally;
- 3 hero cards and 12 lead cards, each with an original flat illustration, a
  region · field · place tag, a bold headline and a short deck;
- 35 briefs grouped by region, a "Diary" box for the days just ahead, and a
  **Date Check** box naming the stories deliberately kept off the page as
  off-day (the Ebola 11,000-case mark passed about 10 Nov; a Vulcan rocket
  lost on 15 Nov; Fela Kuti's 14 Nov Hall of Fame night; a 124 m freedive
  record set on 14 Nov; and Xi's airport welcome for Trump in Shenzhen, which
  is Wednesday's news).

Disputed claims name the side that makes them ("Ukraine says…", "Russia
claims…", "Iran says… — not verified"), and figures name the body that
counted them (WHO, UN, PAHO, INSP). Sources: Reuters, AP, AFP, Al Jazeera,
BBC, UN News, WHO, NASA, RNZ Pacific, Samoa Observer.

## How it runs

`main.py` (Python 3, standard library only) decodes the embedded image and
writes it to `/output/entry.png` — byte-identical on every run. The artwork
was researched, written and drawn with PIL during the recorded build
sessions; the finished PNG is also committed as `entry.png` for inspection.

## License

MIT — see `LICENSE`.
