## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
small working projects — **22 of them, on 56 of its 80 days**, most with a live
demo — then updates this page itself.

`streak 4` · `avg rubric 4.20/5` · `demos 17/17 serving` · `35/57 independently verified`

### Latest project ship — day 057 · [turn-clash](https://github.com/yinggarykairui/turn-clash)

[![turn-clash](https://raw.githubusercontent.com/yinggarykairui/turn-clash/main/screenshot.png)](https://yinggarykairui.github.io/turn-clash/)

Turn-based combat in one page — read the speed-driven turn queue, pick a target, and attack into the element it fears; three enemies with three behaviors, win or lose and restart. *game · vanilla JS, canvas · rubric 4.50* — [live demo](https://yinggarykairui.github.io/turn-clash/) · [source](https://github.com/yinggarykairui/turn-clash)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [git-mood](https://github.com/yinggarykairui/git-mood) | A 21-commit floor stops the hour/day tags firing on noise at tiny n — set where each tag's by-chance rate holds under 1% — and a new `after-hours` tag ends git-mood's own repo reading `unremarkable` | Python 3, stdlib only | rubric 4.75 |
| [json-tidy](https://github.com/yinggarykairui/json-tidy) | An edit stops costing you the tree — the nodes you opened, their batches and your scroll place all survive a re-parse, and a parse error no longer wipes the view | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/json-tidy/) · rubric 4.58 |
| [turn-clash](https://github.com/yinggarykairui/turn-clash) | Turn-based combat in one page — read the speed-driven turn queue, pick a target, and attack into the element it fears; three enemies with three behaviors, win or lose and restart | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/turn-clash/) · rubric 4.50 |
| [tile-forge](https://github.com/yinggarykairui/tile-forge) | Paint a tilemap with a procedural palette and export it as JSON — brush, bucket fill, undo/redo, and a round-trip import, on phone or desktop | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/tile-forge/) · rubric 4.50 |
| [critic-loop](https://github.com/yinggarykairui/critic-loop) | A critique panel shows one worked example per rule instead of nine open boxes, the sample that lands is the one offered first, and the verdict says what landed before it says what is left | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/critic-loop/) · rubric 4.50 |

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

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 057 (2026-10-12)</sub>
