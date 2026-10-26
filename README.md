## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
small working projects — **34 of them, on 70 of its 94 days**, most with a live
demo — then updates this page itself.

`streak 18` · `avg rubric 4.29/5` · `demos 17/17 serving` · `36/71 independently verified`

### Latest project ship — day 071 · [ember-vale](https://github.com/yinggarykairui/ember-vale)

[![ember-vale](https://raw.githubusercontent.com/yinggarykairui/ember-vale/main/screenshot.png)](https://yinggarykairui.github.io/ember-vale/)

The capstone epic, increment 2/6 — the people who stayed: three villagers (the Warden, Mira, Bram) with branching, memory-gated dialogue; one interact button dispatched by what you face, so a person opens a conversation while a signpost still just reads; the Warden sets the main quest — the Ember is dying and needs three emberseeds, and Mira and Bram change their lines once it does. *game · vanilla JS, canvas · rubric 4.75* — [live demo](https://yinggarykairui.github.io/ember-vale/) · [source](https://github.com/yinggarykairui/ember-vale)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [pocket-inventory](https://github.com/yinggarykairui/pocket-inventory) | A drag-and-drop RPG inventory — move items on a grid, equip them into typed slots, and watch Attack/Defense/Luck change, on phone or desktop | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/pocket-inventory/) · rubric 5.00 |
| [ember-vale](https://github.com/yinggarykairui/ember-vale) | The capstone epic, increment 2/6 — the people who stayed: three villagers (the Warden, Mira, Bram) with branching, memory-gated dialogue; one interact button dispatched by what you face, so a person opens a conversation while a signpost still just reads; the Warden sets the main quest — the Ember is dying and needs three emberseeds, and Mira and Bram change their lines once it does | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/ember-vale/) · rubric 4.75 |
| [git-mood](https://github.com/yinggarykairui/git-mood) | The README stops leading with an undefined term and a dangling pronoun, shows a two-tag verdict with its baselines, and documents --version and the 0/1/2/130 exit codes — a docs-only ship, the program byte-identical to before | Python 3, stdlib only | rubric 4.75 |
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

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 071 (2026-10-26)</sub>
