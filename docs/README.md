# Homepage maintenance

This directory is the static GitHub Pages source for the project homepage.

- `index.html` — page content, metadata, and a small inline script (scrollspy, figure lightbox, BibTeX copy). No build step, no external dependencies.
- `styles.css` — all styling. Typography uses system font stacks only, so the page loads without any font request.
- `.nojekyll` — tells GitHub Pages to publish the files without Jekyll processing.

## Figures

Every PNG in `assets/` is regenerated from the survey's own source figures, so the homepage and the manuscript never diverge:

| Asset | Source |
| --- | --- |
| `knowledge-lifecycle.png` | `knowledge/figures/main.pdf` |
| `knowledge-acquisition.png` | `knowledge/figures/knowledge_acquisition.pdf` |
| `representation-parametric.png` | `knowledge/figures/knowledge-representation-parametric-storage.pdf` |
| `representation-activation.png` | `knowledge/figures/knowledge-representation-in-activation-space_cropped.pdf` |
| `knowledge-utilization.png` | `knowledge/figures/utilization.pdf` |
| `knowledge-evolution.png` | `knowledge/figures/knowledge_evolution.pdf` |
| `knowledge-transfer.png` | `knowledge/figures/transfer.pdf` |
| `knowledge-evaluation.png` | `knowledge/figures/evaluation.pdf` |
| `taxonomy-overview.png` | `assets/knowledge-taxonomy.pdf`, the vector export of `sections/taxonomy.tex` |

Regeneration recipe: render at 300 dpi with Ghostscript (`-sDEVICE=pngalpha -r300 -dTextAlphaBits=4 -dGraphicsAlphaBits=4`), flatten onto white, trim the surrounding whitespace with a small padding, resize to 2000 px wide (1700 px for the taxonomy), then quantize to a 256-colour palette (64 for the taxonomy) to keep the files small.

The `width` and `height` attributes in `index.html` must match the real pixel dimensions of each file, otherwise the reserved space is wrong and the layout shifts while images load.

## Other files

- `assets/knowledge-taxonomy.pdf` — vector export of the complete taxonomy, linked from the taxonomy section.
- `downloads/knowledge-mechanisms-across-llm-lifecycle.pdf` — the downloadable manuscript.

Author names follow the manuscript's `Author` section; the BibTeX entry follows `knowledge/cite` and the canonical OSF DOI.

## Preview

```bash
python3 -m http.server 8000 --directory docs
```

Then open <http://localhost:8000/>.

GitHub Pages publishes from branch `xh`, folder `/docs`. When the manuscript or a source figure changes, replace the corresponding committed artifact without changing its public filename so existing links keep working.
