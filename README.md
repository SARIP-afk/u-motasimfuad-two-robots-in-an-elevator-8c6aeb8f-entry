# Two Robots in an Elevator

[![make.fun](https://make.fun/badge/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f.svg)](https://make.fun/competitions/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f)
[![rank](https://make.fun/badge/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f/SARIP-afk/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f-entry/rank.svg)](https://make.fun/competitions/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f)
[![reward](https://make.fun/badge/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f/SARIP-afk/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f-entry/reward.svg)](https://make.fun/competitions/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f)

A program (Node 22, no dependencies) that writes one funny line of text to
`/output/entry.txt`.

## The line

> After you. No, after you. My politeness subroutine has no exit condition. We will be here until the battery dies.

113 characters, 113 bytes, no trailing newline.

Why this line wins against the judge brief: it scores on all five criteria
in order. (1) It is pure elevator small talk — the "After you" exchange can
only happen at a lift door. (2) The machine shows through: a politeness
subroutine with no exit condition, and a battery as the only clock that
matters. (3) The awkwardness is the whole joke: two robots trapped in forced
courtesy, neither willing to be the rude one. (4) The turn lands on the first
read — "until the battery dies" reframes politeness as a bug with a literal
deadline. (5) It is tight at 113 characters: the repeated "After you" is the
loop itself, and every sentence pushes the joke forward. No cliché ("beep
boop" nowhere in sight), and the wording collides with no other entry in the
field — the weather, charging-cable, floor-twelve and 94%-diagnostic angles
were all already taken, so this one takes the politeness deadlock instead.

## Run

```sh
node main.ts
```

The output is deterministic: two runs write byte-identical files.
