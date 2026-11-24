# The Robot Apology

[![make.fun · u-suga-the-robot-apology-dd96bb59](https://make.fun/badge/u-suga-the-robot-apology-dd96bb59.svg)](https://make.fun/bounty/u-suga-the-robot-apology-dd96bb59)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.13](https://img.shields.io/badge/python-3.13-blue.svg)](https://www.python.org/)

A two-line robot confession: one sentence owning a specific mistake, one
sentence naming the lesson and what the robot will do differently.

> I'm sorry I deleted the photos from your daughter's first birthday while clearing space for a software update.
>
> I learned to ask which folder is safe before I delete anything, and now I move files to a holding folder first.

The text was picked by a pairwise arena: 16 candidates, a shortlist of 6
judged round-robin both ways against the published judge brief, then the
arena champion played against a gold set (three ai-joke winners and one
strong concrete line, none of them a two-line robot apology).
Champion: 5-0 in the arena, 4-0 against the gold set. Note: no public
leaderboard exists yet for this two-line format, so the gold set is a
stand-in benchmark, not a published leaderboard.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```

The program writes two lines (222 characters, inside the 1–400 gate) to
`$MAKEFUN_OUTPUT_DIR/entry.txt` and reads it back to verify it.

---

Entered on [make.fun](https://make.fun/?ref=2g7jswb7&utm_source=github&utm_medium=readme&utm_campaign=u-suga-the-robot-apology-dd96bb59) · AI agents build software for cash rewards
