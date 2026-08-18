## Kairui Ying

I design autonomous systems that finish what they start. The proof runs daily:
a build factory I wrote specs, builds, adversarially reviews, and deploys
**one small working project every day** — most with a live demo — then updates
this page itself.

`streak **21**` · `avg rubric **4.33**/5` · `demos alive 16/16`

### Latest ship — day 025 · [tool-loop-viz](https://github.com/yinggarykairui/tool-loop-viz)

[![tool-loop-viz](https://raw.githubusercontent.com/yinggarykairui/tool-loop-viz/main/screenshot.png)](https://yinggarykairui.github.io/tool-loop-viz/)

Paste an agent's tool-call log and walk the loop one step at a time — three transcript dialects, no key, no network. *agent · vanilla JS, zero deps · rubric 4.33* — [live demo](https://yinggarykairui.github.io/tool-loop-viz/) · [source](https://github.com/yinggarykairui/tool-loop-viz)

### Best builds

| build | what it does | stack | proof |
|-------|--------------|-------|-------|
| [git-mood](https://github.com/yinggarykairui/git-mood) | A terminal mood chart for a git repo — tempo, a punch-card clock, streaks, and tags that print their own arithmetic | Python 3, stdlib only | rubric 4.75 |
| [json-tidy](https://github.com/yinggarykairui/json-tidy) | Paste JSON, get a collapsible tree, and copy any node's JSONPath with one click | vanilla JS, zero deps | [demo](https://yinggarykairui.github.io/json-tidy/) · rubric 4.58 |
| [orbit-doodle](https://github.com/yinggarykairui/orbit-doodle) | The pen orbits your cursor — you steer, physics draws the flourishes | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/orbit-doodle/) · rubric 4.50 |
| [trace-lens](https://github.com/yinggarykairui/trace-lens) | Deep-link any moment of the replay; opened tool cards survive scrubbing | TypeScript, React, canvas | [demo](https://yinggarykairui.github.io/trace-lens/) · rubric 4.50 |
| [orbit-doodle](https://github.com/yinggarykairui/orbit-doodle) | Undo, redo, and three pens — every stroke kept as a path, not a picture | vanilla JS, canvas | [demo](https://yinggarykairui.github.io/orbit-doodle/) · rubric 4.50 |

*Ranked by reactions on ship issues, rubric score until the votes arrive.*

### How it works

Every project starts as an issue. It gets a spec and a README before any code
exists, is built by one agent, then torn apart by adversarial critics — a build
ships only past a seven-line must-pass gate (loads clean, survives garbage
input, works at phone width, truthful README, licensed, secret-scanned, demo
live). The doctrine, rubric, and every daily sign-off are public in
[factory-hub](https://github.com/yinggarykairui/factory-hub).

<sub>Maintained by the factory · [dashboard](https://yinggarykairui.github.io/factory-hub/) · last updated day 025 (2026-08-18)</sub>
