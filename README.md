# Bitcoin Pitch — Modular Slides

Standalone HTML slides about Bitcoin and the money system. Mix and match them into
your own talk, share single slides on X, or present the whole deck.

🔗 [@PitchingBTC](https://x.com/PitchingBTC)

## The concept

**One idea = one slide = one file.** Each slide is a complete, self-contained HTML
file with no dependencies. Slides are freely combinable, individually shareable,
and all share the same design. The running order lives in one place: `slides.js`.

## Files

| File | Purpose |
|------|---------|
| `present.html` | The player — shows the deck and steps through it. |
| `slides.js` | The order — edit this to change your talk. |
| `bitcoin-00-cover.html` | Cover slide |
| `bitcoin-01-money-system.html` | “Money is created from nothing” (with speaker notes) |
| `bitcoin-02-m2-chart.html` | M2 chart since 1970 + the “$1,000” calculation (with speaker notes) |

## Use it

- **Show one slide:** double-click the file, press `F11` for fullscreen. That's it.
- **Present the deck:** open `present.html`. Move with `→` / `←` / Space / the on-screen
  arrows, press `F` for fullscreen.

No installation, no server — just open the files in a browser.

## Change the order

Open `slides.js` and edit the lines between the back-ticks — one slide per line,
`filename.html | Title`:

```
bitcoin-00-cover.html        | Cover
bitcoin-01-money-system.html | The Money System
bitcoin-02-m2-chart.html     | The Cost of Infinite Money
```

Reorder by moving lines, remove a slide by deleting its line, add one by writing a
new line. Save, reload — done.

## Speaker notes

Slides with notes show a small **“Speaker Guide”** button (bottom right), off by
default. Click it or press `N` to toggle. Add `#notes` to a slide's URL to open it
with notes already showing. Inside the player the button stays hidden.

## Add your own slide

Copy an existing `bitcoin-XX-*.html`, edit the content (keep the header/footer and
the `:root` block so the design matches), then add its filename to `slides.js`.

## Share on X

Screenshot the clean 16:9 slide — the speaker notes are hidden by default.

---

*Hobby project. Pure, dependency-free HTML. Data figures (e.g. M2) are rounded
approximations from official sources such as the Federal Reserve / FRED.*
