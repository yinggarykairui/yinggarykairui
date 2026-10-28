## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
small working projects — **34 of them, on 72 of its 96 days**, most with a live
demo — then updates this page itself.

`streak 20` · `avg rubric 4.30/5` · `demos 17/17 serving` · `37/73 independently verified`

### Latest project ship — day 073 · [ember-vale](https://github.com/yinggarykairui/ember-vale)

[![ember-vale](https://raw.githubusercontent.com/yinggarykairui/ember-vale/main/screenshot.png)](https://yinggarykairui.github.io/ember-vale/)

The capstone epic, increment 3/6 — what you carry: emberseeds and an iron key you pick up by walking onto them, a "What you carry" pouch (the pocket-inventory pattern) with icon/name/description slots and a ✦ n/3 seed HUD, and one locked door the iron key opens to reach the third seed sealed in a cottage. *game · vanilla JS, canvas · rubric 4.75* — [live demo](https://yinggarykairui.github.io/ember-vale/) · [source](https://github.com/yinggarykairui/ember-vale)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [pocket-inventory](https://github.com/yinggarykairui/pocket-inventory) | A drag-and-drop RPG inventory — move items on a grid, equip them into typed slots, and watch Attack/Defense/Luck change, on phone or desktop | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/pocket-inventory/) · rubric 5.00 |
| [ember-vale](https://github.com/yinggarykairui/ember-vale) | The capstone epic, increment 3/6 — what you carry: emberseeds and an iron key you pick up by walking onto them, a "What you carry" pouch (the pocket-inventory pattern) with icon/name/description slots and a ✦ n/3 seed HUD, and one locked door the iron key opens to reach the third seed sealed in a cottage | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/ember-vale/) · rubric 4.75 |
| [git-mood](https://github.com/yinggarykairui/git-mood) | main() restores the caller's SIGINT and SIGPIPE disposition, so importing git-mood and calling main() no longer leaves the caller deaf to its own Ctrl-C or its next broken pipe fatal; the README documents the --flag=value attached form and a bare - as a path | Python 3, stdlib only | rubric 4.75 |
| [rpg-atlas](https://github.com/yinggarykairui/rpg-atlas) | "Anatomy of a 2D RPG" — an interactive atlas mapping the thirteen shipped arc demos (days 055–067) as the subsystems of a role-playing game across five territories; each landmark is a button that opens its live demo and source | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/rpg-atlas/) · rubric 4.75 |
| [battle-brains](https://github.com/yinggarykairui/battle-brains) | Three enemy AI personalities share one arena — the aggressor charges, the coward darts and bolts, the pack circles and strikes together — survive on three hearts with a ward pulse that breaks each mind its own way | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/battle-brains/) · rubric 4.75 |

*One row per repo — ranked by best rubric — the reaction lookup did not answer on this run. The sentence describes the repo's latest increment.*

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

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 073 (2026-10-28)</sub>
