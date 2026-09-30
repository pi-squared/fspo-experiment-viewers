# FSPO extraction viewers

Public browser viewers for the LangExtract and DocETL experiment on FSPO cases **2020-0256, 2026-0009 and 2022-0040**.

- [Open the site](https://pi-squared.github.io/fspo-experiment-viewers/)
- [LangExtract viewer](https://pi-squared.github.io/fspo-experiment-viewers/langextract-luna-low.html)
- [DocETL / DocWrangler viewer](https://pi-squared.github.io/fspo-experiment-viewers/docetl-luna-low.html)

Each HTML contains all three cases, the relevant native viewer, source text, native and canonical results downloads, promoted schema v2, evidence checks and licence notices. They also work offline when saved locally.

The run used **gpt-6-luna with low reasoning**, with one call per case per framework and no answer reruns. The results are experimental and not human reviewed. Source preparation warnings and quotation/alignment limitations remain visible in each viewer's **Method and checks** panel. LangExtract's unaligned record remains in its downloads even though it has no native source highlight.

The two HTML files are byte-identical to the verified 29 September 2026 experiment artifacts. No model calls were made for this publication. See `SHA256SUMS` for artifact integrity.

GitHub Pages serves the root of the `publish/viewers` branch. `.nojekyll` preserves the self-contained HTML files without a Jekyll build.

Third-party software notices are embedded in the HTML viewers. This repository does not assert ownership of the FSPO decision text.
