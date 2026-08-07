 🕉️ Japa Mala — Digital Prayer Bead Counter

A peaceful, fully offline **Japa Mala (mantra counter)** that runs entirely in the browser. Chant your mantra and count it with a tap, a click, or by holding a key — a realistic 108‑bead SVG mala rotates and glows with every count, while temple bells, a conch, and a layered "Ommmm" chant are synthesized live, so there's not a single external audio or image file to load.

Built with plain **HTML, CSS, and vanilla JavaScript** — no frameworks, no build step, no dependencies. Open the file and start chanting.

> "This year, or this life, whichever comes first." — traditional mala wisdom

---

✨ Features

- **Realistic 108‑bead mala** — hand‑drawn SVG wheel with a meru (guru) bead and tassel, generated at runtime. The active bead glows, and the wheel gently rotates as you count.
- **Multiple ways to count** — tap the mala, tap the "chant plate," or hold your chosen keyboard key. Long‑press auto‑repeats smoothly for continuous counting.
- **Configurable counting key** — bind counting to any key: Space, Enter, a letter, or anything else.
- **Custom targets** — quick presets (27 / 54 / 108 / 216 / 1008) or any custom number.
- **Synthesized sacred sounds** — soft bead clicks, a temple bell, a conch shell, and a layered, breathing **"Ommmm" chant**, all generated live with the Web Audio API (no audio files required).
- **Completion ritual** — on reaching your target: golden glow, falling flower petals, temple bell + conch, optional vibration on mobile, and a gentle "Japa Completed · Om Shanti" screen.
- **Seven themes** — Temple Gold, Himalayan Morning, Dark Meditation, Diwali, Wooden Mala, Minimal White, and Sacred Night.
- **Live statistics** — current count, remaining, completed rounds, today's total, overall total, progress %, session time, average speed, and total key presses.
- **Autosave** — your count, target, theme, key binding, and stats persist automatically via `localStorage`. Close the tab, come back later, and pick up right where you left off.
- **First‑time guide** — a short "How to Use" overlay for new visitors (dismissible, won't show again once closed).
- **Keyboard shortcuts** — `R` reset · `S` settings · `M` mute · `F` fullscreen · `P` pause · `H` help · `Esc` close.
- **Accessible by design** — reduced‑motion mode, high‑contrast mode, adjustable font size, keyboard navigation, and ARIA live regions for the counter.
- **Fully responsive** — comfortable on desktop, tablet, and mobile, with large touch targets.

---

🚀 Getting Started

No installation, no build tools, no server required.

1. **Download** `japa-mala.html`.
2. **Open it** in any modern browser (Chrome, Edge, Firefox, Safari).
3. Start chanting. 🙏

Or clone the repo and open the file directly:

```bash
git clone https://github.com/<your-username>/japa-mala.git
cd japa-mala
open japa-mala.html   # macOS
# or just double-click the file on Windows/Linux
```

You can also serve it locally if you prefer:

```bash
npx serve .
# then visit the printed local URL
```

---

## 🧘 How to Use

1. Open **Settings** (⚙) and choose your counting key, or keep the default `SPACE`.
2. Set your **target** — 108 is traditional, or pick your own from the presets or a custom number.
3. Begin chanting your mantra quietly, at your own pace.
4. **Tap the mala**, tap the chant plate, or **press/hold** your key to count.
5. Watch each bead light up as the mala turns with you.
6. When your round completes, a temple bell and conch will sound, and you can start a new round or continue freely.

---
 ⌨️ Keyboard Shortcuts

| Key   | Action              |
|-------|---------------------|
| `R`   | Reset current count |
| `S`   | Open/close Settings |
| `M`   | Mute / unmute sound |
| `F`   | Toggle fullscreen   |
| `P`   | Pause / resume counting |
| `H`   | Open the help guide |
| `Esc` | Close any open panel |

*(Your chosen counting key takes priority — if it collides with a shortcut letter, counting wins.)*

---

🎨 Themes

| Theme | Mood |
|---|---|
| Temple Gold | Warm saffron and gold, wooden beads |
| Himalayan Morning | Cool blues and soft dawn light |
| Dark Meditation | Deep indigo, minimal and quiet |
| Diwali | Festive reds, oranges, and gold glow |
| Wooden Mala | Earthy browns, matte and grounded |
| Minimal White | Bright, clean, distraction‑free |
| Sacred Night | Starlit navy with a soft golden moon |

Switch instantly from **Settings → Look**.

---

 🔊 Sound

All sound effects and ambient music are **synthesized in real time** with the Web Audio API — there are no `.mp3`/`.wav` files in this project, which keeps it lightweight and fully offline‑capable.

- **Bead click** — a soft plucked tone on every count.
- **Temple bell** — layered sine partials with a long, natural decay.
- **Conch shell** — a swelling filtered tone at round completion.
- **Ambient music** (optional, toggle in Settings → Sound):
  - **Om Chant** — layered harmonics with a slow "O → M" formant sweep and a breathing swell, like a chanted "Ommmm."
  - **Meditation Chime** — soft, randomized bell tones.
  - **Himalayan Wind** — filtered noise for a gentle ambient backdrop.

Volume and mute are adjustable at any time.

---

 🛠️ Tech Stack

- **HTML5** — semantic, accessible markup
- **CSS3** — custom properties (design tokens) for instant theme switching, no CSS frameworks
- **Vanilla JavaScript (ES6+)** — no libraries, no build step
- **SVG** — the mala bead wheel is drawn and animated at runtime
- **Web Audio API** — all sound effects and music synthesized on the fly
- **Canvas** — subtle floating‑particle background
- **`localStorage`** — autosave for progress, settings, and statistics

---

 🌐 Browser Support

Works in current versions of Chrome, Edge, Firefox, and Safari, on desktop, Android, and iOS. Sound requires one user interaction to start, per standard browser autoplay policy.

---

♿ Accessibility

- Reduced‑motion mode (also respects `prefers-reduced-motion`)
- High‑contrast mode
- Adjustable counter font size
- Full keyboard navigation and focus states
- `aria-live` region on the counter for screen readers

---

 🗺️ Roadmap / Ideas

- [ ] Full offline PWA packaging (manifest + service worker, installable app)
- [ ] Additional languages (Bengali, Sanskrit) — the `I18N` object is already structured for easy additions
- [ ] Optional user‑supplied deity/background artwork
- [ ] Cloud sync across devices

Contributions and suggestions are welcome — feel free to open an issue or a pull request.

---

 🤝 Contributing

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-idea`
3. Make your changes to `japa-mala.html`
4. Open a pull request describing what you changed and why

Since this is a single self‑contained file, please keep the "no frameworks, no build step" spirit intact when contributing.

---

📜 License

MIT — free to use, modify, and share. If this brings a little peace to your practice, consider starring the repo. 🙏

---

*Om Shanti Shanti Shanti.*
