# Luck Surface Area_Revised

A visual essay. Research output of the [Post-Industrial School](https://carson-mckee.github.io/post-industrial-school/).

By Carson McKee · Visual identity by [Joy Nneji](https://www.behance.net/joynneji)

## Structure

All files sit at the top level of the repo:

```
index.html      the full essay: markup, styles and scripts in one file
*.woff          fonts: TeX Gyre Heros (GUST Font License), Roboto Mono (Apache 2.0)
crowd.jpg       fig. 01
contact.jpg     fig. 02
corridor.jpg    fig. 03
```

No build step. Published with GitHub Pages from the `main` branch.

## Editing notes

- Colour, type and spacing tokens are CSS variables at the top of the `<style>` block (`:root`).
- The two fold panels (sections 03 and 04, three tabs each) are built in the `<script>` block at the bottom, under `const folds`.
- Section markers: `01` assumption, `02` vacancy, `03` measurement, `04` formula correction, `05` what it returns, `06` revision, `07` framework, `08` honesty layer, then the close.
- To swap a photo, replace the .jpg with a file of the same name.
- Copy is final unless flagged. Design changes are open.
