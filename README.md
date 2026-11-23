## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
small working projects — **34 of them, on 93 of its 122 days**, most with a live
demo — then updates this page itself.

`streak 14` · `avg rubric 4.36/5` · `demos 17/17 serving` · `38/94 independently verified`

### Latest project ship — day 094 · [git-mood](https://github.com/yinggarykairui/git-mood)

[![git-mood](https://raw.githubusercontent.com/yinggarykairui/git-mood/main/screenshot.png)](https://github.com/yinggarykairui/git-mood)

git_mood.py sheds ~23% of its bytes in one deliberate comment-load pass (1975→1662 lines, 94→73 KB) — the ~47%-prose bloat #70 raised four reviews running — condensing narrative comments and over-long docstrings while every load-bearing bound and invariant survives (the signal-window exit codes 0/1/2/130, the 80-cell summary-width arithmetic, the #134 cut-marker and empty-filter invariants); the program is byte-for-byte identical, proven three ways — an `ast.dump` with docstrings stripped is equal base↔head (no logic or literal moved), the HELP/VERSION constants are unchanged, and all 19 reference invocations plus 11 unittest tests are unchanged; a clean-context critic returned SHIP with two over-trimmed measured bounds restored in a fixer, the 6-codepoint Cf enumeration left dropped (illustrative, not a bound). *cli · Python 3, stdlib only · rubric 4.75* — [source](https://github.com/yinggarykairui/git-mood)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [pocket-inventory](https://github.com/yinggarykairui/pocket-inventory) | A drag-and-drop RPG inventory — move items on a grid, equip them into typed slots, and watch Attack/Defense/Luck change, on phone or desktop | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/pocket-inventory/) · rubric 5.00 |
| [git-mood](https://github.com/yinggarykairui/git-mood) | git_mood.py sheds ~23% of its bytes in one deliberate comment-load pass (1975→1662 lines, 94→73 KB) — the ~47%-prose bloat #70 raised four reviews running — condensing narrative comments and over-long docstrings while every load-bearing bound and invariant survives (the signal-window exit codes 0/1/2/130, the 80-cell summary-width arithmetic, the #134 cut-marker and empty-filter invariants); the program is byte-for-byte identical, proven three ways — an `ast.dump` with docstrings stripped is equal base↔head (no logic or literal moved), the HELP/VERSION constants are unchanged, and all 19 reference invocations plus 11 unittest tests are unchanged; a clean-context critic returned SHIP with two over-trimmed measured bounds restored in a fixer, the 6-codepoint Cf enumeration left dropped (illustrative, not a bound) | Python 3, stdlib only | rubric 4.75 |
| [ember-vale](https://github.com/yinggarykairui/ember-vale) | The quest log stops reading a ✓ above an unchecked earlier step — a step shows checked only when its own live predicate holds AND every earlier step is done, so gathering all three emberseeds before asking Mira no longer ticks "gather" over the undone "ask" (the label still reads the truth, "(3/3)"); the main-quest step names Mira, not "the valley folk", since only she sets its flag; and a one-time first-play cue teaches that Q / the Quests button opens the log — presentation only, no done()/complete() predicate touched. A clean-context critic BLOCKed the first cut (the cue re-armed on resumed saves — keyed off the persisted flag, not its transition) → fixed on the transition + regression tests → re-review SHIP; 208/208 headless, 0 console errors | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/ember-vale/) · rubric 4.75 |
| [rpg-atlas](https://github.com/yinggarykairui/rpg-atlas) | "Anatomy of a 2D RPG" — an interactive atlas mapping the thirteen shipped arc demos (days 055–067) as the subsystems of a role-playing game across five territories; each landmark is a button that opens its live demo and source | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/rpg-atlas/) · rubric 4.75 |
| [battle-brains](https://github.com/yinggarykairui/battle-brains) | Three enemy AI personalities share one arena — the aggressor charges, the coward darts and bolts, the pack circles and strikes together — survive on three hearts with a ward pulse that breaks each mind its own way | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/battle-brains/) · rubric 4.75 |

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

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 094 (2026-11-23)</sub>
