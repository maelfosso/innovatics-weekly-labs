# InnovatiCS — Data Science & AI Weekly Labs

My weekly lab work for the **InnovatiCS 40-week Data Science & AI program** (cohort AI&DS B-25).

Each week brings a brief and a starter notebook applying a set of tools to a business case.
This repository holds my completed solutions — one folder per week — and a small shared
toolkit (`src/innovatics/`) that grows as reusable functions emerge.

## Weekly labs

| Week | Topic | Tools | Status |
|:---:|---|---|---|
| 17 | [Advanced Python for AI](weeks/week-17-advanced-python-ai/) | Beautiful Soup, SciPy, TensorFlow/Keras, PyTorch, LangChain | In progress |

## Repository structure

```
.
├── src/innovatics/   # shared helpers reused across weeks
├── templates/week/   # skeleton copied at the start of each week
└── weeks/            # one folder per weekly lab
```

## Getting started

Requirements: Python 3.12 and [uv](https://docs.astral.sh/uv/).

```bash
git clone https://github.com/maelfosso/innovatics-weekly-labs.git
cd innovatics
uv sync --all-groups
uv run jupyter lab
```

> macOS: XGBoost and LightGBM require OpenMP — `brew install libomp`.

## Stack

- **Data:** Polars, pandas, NumPy, SciPy, DuckDB
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Machine learning:** scikit-learn, statsmodels, XGBoost, LightGBM
- **Deep learning:** TensorFlow/Keras, PyTorch
- **NLP & LLM:** Hugging Face Transformers, LangChain

## Notes

Course briefs and starter materials are © InnovatiCS and are not redistributed here.
Lab data is simulated for educational purposes unless stated otherwise.

---
**Author:** Mael Fosso