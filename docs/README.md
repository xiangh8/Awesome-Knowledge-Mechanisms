# Homepage maintenance

This directory is the static GitHub Pages source for the project homepage.

- `index.html` contains the page content and metadata.
- `styles.css` contains all responsive styling.
- `assets/knowledge-lifecycle.png` is rendered from the survey's `figures/main.pdf` source figure.
- `downloads/knowledge-mechanisms-across-llm-lifecycle.pdf` is the downloadable survey manuscript.
- `.nojekyll` tells GitHub Pages to publish the files without Jekyll processing.

Preview locally from the repository root with `python3 -m http.server 8000 --directory docs`, then open `http://localhost:8000/`.

GitHub Pages should publish from branch `xh` and folder `/docs`. When the manuscript or lifecycle figure changes, replace the corresponding committed artifact without changing its public filename so existing links continue to work.
