# Canvas Arcade

Two small browser games built from scratch with vanilla JavaScript and the HTML5 Canvas — no frameworks, no build step, no dependencies. Open a file and play.

**▶ Play live:** https://&lt;your-username&gt;.github.io/canvas-arcade/

---

## The games

**Snake** — the classic, reimagined: a tapering body, direction-aware eyes that look where the snake is heading, swipe + keyboard controls, and a best score saved to your browser.

**Alien Invaders** — a relaxed take on the fixed-shooter. Drag to move, hold to fire (the fire rate ramps up the longer you hold), escalating waves, a light/dark toggle, and fully synthesized sound.

## Built with

- Vanilla JavaScript (ES6) — zero libraries, zero build tooling
- HTML5 Canvas 2D for all rendering, animation, and particle effects
- Web Audio API for procedurally generated sound (no audio files shipped)
- A delta-timed game loop, full keyboard **and** touch/swipe input, and a responsive layout that adapts to any screen size
- Defensive game logic: collision detection, prevented 180° self-reversals, and graceful fallback when browser storage is unavailable
- Typography via Google Fonts (Geist, Geist Mono, Source Serif 4, Fraunces), all under the SIL Open Font License

## Run locally

No install and no server required — just clone and open either HTML file in a browser:

```bash
git clone https://github.com/<your-username>/canvas-arcade.git
cd canvas-arcade
open index.html      # or just double-click the file
```

## A note on design

The visual style — warm coral on charcoal, with a four-point sparkle motif — is a deliberate homage to a design language I admire. This is a personal, non-commercial project and is **not affiliated with, endorsed by, or connected to** any company.

## License

MIT © 2026 &lt;DLazzzar&gt; — see [LICENSE](LICENSE). Use the code however you like; a credit is appreciated but not required.
