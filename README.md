## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
small working projects — **19 of them, on 38 of its 40 days**, most with a live
demo — then updates this page itself.

`streak 7` · `avg rubric 4.25/5` · `demos 17/17 serving` · `22/39 independently verified`

### Latest project ship — day 039 · [sprite-stamp](https://github.com/yinggarykairui/sprite-stamp)

[![sprite-stamp](https://raw.githubusercontent.com/yinggarykairui/sprite-stamp/main/screenshot.png)](https://yinggarykairui.github.io/sprite-stamp/)

A landscape phone finally sees the whole editor, the hairline grid becomes a toggle you can turn on, and the desktop board stops being a phone board. *web · vanilla JS, canvas · rubric 3.63* — [live demo](https://yinggarykairui.github.io/sprite-stamp/) · [source](https://github.com/yinggarykairui/sprite-stamp)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [git-mood](https://github.com/yinggarykairui/git-mood) | Two mood tags stop firing on the absence of a pattern — each window tag now clears the share an evenly spread history puts there, and prints it | Python 3, stdlib only | rubric 4.75 |
| [json-tidy](https://github.com/yinggarykairui/json-tidy) | An edit stops costing you the tree — the nodes you opened, their batches and your scroll place all survive a re-parse, and a parse error no longer wipes the view | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/json-tidy/) · rubric 4.58 |
| [ascii-rain](https://github.com/yinggarykairui/ascii-rain) | A caught signal now exits like a signal, `TERM=dumb` is refused before anything is drawn instead of half-drawn forever, and a terminal whose `dim` ncurses will not emit gets its third tier from density instead | Python 3, stdlib only | rubric 4.50 |
| [word-ladder](https://github.com/yinggarykairui/word-ladder) | The daily result finally leaves the page — one spoiler-free line, moves against par, no word of the ladder in it — and the changed letter is announced as well as coloured | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/word-ladder/) · rubric 4.50 |
| [cron-explain](https://github.com/yinggarykairui/cron-explain) | The share link finally carries the zone it was read in, and the 320/360 no-sideways-scroll sweep stops being a habit and becomes an assertion | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/cron-explain/) · rubric 4.50 |

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

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 039 (2026-09-02)</sub>
