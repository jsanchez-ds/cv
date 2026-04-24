# CV — Jonathan Sánchez Pesantes

[![Download CV (PDF)](https://img.shields.io/badge/Download_CV-PDF-d14836?logo=adobe-acrobat-reader&logoColor=white)](./cv.pdf)

**Senior Data Scientist · ML Engineer · LLM / AI Engineer** · Industrial Engineer (Universidad de Chile, *distinción máxima*) currently at **ClaroVTR** as Efficiencies Engineer — building end-to-end forecasting systems (XGBoost / LightGBM / Prophet ensembles, ~$30M CLP/month identified savings) and a public portfolio trilogy covering classical ML, LLM/RAG and real-time agentic systems.

📄 **[cv.pdf](./cv.pdf)** — current PDF version

---

## About this repo

This repo holds the LaTeX sources of my CV plus the latest compiled PDF. The compiled PDF is what you want if you only need to read or download the CV.

## Versions

| File | Style | Status |
|---|---|---|
| `cv.pdf` | Harvard-style template — clean, well-spaced, single column | ✅ Compiled, **current version** |
| `latex/cv_harvard.tex` | Source for the PDF above — **canonical** | ✅ Ready to compile |
| `latex/cv_modern.tex` | Variant with bold-prefixed bullets and 2-column skills | 📝 Alternate source — same content, different layout |

Both sources are kept in sync: same summary, same experience bullets, same flagship projects, same skills section. `cv_harvard.tex` is what `cv.pdf` is built from.

## How to compile

Compiles cleanly in **Overleaf** (recommended) or with a local TeX Live install:

```bash
pdflatex latex/cv_harvard.tex     # → cv.pdf
# or
pdflatex latex/cv_modern.tex      # → cv_modern.pdf
```

## Contact

- 📧 jonathan.sanchez.ep@gmail.com
- 💼 [linkedin.com/in/jonasanchez](https://www.linkedin.com/in/jonasanchez)
- 🐙 [github.com/jsanchez-ds](https://github.com/jsanchez-ds)

---

## Portfolio

See my data science projects at [github.com/jsanchez-ds](https://github.com/jsanchez-ds):

### 🏆 Flagship trilogy (2026)

- [**energy-forecasting-databricks**](https://github.com/jsanchez-ds/energy-forecasting-databricks) ⚡ Classical ML on Databricks Unity Catalog — LightGBM MAPE **1.81%**, LSTM, Isolation Forest, SHAP, Medallion
- [**energyscholar-rag**](https://github.com/jsanchez-ds/energyscholar-rag) 📚 Production-grade RAG over arXiv energy papers — provider-agnostic LLM layer, hybrid retrieval, RAGAS gated in CI (**0.81 / 0.996**)
- [**gridpulse-realtime-agent**](https://github.com/jsanchez-ds/gridpulse-realtime-agent) 🚨 Real-time streaming + custom LLM agent with function calling — consumes Projects 1 & 2 as tools, posts grounded incident reports to Discord

### Earlier portfolio

- [Telecom Quota Forecasting](https://github.com/jsanchez-ds/telecom-quota-forecasting) — XGBoost quantile ensemble for subscriber plan optimization
- [Bank Marketing Analysis](https://bank-marketing-analysis-jsanchez.streamlit.app/) — Interactive Streamlit demo + RF model (ROC-AUC 0.80)
- [Credit Choice Experiment](https://jsanchez-ds.github.io/credit-choice-experiment/) — Discrete choice modeling with mixed logit
- [Gender Income Gap](https://jsanchez-ds.github.io/gender-income-gap/) — Fixed-effects regression + ML on merchant data
- [Medical Diagnosis Classification](https://jsanchez-ds.github.io/medical-diagnosis-classification/) — SVM with GridSearchCV on Wisconsin Breast Cancer
