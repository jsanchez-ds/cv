# CV — Jonathan Sánchez Pesantes

[![Download CV (PDF)](https://img.shields.io/badge/Download_CV-PDF-d14836?logo=adobe-acrobat-reader&logoColor=white)](./cv.pdf)

Industrial Engineer (Universidad de Chile, *distinción máxima*) currently working at **ClaroVTR** as Efficiencies Engineer, building end-to-end forecasting systems for enterprise clients (XGBoost / LightGBM / Prophet ensembles, ~$30M CLP/month identified savings).

📄 **[cv.pdf](./cv.pdf)** — current PDF version

---

## About this repo

This repo holds the LaTeX sources of my CV plus the latest compiled PDF. The compiled PDF is what you want if you only need to read or download the CV.

## Versions

| File | Style | Status |
|---|---|---|
| `cv.pdf` | Harvard-style template, single column | ✅ Compiled, current version |
| `latex/cv_harvard.tex` | Source for the PDF above | ✅ Ready to compile |
| `latex/cv_modern.tex` | Modern style with **bold-prefixed bullets** and 2-column skills | 📝 Source only — easier to skim for tech recruiters |

The `cv_modern.tex` version is structured so each bullet starts with a bold tag (e.g. **Modelamiento Predictivo:**, **Impacto de Negocio:**, **Feature Engineering:**) which makes the CV easier to skim by tech recruiters in the typical 30-second scan.

## How to compile

Either version compiles cleanly in **Overleaf** (recommended) or with a local TeX Live install:

```bash
pdflatex latex/cv_harvard.tex
# or
pdflatex latex/cv_modern.tex
```

## Contact

- 📧 jonathan.sanchez.ep@gmail.com
- 💼 [linkedin.com/in/jonasanchez](https://www.linkedin.com/in/jonasanchez)
- 🐙 [github.com/Jonathan742001](https://github.com/Jonathan742001)
