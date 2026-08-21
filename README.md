# Matchmaking

Sponsor Matchmaking for the conference app — prototype and flow deliverables.

This is the **conference app**, not Workbench.

## Structure

```
proto/   prototype builds (HTML, self-contained)
flow/    flow spec, state model, screen-by-screen flow deliverables
```

## Conventions

- Deliverable files are named `<What it is> (<version>) - Matchmaking.html`
- Only the current version of each deliverable lives at the top of its folder;
  superseded builds go into `old-versions/`.
- Palette follows the **live app**, not the shared DS token file:
  `#001115` surface, `#19282C` cards, `#92BE11` green as the single accent and
  the single match colour, dark `#001115` text on green. Type is IBM Plex Sans,
  max weight 700.
- Attendee-facing copy follows the app: `Ausstellier`, `Sponsoren`, `Kontakt teilen`.
- `Kontakt teilen` is the one control — Matchmaking changes its state, never adds
  a second button beside it.
- Real partners, real logos only: VMware by Broadcom, secunet, Hyground, Thales,
  Flagsmith, Google.
