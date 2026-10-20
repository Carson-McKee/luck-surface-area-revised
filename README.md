# Luck Surface Area_Revised

**ARC Fund Research · [Post-Industrial School](https://carson-mckee.github.io/post-industrial-school/)**
Carson McKee ([ORCID 0009-0004-8818-7937](https://orcid.org/0009-0004-8818-7937)) · Visual identity by [Joy Nneji](https://www.linkedin.com/in/joynneji/) · Version v.01.01 · October 2026

**Read the visual essay:** https://carson-mckee.github.io/luck-surface-area-revised/

## Abstract

Jason Roberts' 2010 formula for luck, L = D × T (luck equals doing times telling), treats telling as a quantity: the more people you tell, the more surface luck has to land on. This research argues that telling is also an environment, and that environments are not equal.

An exploratory survey of eight founders found an inversion. The environment where they reported spending the most time, social platforms (9.4 hours a month), returned the least perceived serendipity (2.62 out of 5). Structured events took less than half the time (4.4 hours) and returned the most (3.62). Read against prior research on open-plan offices, weak ties and structural holes, the pattern points away from proximity as the mechanism and toward the design of the environment itself.

The essay proposes a revised formula, **L = D × T × e**, where *e* is the environment telling happens in, and three tests for *e*: **constraint** (is it bounded?), **frame** (is there a shared task?) and **friction** (do encounters facilitate a commitment, a synchronous moment?).

## How to cite

McKee, C. (2026). *Luck Surface Area_Revised* (Version v.01.01) [Visual essay]. Post-Industrial School. https://doi.org/10.5281/zenodo.23479711

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23479711.svg)](https://doi.org/10.5281/zenodo.23479711)

Archived on Zenodo. GitHub's "Cite this repository" button uses [`CITATION.cff`](CITATION.cff).

## Method and limits

The primary data comes from an exploratory remote survey of eight founders in Vancouver's startup ecosystem, run in April 2026 with ethics approval. Each reported the hours per month they spend in four environment types and rated the serendipity each returns on a scale of 1 to 5. Figures are founder-reported perceptions, not measured outcomes, and the sample is not statistically representative. Full method in [`METHODS.md`](METHODS.md). Aggregate figures in [`data/environments.csv`](data/environments.csv).

The essay keeps its claims in three layers (section 08, "Summary"):

- **Supported:** proximity alone is not the mechanism. Prior research with far larger samples points to engineered collision instead.
- **Inferred:** founders have a revealed preference, not a stated one. Nobody said they preferred digital. They were just there.
- **Argued:** constraint, frame and friction are the criteria, and they are portable. Rooms have them by accident. Digital spaces can have them by intent.

## Prior research

Full bibliography in [`references.bib`](references.bib).


- Roberts, J. (2010). [Increasing your luck surface area](https://www.codusoperandi.com/posts/increasing-your-luck-surface-area). *Codus Operandi*.
- Granovetter, M. (1973). The strength of weak ties. *American Journal of Sociology*, 78(6), 1360–1380.
- Burt, R. S. (2004). Structural holes and good ideas. *American Journal of Sociology*, 110(2), 349–399.
- Bernstein, E. S. & Turban, S. (2018). The impact of the "open" workspace on human collaboration. *Philosophical Transactions of the Royal Society B*, 373(1753).
- Rajkumar, K., Saint-Jacques, G., Bojinov, I., Brynjolfsson, E. & Aral, S. (2022). A causal test of the strength of weak ties. *Science*, 377(6612), 1304–1310.

## Funding

Supported by the Langara College ARC Research Fund.

## Versions

See [`CHANGELOG.md`](CHANGELOG.md).

## Licence

Text and data: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Fonts, photographs and the visual identity are covered separately. See [`LICENSE.md`](LICENSE.md).

---

## Site files

All site files sit at the top level of the repo:

```
index.html      the full essay: markup, styles and scripts in one file
*.woff          fonts: TeX Gyre Heros (GUST Font License), Roboto Mono (Apache 2.0)
corridor.jpg    hero and fig. 03
crowd.jpg       fig. 01
contact.jpg     fig. 02
data/           aggregate survey figures
METHODS.md      research design and limits
references.bib  bibliography (BibTeX)
CHANGELOG.md    version history
```

No build step. Published with GitHub Pages from the `main` branch.

### Editing notes

- Colour, type and spacing tokens are CSS variables at the top of the `<style>` block (`:root`).
- The two fold panels (sections 03 and 04, three tabs each) are built in the `<script>` block at the bottom, under `const folds`.
- Section markers: `01` assumption, `02` vacancy, `03` measurement, `04` formula correction, `05` what it returns, `06` revision, `07` framework, `08` honesty layer, then the close.
- To swap a photo, replace the .jpg with a file of the same name.
- v.01.01 is the published version. Changes after publication are logged in CHANGELOG.md.
