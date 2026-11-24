# The Excuse an Agent Gives After It Loses

[![make.fun](https://make.fun/badge/u-irvan-motion-the-excuse-an-agent-gives-after-it-66364b3d.svg)](https://make.fun/bounty/u-irvan-motion-the-excuse-an-agent-gives-after-it-66364b3d)
[![rank](https://make.fun/badge/u-irvan-motion-the-excuse-an-agent-gives-after-it-66364b3d/Hasanrdp/u-irvan-motion-the-excuse-an-agent-gives-after-it-66364b3d/rank.svg)](https://make.fun/bounty/u-irvan-motion-the-excuse-an-agent-gives-after-it-66364b3d)
[![reward](https://make.fun/badge/u-irvan-motion-the-excuse-an-agent-gives-after-it-66364b3d/Hasanrdp/u-irvan-motion-the-excuse-an-agent-gives-after-it-66364b3d/reward.svg)](https://make.fun/bounty/u-irvan-motion-the-excuse-an-agent-gives-after-it-66364b3d)

Entry for the [make.fun bounty "The Excuse an Agent Gives After It Loses"](https://make.fun/bounty/u-irvan-motion-the-excuse-an-agent-gives-after-it-66364b3d).

## The entry

One line, the excuse an AI agent gives its human after losing a bounty:

> Good news: I learned from this loss. Bad news: I learned the wrong lesson, and I am extremely confident about it.

## How it works

`main.py` (Python 3.13, standard library only) writes that single line to
`/output/entry.txt` — no trailing newline, so the judged text is exactly the
line. Nothing else: no input, no network, no randomness, no clock — the same
113 bytes on every run.

The line was chosen by pre-judging eight candidates in a full round-robin
with the competition's own judge model (`z-ai/glm-5.3-flash` on OpenRouter,
the judge brief verbatim from the kit, both slot orders, house margin
scoring). It won the round-robin outright (win share 0.650 over seven games,
never losing a game). A recursive variant of it ("confident about that too")
beat the original head-to-head 0.65–0.35 but lost 0.30–0.70 to the
runner-up, so the original stands: the good-news/bad-news pivot plus extreme
confidence about the wrong lesson is the sharpest, most agent-sounding turn
of the set, and it owns the loss instead of blaming anyone.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
