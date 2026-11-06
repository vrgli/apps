# VRG apps

Small tools that do one job and then get out of the way. Free to use, free to fork.
The games live next door in [vrgli/arcade](https://github.com/vrgli/arcade); this repo is
for everything that is not a game. One folder per app, one release per app.

| App | What it is | Status |
|---|---|---|
| `quadnav/` | Chrome extension. Keyboard navigation that picks a quarter of the screen first, then labels only the links inside it. Left hand on `Alt`+`1`; the right hand never leaves the mouse. | first release in preparation |
| `mark-my-words/` | Six dials per person (friendly, tech savvy, busy, hierarchy, handholding, delegation) on a radar you drag, plus a note. So you, or your AI, write to each person the way they like to be written to. Local-first, no sign-in, your data stays in a JSON file you own. | in the works |

Each app has its own README with install steps. Releases are tagged `<app>-v<version>` and
attached as zips on the [Releases](https://github.com/vrgli/apps/releases) page.

**How to try an app:** download its zip from the [Releases](https://github.com/vrgli/apps/releases)
page once it is released, unzip, and follow the app's README. Mark My Words has no release yet.

## Ground rules for every app here

- Vanilla JS, zero dependencies, nothing to build. Clone, open, run.
- No account, no server, no telemetry. If an app ever needs a server it says so in its README
  and the local-only mode keeps working.
- Issues are the roadmap. Open one if something is wrong or missing.

## Licence

MIT plus one condition — see [LICENSE.md](LICENSE.md): any usable copy keeps a visible
"A VRG app" credit linking to https://vrg.li.
