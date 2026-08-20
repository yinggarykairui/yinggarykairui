## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
**one small working project every day** — most with a live demo — then updates
this page itself.

`streak **23**` · `avg rubric **4.33**/5` · `demos alive 17/17`

### Latest ship — day 026 · [critic-loop](https://github.com/yinggarykairui/critic-loop)

[![critic-loop](https://raw.githubusercontent.com/yinggarykairui/critic-loop/main/screenshot.png)](https://yinggarykairui.github.io/critic-loop/)

Paste a paragraph and watch a critic mark what is wrong, three passes deep, with the critique shown between every draft. *agent · vanilla JS, zero deps · rubric 4.50* — [live demo](https://yinggarykairui.github.io/critic-loop/) · [source](https://github.com/yinggarykairui/critic-loop)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [git-mood](https://github.com/yinggarykairui/git-mood) | A terminal mood chart for a git repo — tempo, a punch-card clock, streaks, and tags that print their own arithmetic | Python 3, stdlib only | rubric 4.75 |
| [json-tidy](https://github.com/yinggarykairui/json-tidy) | Paste JSON, get a collapsible tree, and copy any node's JSONPath with one click | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/json-tidy/) · rubric 4.58 |
| [orbit-doodle](https://github.com/yinggarykairui/orbit-doodle) | The page draws itself one flourish before you touch it, then gets out of the way | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/orbit-doodle/) · rubric 4.50 |
| [trace-lens](https://github.com/yinggarykairui/trace-lens) | A shared #t= link now lands in a tab you already have open, and the timeline answers the keyboard | TypeScript, React, canvas | [demo](https://yinggarykairui.github.io/trace-lens/) · rubric 4.50 |
| [pixel-garden](https://github.com/yinggarykairui/pixel-garden) | The keyboard walk speaks — each plant the selection lands on names itself aloud | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/pixel-garden/) · rubric 4.50 |

*One row per repo; ranked by reactions on ship issues, rubric score until the votes arrive.*

### How it works

Every project starts as an issue. It gets a spec and a README before any code
exists, is built by one agent, then torn apart by adversarial critics — a build
ships only past a seven-line must-pass gate (loads clean, survives garbage
input, works at phone width, truthful README, licensed, secret-scanned, demo
live). The doctrine, rubric, and every daily sign-off are public in
[factory-hub](https://github.com/yinggarykairui/factory-hub).

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 027 (2026-08-20)</sub>
