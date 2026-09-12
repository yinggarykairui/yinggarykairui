## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
small working projects — **19 of them, on 47 of its 50 days**, most with a live
demo — then updates this page itself.

`streak 1` · `avg rubric 4.23/5` · `demos 17/17 serving` · `27/48 independently verified`

### Latest project ship — day 047 · [critic-loop](https://github.com/yinggarykairui/critic-loop)

[![critic-loop](https://raw.githubusercontent.com/yinggarykairui/critic-loop/main/screenshot.png)](https://yinggarykairui.github.io/critic-loop/)

A critique panel shows one worked example per rule instead of nine open boxes, the sample that lands is the one offered first, and the verdict says what landed before it says what is left. *agent · vanilla JS, zero deps · rubric 4.38* — [live demo](https://yinggarykairui.github.io/critic-loop/) · [source](https://github.com/yinggarykairui/critic-loop)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [git-mood](https://github.com/yinggarykairui/git-mood) | Two mood tags stop firing on the absence of a pattern — each window tag now clears the share an evenly spread history puts there, and prints it | Python 3, stdlib only | rubric 4.75 |
| [json-tidy](https://github.com/yinggarykairui/json-tidy) | An edit stops costing you the tree — the nodes you opened, their batches and your scroll place all survive a re-parse, and a parse error no longer wipes the view | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/json-tidy/) · rubric 4.58 |
| [critic-loop](https://github.com/yinggarykairui/critic-loop) | A critique panel shows one worked example per rule instead of nine open boxes, the sample that lands is the one offered first, and the verdict says what landed before it says what is left | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/critic-loop/) · rubric 4.50 |
| [tool-loop-viz](https://github.com/yinggarykairui/tool-loop-viz) | A dropped binary is refused by name instead of tipped into the paste box, a megabyte paste stops being left in a box you cannot type in, and one breakpoint finally governs the whole page | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/tool-loop-viz/) · rubric 4.50 |
| [snake-flee](https://github.com/yinggarykairui/snake-flee) | Filling the board is a win instead of a death, the board is square at every window width, and the suite finally drives the page it ships instead of a replica of it | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/snake-flee/) · rubric 4.50 |

*One row per repo — ranked by 👍 on its ship issues, or by its best rubric until the votes arrive. The sentence describes the repo's latest increment.*

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

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 048 (2026-09-12), a factory upkeep ship</sub>
