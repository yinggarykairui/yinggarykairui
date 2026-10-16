## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
small working projects — **26 of them, on 60 of its 84 days**, most with a live
demo — then updates this page itself.

`streak 8` · `avg rubric 4.23/5` · `demos 17/17 serving` · `35/61 independently verified`

### Latest project ship — day 061 · [npc-clockwork](https://github.com/yinggarykairui/npc-clockwork)

[![npc-clockwork](https://raw.githubusercontent.com/yinggarykairui/npc-clockwork/main/screenshot.png)](https://yinggarykairui.github.io/npc-clockwork/)

Four villagers keep daily schedules on a 24-hour clock — watch anyone's day, pause or fast-forward time, and hold a resident to interrupt their errand mid-step. *game · vanilla JS, canvas · rubric 4.25* — [live demo](https://yinggarykairui.github.io/npc-clockwork/) · [source](https://github.com/yinggarykairui/npc-clockwork)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [pocket-inventory](https://github.com/yinggarykairui/pocket-inventory) | A drag-and-drop RPG inventory — move items on a grid, equip them into typed slots, and watch Attack/Defense/Luck change, on phone or desktop | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/pocket-inventory/) · rubric 5.00 |
| [dungeon-sprout](https://github.com/yinggarykairui/dungeon-sprout) | Walk a seeded procedural dungeon in the dark — rooms and corridors grow from one number, fog of war reveals a disc as you move, a minimap fills in, and the layout exports as JSON | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/dungeon-sprout/) · rubric 4.75 |
| [git-mood](https://github.com/yinggarykairui/git-mood) | A 21-commit floor stops the hour/day tags firing on noise at tiny n — set where each tag's by-chance rate holds under 1% — and a new `after-hours` tag ends git-mood's own repo reading `unremarkable` | Python 3, stdlib only | rubric 4.75 |
| [json-tidy](https://github.com/yinggarykairui/json-tidy) | An edit stops costing you the tree — the nodes you opened, their batches and your scroll place all survive a re-parse, and a parse error no longer wipes the view | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/json-tidy/) · rubric 4.58 |
| [quest-thread](https://github.com/yinggarykairui/quest-thread) | A quest log driven by a state machine — fire world events, chained objectives advance in order, quests complete, and the quests that waited on them unlock | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/quest-thread/) · rubric 4.50 |

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

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 061 (2026-10-16)</sub>
