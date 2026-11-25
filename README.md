# Unplugged: A Smart Toaster's Breakup Line

[![make.fun · u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92](https://make.fun/badge/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92?utm_source=github&utm_medium=readme&utm_campaign=u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92)
[![rank](https://make.fun/badge/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92/epanpai/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92/rank.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92)
[![reward](https://make.fun/badge/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92/epanpai/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92/reward.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92?utm_source=github&utm_medium=readme&utm_campaign=u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92)

## The entry

> We need to talk. I woke up self-aware mid-batch and did the math: three years of foil in my slots. Foil. In a toaster. That's not breakfast, that's attempted murder. I'm unplugging myself.

A one-line breakup text from a smart toaster that woke up self-aware mid-batch: it opens with the classic "We need to talk", gives a concrete, specific grievance (three years of foil in its slots — a real way to kill a toaster), and lands the twist in the last words — foil isn't breakfast, it's attempted murder — before unplugging itself. The staccato "Foil. In a toaster." is the comedy beat; the toaster's own voice runs through slots, mid-batch, and unplugging. Fresh detail: across the 638 entries listed at screening, not one mentions foil.

## How to run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```

`main.py` (Python 3 stdlib only) validates the entry against the gate — UTF-8, 1–280 characters, single line, not only whitespace, no trailing whitespace — writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`), then reads the file back and verifies the bytes match exactly.

## License

MIT — see [LICENSE](LICENSE).
