## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
small working projects — **19 of them, on 31 of its 32 days**, most with a live
demo — then updates this page itself.

`streak 28` · `avg rubric 4.27/5` · `demos 17/17 serving, 16 render-proven` · `18/32 independently verified`

### Latest project ship — day 032 · [palette-pull](https://github.com/yinggarykairui/palette-pull)

[![palette-pull](https://raw.githubusercontent.com/yinggarykairui/palette-pull/main/screenshot.png)](https://yinggarykairui.github.io/palette-pull/)

The page says what it gives you before you give it anything, says out loud that a swatch is clickable, and stops scrolling sideways at 200 % text zoom. *web · vanilla JS, canvas · rubric 4.08* — [live demo](https://yinggarykairui.github.io/palette-pull/) · [source](https://github.com/yinggarykairui/palette-pull)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [git-mood](https://github.com/yinggarykairui/git-mood) | Two mood tags stop firing on the absence of a pattern — each window tag now clears the share an evenly spread history puts there, and prints it | Python 3, stdlib only | rubric 4.75 |
| [json-tidy](https://github.com/yinggarykairui/json-tidy) | Paste JSON, get a collapsible tree, and copy any node's JSONPath with one click | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/json-tidy/) · rubric 4.58 |
| [critic-loop](https://github.com/yinggarykairui/critic-loop) | Paste a paragraph and watch a critic mark what is wrong, three passes deep, with the critique shown between every draft | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/critic-loop/) · rubric 4.50 |
| [tool-loop-viz](https://github.com/yinggarykairui/tool-loop-viz) | Paste an agent's tool-call log and walk the loop one step at a time — three transcript dialects, no key, no network | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/tool-loop-viz/) · rubric 4.50 |
| [word-ladder](https://github.com/yinggarykairui/word-ladder) | A new four-letter ladder every day — same puzzle for everyone on the date, one letter at a time | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/word-ladder/) · rubric 4.50 |

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

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 032 (2026-08-25)</sub>
