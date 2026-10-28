# Food Distribution Web Viewer

Browser simulation viewer for [`food-distribution-gym`](https://github.com/ui-iros/food-distribution-gym). It mirrors the Python pygame viewer with a live/replay launcher, configurable seed/FPS/max steps, city network visualization, commodity selection, state details, pause/step/reset controls, zoom, and help overlay.

The web viewer is a lightweight visual simulation. The canonical Gymnasium dynamics remain in the Python package and are not replaced by this static viewer.

## Run locally

Open `index.html` directly, or serve the folder:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

## GitHub Pages

The repository is configured to deploy automatically from the `main` branch using GitHub Actions.

## License

MIT, matching the Python package.
