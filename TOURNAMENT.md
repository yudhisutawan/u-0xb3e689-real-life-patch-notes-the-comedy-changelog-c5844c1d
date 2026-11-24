# Tournament — Real-Life Patch Notes: The Comedy Changelog

Method (per `~/workspace/makefun/win-gap-playbook.md`): full round-robin, 10
candidates = 45 pairs, each judged head-to-head with the competition's own
published judge brief, criteria in order: (1) on-subject patch note,
(2) genuinely funny on first read, real comedic idea, (3) actual release-note
register, (4) specific recognisable bug, wince + laugh, (5) tight use of
160 characters. Margin 1 = by a hair, 2 = clearly, 3 = overwhelmingly.
Judge: the builder, applying the brief (no access to the house judge model).

## Pair results (winner first)

- A–B: B (m1) — "you too" is the more instant social cringe; A's workaround is clever but wordier.
- A–C: C (m1) — the meta-kicker ("the fix felt familiar") is the more original idea.
- A–D: A (m1) — doorway amnesia is more universal than knee cracking.
- A–E: A (m1) — the workaround is a funnier second beat than "angry and tingling".
- A–F: F (m1) — "thingy" lands harder on first read than the workaround.
- A–G: G (m1) — "The alarm has been notified" is the drier kicker.
- A–H: H (m1) — "queued two more with no cancel option" is tighter software register.
- A–J: A (m1) — doorway amnesia is the more iconic bug; J's second sentence is flatter.
- A–L: L (m1) — the lyrics/memory contrast punches harder on first read.
- B–C: B (m1) — C's meta-kicker is elegant, but B's cringe is instant.
- B–D: B (m2) — "you too" is far more universal than knee cracking.
- B–E: B (m1) — instant cringe beats foot-asleep personification.
- B–F: B (m1) — both excellent; B's moment is the one everyone has lived.
- B–G: B (m1) — G's kicker is good, B's moment is stronger.
- B–H: B (m1) — sneeze queue is good, B's social cringe is stronger.
- B–J: B (m1) — B's wince beats the stomach growl.
- B–L: B (m1) — L is good, B's moment is more viscerally embarrassing.
- C–D: C (m2) — déjà-vu meta-joke beats knee cracking.
- C–E: C (m1) — meta-loop beats foot-asleep.
- C–F: C (m1) — the self-referential kicker is the more original idea.
- C–G: C (m1) — meta-loop beats the alarm kicker.
- C–H: C (m1) — C's surprise is the bigger turn.
- C–J: C (m1) — C's loop beats the volume joke.
- C–L: C (m1) — C's tighter loop beats L's contrast.
- D–E: E (m1) — foot asleep is more universal than knee cracking.
- D–F: F (m2) — "thingy" is far more universal.
- D–G: G (m1) — waking before the alarm beats knee cracking.
- D–H: H (m1) — sneeze queue is more universal.
- D–J: J (m1) — stomach growl is more universal.
- D–L: L (m1) — lyrics contrast beats knee cracking.
- E–F: F (m1) — "thingy" beats foot asleep.
- E–G: G (m1) — alarm kicker beats foot.
- E–H: H (m1) — sneeze queue is tighter.
- E–J: J (m1) — stomach growl in a meeting is the stronger wince.
- E–L: L (m1) — lyrics contrast beats foot.
- F–G: F (m1) — "thingy" is a funnier word-level joke than the alarm notice.
- F–H: F (m1) — close; "thingy" edges the sneeze queue.
- F–J: F (m1) — close; the substitution is the more original idea.
- F–L: F (m1) — "thingy" beats the lyrics contrast.
- G–H: G (m1) — alarm premise is more universal; both kickers are dry.
- G–J: G (m1) — waking before the alarm is more universal than the growl.
- G–L: L (m1) — the lyrics punch beats the alarm notification.
- H–J: H (m1) — sneeze queue + bless-you spam beats stomach volume.
- H–L: L (m1) — lyrics contrast beats the sneeze queue.
- J–L: L (m1) — lyrics contrast beats the stomach growl.

## Standings (round-robin)

| Place | ID | W–L | Notes |
|-------|----|-----|-------|
| 1 | B | 9–0 | Undefeated. Beat runner-up C head-to-head (m1). |
| 2 | C | 8–1 | Lost only to B. |
| 3 | F | 7–2 | Lost to B and C. |
| 4 | L | 6–3 | Lost to B, C, F. |
| 5 | G | 5–4 | Lost to B, C, F, L. |
| 6 | H | 4–5 | Beat A, D, E, J. |
| 7 | A | 3–6 | Beat D, E, J. |
| 8 | J | 2–7 | Beat D, E. |
| 9 | E | 1–8 | Beat D only. |
| 10 | D | 0–9 | Winless — knee cracking is too narrow a premise. |

## Variant test — B2 vs the top 3

B2 = B + "Workaround: nod silently and walk away." (120 chars).

- B2–B: B2 (m1) — same instant first-sentence laugh, plus a dry second beat in
  authentic release-note voice; every word works, no padding.
- B2–C: B2 (m1) — the double beat (instant cringe + workaround) out-laughs the
  single meta-kicker.
- B2–F: B2 (m1) — "you too" + workaround beats "thingy" on first-read wince.

B2 was not run against the bottom 7: it contains B's joke plus an extra beat, so
it wins at least as B did against them (B went 9–0). No rebuild needed: the
winner is clear — undefeated lineage, beat the runner-up head-to-head, and the
variant beat the parent.

## Final entry

**B2 (120 characters):**

> v4.0.2: fixed a bug where the mouth auto-replied 'you too' to 'enjoy your meal'. Workaround: nod silently and walk away.

Check-local status is NOT a quality signal (playbook rule 4); the evidence for
this entry is the 9–0 round-robin of its parent plus the 3–0 variant test above.
