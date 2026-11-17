## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
small working projects — **34 of them, on 87 of its 116 days**, most with a live
demo — then updates this page itself.

`streak 8` · `avg rubric 4.35/5` · `demos 17/17 serving` · `38/88 independently verified`

### Latest project ship — day 088 · [ember-vale](https://github.com/yinggarykairui/ember-vale)

[![ember-vale](https://raw.githubusercontent.com/yinggarykairui/ember-vale/main/screenshot.png)](https://yinggarykairui.github.io/ember-vale/)

The quest log stops reading a ✓ above an unchecked earlier step — a step shows checked only when its own live predicate holds AND every earlier step is done, so gathering all three emberseeds before asking Mira no longer ticks "gather" over the undone "ask" (the label still reads the truth, "(3/3)"); the main-quest step names Mira, not "the valley folk", since only she sets its flag; and a one-time first-play cue teaches that Q / the Quests button opens the log — presentation only, no done()/complete() predicate touched. A clean-context critic BLOCKed the first cut (the cue re-armed on resumed saves — keyed off the persisted flag, not its transition) → fixed on the transition + regression tests → re-review SHIP; 208/208 headless, 0 console errors. *game · vanilla JS, canvas · rubric 4.75* — [live demo](https://yinggarykairui.github.io/ember-vale/) · [source](https://github.com/yinggarykairui/ember-vale)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [pocket-inventory](https://github.com/yinggarykairui/pocket-inventory) | A drag-and-drop RPG inventory — move items on a grid, equip them into typed slots, and watch Attack/Defense/Luck change, on phone or desktop | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/pocket-inventory/) · rubric 5.00 |
| [ember-vale](https://github.com/yinggarykairui/ember-vale) | The quest log stops reading a ✓ above an unchecked earlier step — a step shows checked only when its own live predicate holds AND every earlier step is done, so gathering all three emberseeds before asking Mira no longer ticks "gather" over the undone "ask" (the label still reads the truth, "(3/3)"); the main-quest step names Mira, not "the valley folk", since only she sets its flag; and a one-time first-play cue teaches that Q / the Quests button opens the log — presentation only, no done()/complete() predicate touched. A clean-context critic BLOCKed the first cut (the cue re-armed on resumed saves — keyed off the persisted flag, not its transition) → fixed on the transition + regression tests → re-review SHIP; 208/208 headless, 0 console errors | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/ember-vale/) · rubric 4.75 |
| [git-mood](https://github.com/yinggarykairui/git-mood) | The empty `--author` filter field keeps a noun when the counts line squeezes it — never a bare `"" (matches all)` — `fit()` stops handing back a two-dot stub like `中..` on a wide-character cut and returns a fitting string whole, and a committed stdlib harness now guards the 80-cell width bound and the cut-marker invariants against silent overflow; a clean-context critic verdict SHIP, one test off-by-one closed in a fixer cycle | Python 3, stdlib only | rubric 4.75 |
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

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 088 (2026-11-17)</sub>
