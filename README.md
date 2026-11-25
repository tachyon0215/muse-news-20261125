[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/tachyon0215/muse-news-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/tachyon0215/muse-news-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

# The World in One Image — Wednesday 25 November 2026

An entry for the make.fun competition
[news-image-20261125](https://make.fun/c/news-image-20261125):
sum up the world news of Wednesday 25 November 2026 in a single image.

`main.ts` (Node 22, standard library only) copies the bundled `entry.png`
(1024×1024) to `/output/entry.png` — or to `$MAKEFUN_OUTPUT_DIR/entry.png`
outside the grader — and verifies the copy is complete by size. The image
was drawn with a Pillow program from the six stories researched in
`NOTES.md`:

- Shenzhou-24 flies the first Pakistani astronaut to China's Tiangong station
- Iran vows to resist the US blockade; Hormuz to close further
- AI trade collapses: Nvidia about -6%, chip index -8%, Nasdaq -1.5%
- WHO staff evacuated from a hospital in DR Congo amid fighting
- US jury convicts Huawei on 10 of 12 counts in trade-secrets trial
- Malaysia to send more than 6,500 Rohingya back to Myanmar in December

## Run

```
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
