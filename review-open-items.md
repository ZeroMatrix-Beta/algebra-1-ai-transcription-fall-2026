# Open items from the final review

The final review of the lecture notes (12–13 October 2026) fixed what it found in commit `fd085cf`, except three spots that can only be settled against the lecture recordings, which are not on this computer. Each one needs a few seconds of audio; item 3 also needs the video.

When an item is settled, fix it, rebuild `algebra-1.pdf`, and delete the item from this file (or the whole file, once all three are done).

## 1. Week 2 Tuesday: "the origin of this $n$"

- **Where:** [`content/step4-2026-09-22-tuesday-week2-algebra-1-offset-final.tex`, line 1345](content/step4-2026-09-22-tuesday-week2-algebra-1-offset-final.tex#L1345), near the end of the speech block `[00:50:20 - 00:50:43]` (line 1342).
- **Current text:** "Okay, but that's the origin of this $n$. So, we have to prove something."
- **Suspected:** "the origin of this **name**". The lecturer has just explained where the word "ideal" comes from (ideal numbers, Hilbert's epitaph); an $n$ has nothing to refer to there.
- **Check:** recording `2026-09-22-tuesday-week2-algebra-1.mp4`, 00:50:20–00:50:43.
- **Fix if confirmed:** replace `this $n$` with `this name`.

## 2. Week 2 Tuesday: "there's a motion giving a vector space another one"

- **Where:** [same file, line 2428](content/step4-2026-09-22-tuesday-week2-algebra-1-offset-final.tex#L2428), in the speech block `[01:30:08 - 01:30:50]` (line 2423).
- **Current text:** "I'm just saying there's a motion giving a vector space another one, and that's the double dual, and it's functorial in this sense."
- **Suspected:** "there's a **notion** giving a vector space another one". "Motion" makes no sense here.
- **Check:** same recording, 01:30:08–01:30:50.
- **Fix if confirmed:** replace `motion` with `notion`.

## 3. Week 4 Wednesday: two speech blocks overlap by 10 seconds

- **Where:** [`content/step4-2026-10-07-wednesday-week4-algebra-1-offset-final.tex`, lines 216 and 240–241](content/step4-2026-10-07-wednesday-week4-algebra-1-offset-final.tex#L240).
- **Problem:** the block at line 216 is `[00:07:05 - 00:08:15]`, but the next block (line 241) starts at `00:08:05`. Line 240 still carries the pipeline's marker `% [TIMESTAMP-SUSPECT: inspect manually — original: 00:08:05 - 00:10:25]`.
- **Check:** in the 7 October recording, find where "…that's the main thing this week." ends and "So, we'll explore (ii) a bit more today." begins. Shortly after, the lecturer writes "Let f: R → S be any hom. of rings" on the board. This file's pipeline header names the run `2026-10-07-wednesday-week3-algebra-1`, so the recording may carry that name rather than `week4`.
- **Fix:** set the end of the first block and the start of the second to that time. Replace the marker on line 240 with a `% [TIMESTAMP-CORRECTED: …]` comment saying what the recording showed, as the other lecture files do.
