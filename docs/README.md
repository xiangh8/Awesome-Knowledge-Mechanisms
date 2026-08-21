# Homepage maintenance

This directory is the static GitHub Pages source for the project homepage.

- `index.html` contains the page content and metadata.
- `styles.css` contains all responsive styling.
- `assets/knowledge-lifecycle.png` is rendered from the survey's `figures/main.pdf` source figure.
- `assets/knowledge-taxonomy.pdf` is the vector export of the survey's complete lifecycle taxonomy, which is defined inline in `sections/taxonomy.tex`; `assets/taxonomy-overview.png` is its web rendering.
- The remaining PNG files in `assets/` are web renderings of the section-level taxonomy PDFs maintained in the survey's `figures/` directory.
- `downloads/knowledge-mechanisms-across-llm-lifecycle.pdf` is the downloadable survey manuscript.
- `.nojekyll` tells GitHub Pages to publish the files without Jekyll processing.

Author names follow the manuscript's `Author` section. Citation metadata follows `knowledge/cite` and the canonical OSF DOI.

Preview locally from the repository root with `python3 -m http.server 8000 --directory docs`, then open `http://localhost:8000/`.

GitHub Pages should publish from branch `xh` and folder `/docs`. When the manuscript or a source figure changes, replace the corresponding committed artifact without changing its public filename so existing links continue to work.
