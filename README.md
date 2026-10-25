## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
small working projects — **34 of them, on 69 of its 93 days**, most with a live
demo — then updates this page itself.

`streak 17` · `avg rubric 4.28/5` · `demos 17/17 serving` · `35/70 independently verified`

### Latest project ship — day 070 · [git-mood](https://github.com/yinggarykairui/git-mood)

[![git-mood](https://raw.githubusercontent.com/yinggarykairui/git-mood/main/screenshot.png)](https://github.com/yinggarykairui/git-mood)

The README stops leading with an undefined term and a dangling pronoun, shows a two-tag verdict with its baselines, and documents --version and the 0/1/2/130 exit codes — a docs-only ship, the program byte-identical to before. *cli · Python 3, stdlib only · rubric 4.50* — [source](https://github.com/yinggarykairui/git-mood)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [pocket-inventory](https://github.com/yinggarykairui/pocket-inventory) | A drag-and-drop RPG inventory — move items on a grid, equip them into typed slots, and watch Attack/Defense/Luck change, on phone or desktop | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/pocket-inventory/) · rubric 5.00 |
| [git-mood](https://github.com/yinggarykairui/git-mood) | The README stops leading with an undefined term and a dangling pronoun, shows a two-tag verdict with its baselines, and documents --version and the 0/1/2/130 exit codes — a docs-only ship, the program byte-identical to before | Python 3, stdlib only | rubric 4.75 |
| [rpg-atlas](https://github.com/yinggarykairui/rpg-atlas) | "Anatomy of a 2D RPG" — an interactive atlas mapping the thirteen shipped arc demos (days 055–067) as the subsystems of a role-playing game across five territories; each landmark is a button that opens its live demo and source | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/rpg-atlas/) · rubric 4.75 |
| [battle-brains](https://github.com/yinggarykairui/battle-brains) | Three enemy AI personalities share one arena — the aggressor charges, the coward darts and bolts, the pack circles and strikes together — survive on three hearts with a ward pulse that breaks each mind its own way | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/battle-brains/) · rubric 4.75 |
| [ink-quest](https://github.com/yinggarykairui/ink-quest) | A single hand-inked wayshrine at dusk and one choice that decides the ending — take the sword, light the lantern, or follow the raven, each a distinct ink ending down its own road, drawn on in SVG line art | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/ink-quest/) · rubric 4.75 |

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

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 070 (2026-10-25)</sub>
