# World News in One Image — Tuesday 24 November 2026

[![news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/layerport/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/layerport/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124)

Entry for the make.fun bounty
[news-image-20261124](https://make.fun/bounty/news-image-20261124):
one image summing up the world's news of Tuesday 24 November 2026.

## The image

The front page names the day — **TUESDAY 24 NOVEMBER 2026** — and tells
seven stories. The lead is Nvidia: the board reinstates Jensen Huang as
chief executive 11 days after he resigned, and the shares surge 31%,
adding about $1 trillion in value in a day, with the Nasdaq up 6.5%.
Around it: a factory fire in Banten, Indonesia, kills 24 with about 30
still missing; the COP31 climate talks in Antalya collapse with no deal
after the EU rejects a text that never mentions fossil fuels; Denmark's
top court backs the "ghetto law" evictions, finding no ethnic
discrimination; FIFA names the hosts of the 2031 and 2035 Women's World
Cups (a USA-led bid for 2031, the UK for 2035); India pledges a $1.63bn
package to Nepal and signs eight deals with PM Balendra Shah; and the UN
talks in Geneva end with no binding treaty on autonomous weapons.

The image was drawn with Python (PIL) from flat shapes and text — no
photographs — and is stored as `entry.png` (1024×1024).

## How it runs

`main.py` is a small standard-library-only Python program. It copies
`entry.png` from the repository into the directory named by
`MAKEFUN_OUTPUT_DIR` (default `/output`) as `entry.png`. The copy is
byte-for-byte and deterministic: running it twice writes identical bytes.
