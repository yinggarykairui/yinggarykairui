## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
small working projects — **34 of them, on 71 of its 95 days**, most with a live
demo — then updates this page itself.

`streak 19` · `avg rubric 4.29/5` · `demos 17/17 serving` · `37/72 independently verified`

### Latest project ship — day 072 · [git-mood](https://github.com/yinggarykairui/git-mood)

[![git-mood](https://raw.githubusercontent.com/yinggarykairui/git-mood/main/screenshot.png)](https://github.com/yinggarykairui/git-mood)

main() restores the caller's SIGINT and SIGPIPE disposition, so importing git-mood and calling main() no longer leaves the caller deaf to its own Ctrl-C or its next broken pipe fatal; the README documents the --flag=value attached form and a bare - as a path. *cli · Python 3, stdlib only · rubric 4.75* — [source](https://github.com/yinggarykairui/git-mood)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [pocket-inventory](https://github.com/yinggarykairui/pocket-inventory) | A drag-and-drop RPG inventory — move items on a grid, equip them into typed slots, and watch Attack/Defense/Luck change, on phone or desktop | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/pocket-inventory/) · rubric 5.00 |
| [git-mood](https://github.com/yinggarykairui/git-mood) | main() restores the caller's SIGINT and SIGPIPE disposition, so importing git-mood and calling main() no longer leaves the caller deaf to its own Ctrl-C or its next broken pipe fatal; the README documents the --flag=value attached form and a bare - as a path | Python 3, stdlib only | rubric 4.75 |
| [ember-vale](https://github.com/yinggarykairui/ember-vale) | The capstone epic, increment 2/6 — the people who stayed: three villagers (the Warden, Mira, Bram) with branching, memory-gated dialogue; one interact button dispatched by what you face, so a person opens a conversation while a signpost still just reads; the Warden sets the main quest — the Ember is dying and needs three emberseeds, and Mira and Bram change their lines once it does | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/ember-vale/) · rubric 4.75 |
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

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 072 (2026-10-27)</sub>
