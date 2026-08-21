# sands-matchmaking

Live prototypes for **Sponsor Matchmaking** in the conference app (SandS Media).

Root is the prototype. Everything under `flows/` is an annotated user-flow prototype.

| Path | What it is | Link |
|---|---|---|
| `/` | **Matchmaking v1** — attendee ↔ partner matchmaking inside the existing app. Check-in, intro, the swipe deck, the summary, and the Partners overview in its matched state. `Kontakt teilen` is the one control — Matchmaking changes its state, it never adds a second button. | [open](https://tcappelletti-stack.github.io/sands-matchmaking/) |
| `/flows/` | Annotated user flows — one folder per epic (`flows/epic1/`) or per ticket (`flows/PROD-xxxx/`). None published yet. | — |

All prototypes are self-contained single-file HTML — no build, no install, no login.

**All prototypes:** [sands-prototypes](https://tcappelletti-stack.github.io/sands-prototypes/)

## Notes

- This is the **conference app**, not Workbench. Different product, different vocabulary.
- Attendee-facing copy follows the app: `Ausstellier`, `Sponsoren`, `Kontakt teilen`. "Partner" is the internal word only.
- Palette follows the **live app**, not the shared DS token file — `#001115` surface, `#19282C` cards, `#92BE11` green as the single accent and the single match colour, dark `#001115` text on green. Type is IBM Plex Sans, max weight 700.
- Real partners, real logos only: VMware by Broadcom, secunet, Hyground, Thales, Flagsmith, Google.
- The Partners overview and Partner detail screens are never restructured — additive state only.
- Prototypes are design artefacts, not production code — they mock data and interactions to make the intended behaviour unambiguous. Where a flow and the current build disagree, the flow is the request.

## Updating

Replace the relevant `index.html` and commit. GitHub Pages redeploys automatically.
