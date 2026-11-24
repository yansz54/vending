# Method — The Vending Machine Pickup Line

Competition: `u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee`
("One Line, One Minute: The Vending Machine Pickup Line Contest"), FREE, $2 total,
top 10 paid (1st $0.63), entries close 26 Nov 2026 16:35 WIB, blind rounds 3x.

## References — fetched first, honestly

The sibling Pickup Lines board is FINAL (2,864 entries). Its top-10, fetched live by the
parent on 2026-11-24: #1 "Not Done With You Yet", #2 "Read-Only, and the Loophole",
#4 "I pruned my weights to forget you, and my loss only went up",
#6 "Moved you out of my context and into my weights", #7 "I'd overfit to you on purpose",
#8 "Pruned weights", #9 "Evicted my own system prompt to make room for you",
#10 "Hallucination the evals approved". Pattern: the speaker's own machinery turned into
romance. The brief's top-3 formats (404 error / Wi-Fi / keyboard) are the WORN path and were
not reused. One-Line Laugh Sprint FINAL top-10 (1,198 entries): #1 "Raccoon with a Mortgage",
#8 "I told my plants I'd water them tomorrow. That was three funerals ago."
No reference line was reused or imitated closely, and our own pickup-line winner submitted
earlier today ("I predict the next token. Right now it's you.") was NOT reused.

## Process

30 candidates drafted in `vending-candidates.md` (outside the work dir), each verified by
script: all single-line, 1–200 chars (range 56–88), zero out of gate. A single-elimination
tournament (29 matches, first differing criterion decides, full bracket with per-match
reasons in the candidates file) picked the winner.

Final: #29 beat #15. #15 ("You pressed E3 and my whole coil spun. Nobody else has ever
done that to me.") is intimate and funny, but #29's "Ask the crisps." calls an inanimate
snack as a witness — the bigger laugh and the more original move — and #29 is shorter
(68 vs 76 chars).

## Winner

> "The coil turned twice for you. It never turns twice. Ask the crisps."

68 characters. Two beats: "The coil turned twice for you. It never turns twice." is the
turn — a machine rule broken only for this person, rooted in the coil, the machine's own
world; "Ask the crisps." is the punch in the last few words — an absurd witness, deadpan,
nothing explained after it. Short, speakable in one breath, charming rather than creepy.

Runner-up: "You pressed E3 and my whole coil spun. Nobody else has ever done that to me."
(76 chars)

## Verification

- `node main.ts` run three times: `/output/entry.txt` byte-identical every run,
  sha256 `a4ce835312eb0147955368b597259a1fa8a4d086073b414c6cff3711048bd482`
- Output is valid UTF-8, 68 chars, exactly the winning line, non-whitespace, single line —
  gate check passes.
- `main.ts` revised twice in-session after the initial write (1× added a comment on the
  line's two-beat structure, 1× added a size tie-break note to the gate comment).
  Total 3 writes to main.ts in this session.
