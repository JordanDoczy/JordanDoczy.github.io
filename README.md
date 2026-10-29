# Jordan Doczy — Portfolio

An ultra-minimalist, single-file portfolio site built with pure HTML and CSS. No build tools, no frameworks, zero dependencies.

## What's Included

- [index.html](file:///Users/jordandoczy/Developer/Antigravity/index.html): Completely self-contained webpage.
  - **About & Leadership**: Summary of 18+ years across native mobile development, systems architecture, and digital operations.
  - **Featured Projects**:
    - **Tetra Fire**: SpriteKit arcade puzzle game with particle physics.
    - **ooVoo**: Scaled multi-party simultaneous video chat platform.
    - **instanote**: Photo memory app with Core Data and MapKit.
    - **Match Pop!**: Interactive vector animation card game.
    - **Graph**: Mathematical 2D plotting prototype with `UIBezierPath`.
  - **Technical Skills**: Mobile SDKs, languages, architecture patterns, and engineering management.
  - **Experience & Education**: Timeline of roles (Ascend Innovations, Krush Technologies, Odopod, Crispin Porter + Bogusky, 180 Amsterdam) and university credentials.
  - **Automatic Dark Mode**: Respects system appearance (`prefers-color-scheme`) without external scripts.
  - **Print / PDF Friendly**: Clean typography and layouts for print and resume viewing.
- [Jordan.Doczy.Resume.pdf](file:///Users/jordandoczy/Developer/Antigravity/Jordan.Doczy.Resume.pdf): PDF resume linked directly from the header and footer.

## Preview Locally

Open directly in your default browser:

```bash
open index.html
```

Or run a local static server:

```bash
python3 -m http.server 8000
```
Then visit [http://localhost:8000](http://localhost:8000).

## Deployment

Because this is a pure static site with an `index.html` file at the root:
- **GitHub Pages**: Initialize git (`git init && git add . && git commit -m "Init"`), push to GitHub, and turn on GitHub Pages in the repo settings.
- **Vercel / Cloudflare Pages / Netlify**: Connect the repository or drag-and-drop the directory; it will serve immediately with zero build commands.
