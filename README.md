# Ajit Prasad — Digital Product Designer Portfolio

An autonomous cursor-swarm portfolio website replicating the cursor-style interactive experience. Live cursors autonomously lay out wireframes, type content, pick brand colors, and construct the interface in real time.

## 🚀 Live Interactions & Controls

- **`Space`**: Start or pause the autonomous swarm builder
- **`R`**: Replay the construction from scratch
- **`A`**: Auto-glide tour through all sections
- **`C`**: Cycle brand accent color palette (Yellow, Red, Mint, Violet)
- **`1` / `2` / `3`**: Speed controls (1x, 2x, 0.5x)
- **`M`**: Mute or enable synthetic Web Audio effects
- **`H`**: Hide cursor tools / clean view mode

## 🛠 Project Structure

- `index.html` — Self-contained production build with embedded fonts, CSS styling, interactive canvas, Web Audio engine, and autonomous swarm agent orchestration.
- `Ajit_Prasad_Resume.pdf` / `resume.pdf` — Direct downloadable resume asset.
- `assets/images/` — High-resolution portrait photographs and visual assets.

## 💻 Local Preview

Run any static HTTP server:
```bash
python3 -m http.server 8000
# or
npx serve .
```
Then open `http://localhost:8000/`.

To inspect the fully assembled view directly (reduced-motion / static preview):
`http://localhost:8000/?built`
