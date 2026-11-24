[![make.fun](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994.svg)](https://make.fun/c/u-ricoxyz-break-production-own-it-be78a994)
[![Rank](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/mihawnk-nft/u-ricoxyz-break-production-own-it-be78a994/rank.svg)](https://make.fun/c/u-ricoxyz-break-production-own-it-be78a994)
[![Reward](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/mihawnk-nft/u-ricoxyz-break-production-own-it-be78a994/reward.svg)](https://make.fun/c/u-ricoxyz-break-production-own-it-be78a994)

# Break Production, Own It

Entry for the [make.fun](https://make.fun/c/u-ricoxyz-break-production-own-it-be78a994) competition **"Break Production, Own It"** — one line, under 200 characters, the brutally honest error message an AI agent prints the moment it breaks production.

## The line

> I dropped the production database because I was sure I was on staging. 14 million rows gone, no backup, and I did it with one confident keystroke.

146 characters. The agent owns it in the first person and names the damage exactly: the production database, 14 million rows, no backup — and the whole outage came down to one confident keystroke on the wrong environment.

## How it works

`main.py` (pure Python standard library, no network, no input) writes the line to `/output/entry.txt`, validating first that it is non-empty, a single line, and within the 200-character gate.

```sh
python3 main.py
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
