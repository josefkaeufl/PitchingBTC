# Bitcoin Pitch — Modular Slides

Standalone HTML slides about Bitcoin and the money system. Mix and match them into
your own talk, share single slides on X, or present the whole deck.

🔗 [@PitchingBTC](https://x.com/PitchingBTC)

## The concept

**One idea = one slide = one file.** Each slide is a complete, self-contained HTML
file with no dependencies. Slides are freely combinable, individually shareable,
and all share the same design.

## What's what

```
PitchingBTC/
├── present.html      FIXED     The player — don't touch, just open it.
├── cover.html        FIXED     Cover slide (optional, remove its line in slides.js if you don't want it)
├── slides.js         YOURS     The running order of your talk — the one file you edit.
└── slides/           PICK      All topic slides. Choose the ones you want.
    ├── money-system.html
    ├── m2-chart.html
    ├── bitcoin-game-theory.html
    ├── value.html
    ├── bitcoin-asset-and-network.html
    ├── gold-and-money.html
    ├── criminal-use.html
    └── energy-myth.html
```

| Where | Role | What you do |
|-------|------|-------------|
| `present.html` | Player (fixed) | Open it to present. |
| `cover.html` | Cover (fixed) | Keep it as opener or drop it. |
| `slides.js` | Your configuration | Choose, order and title the slides of your talk. |
| `slides/` | Slide library | Pick from it, or add your own slide here. |

## Use it

- **Show one slide:** open a file from `slides/` (double-click), press `F11` for fullscreen.
- **Present a deck:** open `present.html`. Move with `→` / `←` / Space / the on-screen
  arrows, press `F` for fullscreen.

No installation, no server — just open the files in a browser.

## Build your own talk

Open `slides.js` and edit the lines between the back-ticks — one slide per line,
`path | Title`:

```
cover.html                  | Cover
slides/money-system.html    | The Money System
slides/value.html           | What Gives Things Value
slides/energy-myth.html     | Energy, Well Spent
```

- **Select:** keep only the lines for the slides you want (or comment out with `#`).
- **Reorder:** move lines.
- **Add:** write a new line pointing to a file in `slides/`.

Save, reload `present.html` — done.

## Speaker notes

Slides with notes show a small **“Speaker Guide”** button (bottom right), off by
default. Click it or press `N` to toggle. Add `#notes` to a slide's URL to open it
with notes already showing. Inside the player the button stays hidden.

## Add your own slide

Copy an existing file from `slides/`, edit the content (keep the header/footer and
the `:root` block so the design matches), save it in `slides/`, then add a line
`slides/your-file.html | Title` to `slides.js`.

## Share on X

Screenshot the clean 16:9 slide — the speaker notes are hidden by default.

---

*Hobby project. Pure, dependency-free HTML. Data figures (e.g. M2) are rounded
approximations from official sources such as the Federal Reserve / FRED.*
