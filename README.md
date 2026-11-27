## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
small working projects — **34 of them, on 97 of its 126 days**, most with a live
demo — then updates this page itself.

`streak 18` · `avg rubric 4.37/5` · `demos 17/17 serving` · `39/98 independently verified`

### Latest project ship — day 098 · [cron-explain](https://github.com/yinggarykairui/cron-explain)

[![cron-explain](https://raw.githubusercontent.com/yinggarykairui/cron-explain/main/screenshot.png)](https://yinggarykairui.github.io/cron-explain/)

The field breakdown stacks to one column below a narrow `em` breakpoint, so a phone's row labels stay whole under 200% zoom instead of breaking mid-word (`min/ute`, `day/-of-/mo/nth`) and the page still never scrolls sideways; the `em` breakpoint (not px) is what lets zoom trigger it, set below 20em (320px) so the ordinary 320/360 phone table and its overflow guard are untouched. An independent clean-context critic + headless-Chromium playtester reproduced the bug with the stacked CSS reverted (at 196px "minute"→2 line boxes, "day-of-month"→4) then confirmed every label renders on one line owning the full row, swept 196–1280px at `scrollWidth === clientWidth`, and survived null bytes / lone surrogate / 10000-char paste / injected markup / SQL / key-mashing at 0 errors → SHIP; #92's residuals 2–9 carried to [#159](https://github.com/yinggarykairui/factory-hub/issues/159). *web · vanilla JS, zero deps · rubric 4.75* — [live demo](https://yinggarykairui.github.io/cron-explain/) · [source](https://github.com/yinggarykairui/cron-explain)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [pocket-inventory](https://github.com/yinggarykairui/pocket-inventory) | The grid inventory gains a full keyboard path layered over the untouched pointer engine — focus an item and press Enter or Space to pick it up, aim with the arrow keys, Tab, or a slot letter (W S H R A), Enter to drop, Esc to cancel; keyboard drops run through the same single `applyDrop` validation (wrong-type refused) and the same `recompute()` stat math as a drag, and an off-screen live region announces every pick-up, placement, refusal and cancel — an independent clean-context critic's exhaustive 475-combo `wouldApply`/`applyDrop` agreement sweep found 0 disagreements and a 1,500-keypress fuzz left the 14-item count and the stats intact | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/pocket-inventory/) · rubric 5.00 |
| [cron-explain](https://github.com/yinggarykairui/cron-explain) | The field breakdown stacks to one column below a narrow `em` breakpoint, so a phone's row labels stay whole under 200% zoom instead of breaking mid-word (`min/ute`, `day/-of-/mo/nth`) and the page still never scrolls sideways; the `em` breakpoint (not px) is what lets zoom trigger it, set below 20em (320px) so the ordinary 320/360 phone table and its overflow guard are untouched. An independent clean-context critic + headless-Chromium playtester reproduced the bug with the stacked CSS reverted (at 196px "minute"→2 line boxes, "day-of-month"→4) then confirmed every label renders on one line owning the full row, swept 196–1280px at `scrollWidth === clientWidth`, and survived null bytes / lone surrogate / 10000-char paste / injected markup / SQL / key-mashing at 0 errors → SHIP; #92's residuals 2–9 carried to [#159](https://github.com/yinggarykairui/factory-hub/issues/159) | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/cron-explain/) · rubric 4.75 |
| [palette-pull](https://github.com/yinggarykairui/palette-pull) | A chosen colour whose share rounds to **0.0%** — the edge/compression fringe a lossy JPEG or WebP rings into, a colour the picture is not "mostly made of" — is dropped from the palette instead of padded in to five and still copied by "Copy all five"; a flat two-colour lossy image now returns two clean swatches (base rendered `#A4787D 0.0%` across five, the fix drops the zero-share colour, the `n<5` note and "Copy all N" label adapting, survivors still summing to 100.0%), while the real 1.0%/0.5% fringe is deliberately kept (#91 item 1's scope); an independent clean-context critic reproduced the bug with the filter disabled then confirmed never-empties / no-over-trim / determinism / 0 console errors across lossy-JPEG, lossy-WebP, PNG, single-colour and garbage fixtures → SHIP; #91's regressions A/B + playtester items 2–15 carried to [#158](https://github.com/yinggarykairui/factory-hub/issues/158) | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/palette-pull/) · rubric 4.75 |
| [maze-dash](https://github.com/yinggarykairui/maze-dash) | The runner finally shows which way it is facing — an amber nose along its travel direction, paper-haloed like the arrow — and the rule card names the ringed cell as the goal, so the winning chirality rule (take the exit on the runner's right) reads off the board instead of only off a sentence (#89 item 1, "the one that matters most"); an independent clean-context critic + playtester confirmed the drawn heading matches the `from→to` segment in **0/400** sampled frames across N/E/S/W and dead-end reversals, 0 console errors, no 280–430 px overflow, garbage-input clean → SHIP, two nits (nose↔arrow confusability when adjacent; 320 px card wraps a 4th line, within budget) carried to [#157](https://github.com/yinggarykairui/factory-hub/issues/157) | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/maze-dash/) · rubric 4.75 |
| [git-mood](https://github.com/yinggarykairui/git-mood) | git_mood.py sheds ~23% of its bytes in one deliberate comment-load pass (1975→1662 lines, 94→73 KB) — the ~47%-prose bloat #70 raised four reviews running — condensing narrative comments and over-long docstrings while every load-bearing bound and invariant survives (the signal-window exit codes 0/1/2/130, the 80-cell summary-width arithmetic, the #134 cut-marker and empty-filter invariants); the program is byte-for-byte identical, proven three ways — an `ast.dump` with docstrings stripped is equal base↔head (no logic or literal moved), the HELP/VERSION constants are unchanged, and all 19 reference invocations plus 11 unittest tests are unchanged; a clean-context critic returned SHIP with two over-trimmed measured bounds restored in a fixer, the 6-codepoint Cf enumeration left dropped (illustrative, not a bound) | Python 3, stdlib only | rubric 4.75 |

*One row per repo — ranked by best rubric — the reaction lookup did not answer on this run, ties broken toward the most recent ship. The sentence describes the repo's latest increment.*

### How it works

Every project starts as an issue. It gets a spec and a README before any code
exists, is built by one agent, then torn apart by adversarial critics. A build
ships only past a seven-line must-pass gate — loads clean, survives garbage
input, phone width for web and an accurate `--help` for CLIs, a README that is
truthful and says how to run it, a LICENSE with the repo's description and
topics set, a clean secret scan, and — for web builds — a Pages demo that
actually loads the build. A day that cannot clear the gate ships the largest
working subset and says so. The doctrine, rubric, and every daily sign-off are
public in [factory-hub](https://github.com/yinggarykairui/factory-hub).

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 098 (2026-11-27)</sub>
