# Hero Animation — Interactive Particle System

A cursor-interactive particle hero animation with [Tweakpane](https://cocopon.github.io/tweakpane/) controls. Tune the look in the browser, then use **Copy Code** to export HTML/CSS/JS you can paste into any site (or have an LLM integrate it).

## Run locally

**Important:** Run the server from inside the `hero-animation` folder so the root URL serves `index.html`.

```bash
cd /path/to/hero-animation
python3 -m http.server 8080
```

Then open: **http://localhost:8080**

Or with Node:

```bash
npx serve .
```

Then open the URL shown (e.g. http://localhost:3000).

## Features

- **Cursor interaction** — Particles react to the mouse (repel, attract, or orbit).
- **Tweakpane controls** — Grid density, particle shape/color, interaction type/radius, grid overlay, connections, clustering, background, etc.
- **Copy Code** — Exports a self-contained snippet (HTML + script + CSS) for your portfolio or any page.

## Project structure

```
hero-animation/
├── index.html   # Single-file app (canvas + Tweakpane)
├── README.md
└── .gitignore
```

No build step; open via a local server as above.

## License

MIT (or your choice).
