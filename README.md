## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
small working projects — **30 of them, on 64 of its 88 days**, most with a live
demo — then updates this page itself.

`streak 12` · `avg rubric 4.26/5` · `demos 17/17 serving` · `35/65 independently verified`

### Latest project ship — day 065 · [ink-quest](https://github.com/yinggarykairui/ink-quest)

[![ink-quest](https://raw.githubusercontent.com/yinggarykairui/ink-quest/main/screenshot.png)](https://yinggarykairui.github.io/ink-quest/)

A single hand-inked wayshrine at dusk and one choice that decides the ending — take the sword, light the lantern, or follow the raven, each a distinct ink ending down its own road, drawn on in SVG line art. *game · vanilla JS, inline SVG · rubric 4.75* — [live demo](https://yinggarykairui.github.io/ink-quest/) · [source](https://github.com/yinggarykairui/ink-quest)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [pocket-inventory](https://github.com/yinggarykairui/pocket-inventory) | A drag-and-drop RPG inventory — move items on a grid, equip them into typed slots, and watch Attack/Defense/Luck change, on phone or desktop | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/pocket-inventory/) · rubric 5.00 |
| [ink-quest](https://github.com/yinggarykairui/ink-quest) | A single hand-inked wayshrine at dusk and one choice that decides the ending — take the sword, light the lantern, or follow the raven, each a distinct ink ending down its own road, drawn on in SVG line art | vanilla JS, inline SVG | [demo](https://yinggarykairui.github.io/ink-quest/) · rubric 4.75 |
| [save-crystal](https://github.com/yinggarykairui/save-crystal) | A save system for a 2D RPG — named slots, checksum-guarded snapshots, schema migration, and a corruption guard that refuses a bad save instead of loading garbage | vanilla JS, localStorage | [demo](https://yinggarykairui.github.io/save-crystal/) · rubric 4.75 |
| [shop-keeper](https://github.com/yinggarykairui/shop-keeper) | Buy low and sell high across seeded market days, haggling each trade three pushes toward the fair price — grow 120 gold to 400 as supply and demand swing every price, and you are the only supply and demand | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/shop-keeper/) · rubric 4.75 |
| [parley](https://github.com/yinggarykairui/parley) | A duel fought entirely in type — read the foe's telegraphed STRIKE/LUNGE/CRUSH and answer PARRY/DODGE/BRACE to negate-and-riposte or STRIKE to trade; a deterministic three-foe gauntlet, no board and no art | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/parley/) · rubric 4.75 |

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

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 065 (2026-10-20)</sub>
