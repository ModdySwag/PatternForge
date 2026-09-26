# Third-party notices — Pattern Forge

Pattern Forge itself — © 2026 Modtech (a.k.a. Moddy), <modtech@gmail.com>, github.com/ModdySwag — is free
software under the GNU AGPL-3.0-or-later (see LICENSE). It bundles **no third-party code, media or data**:
the single `index.html` is Pattern Forge's own source, concatenated by `build.py`. Everything
listed below is either fetched at runtime by the browser, or credited as an influence on original
code. Nothing here is redistributed inside the artifact.

## Fetched at runtime (not bundled)

| Component | Where from | Licence / terms |
|---|---|---|
| **Strudel** `@strudel/repl@1.3.0` (pinned) | `unpkg.com` | AGPL-3.0-or-later. © Felix Roos, Alex McLean and the Strudel / TidalCycles (uzu) contributors. Loaded unmodified and driven through its own editor API. |
| **three.js** `three@0.147.0` (pinned) | `unpkg.com` | MIT. Used by the dancer. |
| **RobotExpressive.glb** | `threejs.org` | CC0 1.0 — Tomás Laulhé, modifications by Don McCurdy. |
| **Xbot.glb / Soldier.glb** | `threejs.org` | Adobe Mixamo assets — used under Mixamo's terms, never redistributed here. |
| **Sample maps** — dough-samples, uzu-drumkit, todepond/samples, felixroos soundfonts | GitHub Pages / raw.githubusercontent.com, pulled by the Strudel engine on demand | Each map's own terms (mostly CC0 / MIT). Not bundled, not mirrored. |
| **The pack store** — `moddys.net/packs/` | first-party hosts | First-party sound banks are CC0 or generated (e.g. Adventure Kid WF, CC0 1.0); pattern packs carry their authors' licences, and the store index names the author of every pack. |
| **Your AI endpoint** (optional) | whatever endpoint you configure | Only used when you switch Kody on and supply a key of your own. Keys are stored in `localStorage` and sent only to that endpoint. |

## Influences credited in the source (original code, not copied)

- **Hardware Forge theme** — after stevebarakat/Minimoog and Playtronica's DX7.
- **Kody's prompt design** — adapted from `nicholasgriffintn/ai-platform` (Apache-2.0); the prompt
  is assembled from Pattern Forge's own live data arrays.
- **`strudel-box`** (deep2universe, MIT) — its share-to-strudel.cc scheme, `Ctrl+.` hush and
  starter patterns inspired features and a pack.
- **UhhyouWebSynthesizers** (ryukau, Apache-2.0) — SquareMorph's morph inspired the waveform morph;
  IntegerChord / GlitchSprinkler pitch sets inspired the tuning tools.

If you redistribute a *pack* from the store, follow that pack's own licence line — it is printed in
the store index and shown on the pack card in the app.
