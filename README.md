# Happy 5 Months 🏹💗🌳

A 5-month anniversary card that plays like a little film in your browser.

You pull back a bow, shoot an arrow into a heart, and the heart bursts and grows
into a tree made of hundreds of tiny hearts.

There is no video file. It is all drawn live by the browser.

### 👉 [See it live](https://YOUR-USERNAME.github.io/five-months-tree/)

![Preview](media/preview.jpg)

▶️ [media/demo-silent.mp4](media/demo-silent.mp4) — a short clip of the whole thing (no sound).

---

## Run it on your computer

You need [Node.js](https://nodejs.org/) version 20 or newer. Then copy these
commands one by one:

```bash
git clone https://github.com/YOUR-USERNAME/five-months-tree.git
cd five-months-tree
npm install
npm run dev
```

The last command prints a link like `http://localhost:5173`.
Open it in your browser. That's it.

To stop it, press `Ctrl + C` in the terminal.

## All the commands

| Command | What it does |
| --- | --- |
| `npm install` | Downloads what the project needs. Run this once, at the start. |
| `npm run dev` | Runs the site on your computer. Every file you save updates the page instantly. |
| `npm run build` | Makes the finished version inside a `dist/` folder. |
| `npm run preview` | Opens that finished version so you can check it before putting it online. |

## How to play it

- **Mouse or finger** — press on the bow, drag down to pull the string, then let go.
- **Keyboard** — press `Tab` until the bow is selected, then press `Enter` or `Space`.
- **Watch again** — an "Again" button shows up at the end.
- If your computer is set to *reduce motion*, the film is skipped and you go
  straight to the finished tree.

## What happens, in order

1. **The bow** — a heart beats gently and a small bow waits under it. Pull the
   string back and let go.
2. **The shot** — the string twangs, the arrow flies up, hits the heart, and the
   heart bursts into a flood of rose colour.
3. **The wish** — *Happy 5 Months* rises up out of that colour one letter at a
   time, a hand-drawn line sweeps underneath, and black film bars slide in.
4. **The tree** — a gold light blooms, a bare tree grows and fills a
   heart-shaped top with hundreds of lit blossoms, petals drift down, and the
   wish writes itself on again in flowing script.

## Change the words or colours

| What you want to change | Open this file |
| --- | --- |
| The text on screen | `index.html` |
| Colours, fonts, sizes | `anniversary.css` |
| Timing and the animation | `anniversary.js` |

Save the file while `npm run dev` is running and the page updates by itself.

## Put it online

It publishes itself to GitHub Pages. Just push your changes:

```bash
git add .
git commit -m "my changes"
git push
```

GitHub then runs `npm run build` for you and puts the finished site online. You
can watch it happen in the **Actions** tab.

⚠️ One setting has to be right. In your repo go to **Settings → Pages** and set
**Source** to **GitHub Actions** — *not* "Deploy from a branch". If you serve the
raw files instead of the built ones, the page opens blank.

## Built with

Plain JavaScript · [GSAP](https://gsap.com/) · Canvas 2D · [Vite](https://vitejs.dev/) ·
Google Fonts (Great Vibes, Fraunces, Cormorant Garamond)

No framework. One `<canvas>` for the tree, and GSAP for everything else.

## License

[MIT](LICENSE) © Hasib — free to use, copy and change.

_The demo clip has no sound. The music in the published Short is a third-party
track and is not included here._
