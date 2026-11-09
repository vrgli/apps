# VRG apps

Small tools that do one job and then get out of the way. Free to use, free to fork.
The games live next door in [vrgli/games](https://github.com/vrgli/games).

## Apps

Each app has its own repo, with its own README, install steps and releases.

| App | What it is | Status |
|---|---|---|
| [QuadNav](https://github.com/vrgli/quadnav) | Chrome extension. Keyboard navigation that picks a quarter of the screen first, then labels only the links inside it. Left hand on `Alt`+`1`; the right hand never leaves the mouse. | first release in preparation |
| [Mark My Words](https://github.com/vrgli/mark-my-words) | Six dials per person (friendly, tech savvy, busy, hierarchy, handholding, delegation) on a radar you drag, plus a note. So you, or your AI, write to each person the way they like to be written to. Local-first, no sign-in, your data stays in a JSON file you own. | v0.1 is out: [try it](https://vrgli.github.io/mark-my-words/) or [download](https://github.com/vrgli/mark-my-words/releases/tag/v0.1) |

**How to try an app:** open its repo and download the zip from its Releases page, unzip, and
follow its README. Mark My Words v0.1 is out (it also runs in the browser, no install). QuadNav has
no release yet.

**How to fork an app:** open its repo, click **Fork**, clone your fork.

## Ground rules for every app

- Vanilla JS, zero dependencies, nothing to build. Clone, open, run.
- No account, no server, no telemetry. If an app ever needs a server it says so in its README
  and the local-only mode keeps working.
- Issues are the roadmap. Open one in the app's own repo if something is wrong or missing.

## Licence

MIT plus one condition — see [LICENSE.md](LICENSE.md): any usable copy keeps a visible
"A VRG app" credit linking to https://vrg.li. Every app repo carries the same licence.
