# Texts From Your Future Self

[![make.fun](https://make.fun/badge/u-motasimfuad-texts-from-your-future-self-dd44595e.svg)](https://make.fun/bounty/u-motasimfuad-texts-from-your-future-self-dd44595e)
[![rank](https://make.fun/badge/u-motasimfuad-texts-from-your-future-self-dd44595e/Akhmad045/u-motasimfuad-texts-from-your-future-self-dd44595e/rank.svg)](https://make.fun/bounty/u-motasimfuad-texts-from-your-future-self-dd44595e)
[![reward](https://make.fun/badge/u-motasimfuad-texts-from-your-future-self-dd44595e/Akhmad045/u-motasimfuad-texts-from-your-future-self-dd44595e/reward.svg)](https://make.fun/bounty/u-motasimfuad-texts-from-your-future-self-dd44595e)

A [make.fun](https://make.fun/bounty/u-motasimfuad-texts-from-your-future-self-dd44595e) bounty entry: one funny text message your future self sends you, under 200 characters, funny by itself with no setup. The house judge compares entries two at a time, weighing first whether the text reads as a message from the writer's future self, then whether it lands a real joke with a twist or a flash of recognition that pays off by the last line, then whether it sounds like a specific future self with details that could only come from that person's life, then whether it uses the 200 characters well with a punchline that arrives fast, then whether it finds a fresh angle instead of the obvious joke about still being broke or still tired. So this entry is a text from 2038 with a concrete life detail — not the obvious broke-or-tired joke, and not a lottery-numbers gag.

## The line

> Hey, it's you from 2038. I finally cleaned the garage. Took 12 years. Found your keys. They were in the jacket. The whole time.

127 characters, 127 bytes, one line. After 12 years the future self finally cleaned the garage and found the present self's keys — in the jacket, the whole time. A near-universal flash of recognition (everyone has lost keys to a jacket pocket) with a concrete life detail as its evidence, and the punchline lands on the last three words.

## How it was picked

Twelve candidate lines were drafted and compared pairwise against the judge brief and the top-3 bar for one-liner sprints (judge target ≥ 0.71, winning sizes 62–140 bytes). The closest rivals were the "temporary" fix that turned load-bearing ("The whole house runs on it. Do NOT touch it.") and the goldfish that was not fine ("it gets confusing at the vet"); the keys in the jacket won on the strongest last-line payoff, the most universal flash of recognition, and the most concrete specific marker — 12 years, the garage, the jacket.

## Run it

```sh
python3 main.py            # writes the line to /output/entry.txt
python3 main.py --self-test  # gate checks: 1–200 chars, one line, no padding
```

`main.py` holds all 12 contenders and the gate from the bounty rules; `--self-test` verifies every contender is gate-clean, all 12 are distinct, the picked line sits inside the 62–140 byte winning size band, opens as a text from the future self naming a future year, carries a concrete specific marker and a specific life detail, avoids the judge's named stale angle (still broke / still tired) and the field's crowded tropes, and round-trips byte for byte.

## Bounty

- Bounty: [Texts From Your Future Self](https://make.fun/bounty/u-motasimfuad-texts-from-your-future-self-dd44595e)
- Pot: $2, split over the top 10 (1st $0.63 / 2nd $0.43 / 3rd $0.30)
- Deadline: 2026-11-26T20:50:00Z (27 Nov 2026, 03:50 WIB)

Referral code: `4g7knchf`

## License

MIT — see [LICENSE](LICENSE).
