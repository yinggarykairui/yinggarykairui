## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
small working projects — **34 of them, on 68 of its 92 days**, most with a live
demo — then updates this page itself.

`streak 16` · `avg rubric 4.28/5` · `demos 17/17 serving` · `35/69 independently verified`

### Latest project ship — day 069 · [ember-vale](https://github.com/yinggarykairui/ember-vale)

[![ember-vale](https://raw.githubusercontent.com/yinggarykairui/ember-vale/main/screenshot.png)](https://yinggarykairui.github.io/ember-vale/)

The capstone epic, increment 1/6 — a short 2D RPG built one piece at a time; increment 1 is the overworld: walk a hand-authored dusk valley with axis-separated collision and a clamped camera, and read its signposts and the dimming Ember. *game · vanilla JS, canvas · rubric 4.50* — [live demo](https://yinggarykairui.github.io/ember-vale/) · [source](https://github.com/yinggarykairui/ember-vale)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [pocket-inventory](https://github.com/yinggarykairui/pocket-inventory) | A drag-and-drop RPG inventory — move items on a grid, equip them into typed slots, and watch Attack/Defense/Luck change, on phone or desktop | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/pocket-inventory/) · rubric 5.00 |
| [rpg-atlas](https://github.com/yinggarykairui/rpg-atlas) | "Anatomy of a 2D RPG" — an interactive atlas mapping the thirteen shipped arc demos (days 055–067) as the subsystems of a role-playing game across five territories; each landmark is a button that opens its live demo and source | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/rpg-atlas/) · rubric 4.75 |
| [battle-brains](https://github.com/yinggarykairui/battle-brains) | Three enemy AI personalities share one arena — the aggressor charges, the coward darts and bolts, the pack circles and strikes together — survive on three hearts with a ward pulse that breaks each mind its own way | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/battle-brains/) · rubric 4.75 |
| [ink-quest](https://github.com/yinggarykairui/ink-quest) | A single hand-inked wayshrine at dusk and one choice that decides the ending — take the sword, light the lantern, or follow the raven, each a distinct ink ending down its own road, drawn on in SVG line art | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/ink-quest/) · rubric 4.75 |
| [save-crystal](https://github.com/yinggarykairui/save-crystal) | A save system for a 2D RPG — named slots, checksum-guarded snapshots, schema migration, and a corruption guard that refuses a bad save instead of loading garbage | vanilla JS, localStorage | [demo](https://yinggarykairui.github.io/save-crystal/) · rubric 4.75 |

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

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 069 (2026-10-24)</sub>
