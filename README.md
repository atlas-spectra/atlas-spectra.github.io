# Atlas Spectra Pages shell

This repository exists only to publish the Atlas Spectra organization site at <https://atlas-spectra.github.io/>.

The canonical source, scientific corpus, issues, and development history live in [`atlas-spectra/atlas-spectra`](https://github.com/atlas-spectra/atlas-spectra).

The deployment workflow checks out an explicit source ref from the canonical repository, re-runs the scientific validation suite and Astro build, and deploys the resulting `dist/` artifact to GitHub Pages.

Do not add product source or scientific data here.
