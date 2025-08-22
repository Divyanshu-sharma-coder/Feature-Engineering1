# Feature-Engineering1

<!-- PROJECT BANNER -->
<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOTFhM2M2ZWYzN2Q5NTYxMTk1ZDUyN2Q2MzI0YzQ0ZDNhZGI0N2RjMCZjdD1n/coxQHKASG60HrHtvkt/giphy.gif" width="680" alt="Data to Insights">
</p>

<h1 align="center">🧹✨ Feature Engineering & Dataset Cleaning</h1>
<p align="center">From messy data ➜ model-ready features, step by step.</p>

<p align="center">
  <!-- Badges -->
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-2.x-150458?logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-1.x-F7931E?logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/numpy-1.x-013243?logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/black-formatter-000000?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/pre--commit-enabled-efefef?logo=pre-commit&logoColor=EF3340" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" />
  <img src="https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F%20in-India-ff9933" />
</p>

---

## 🚀 What’s inside

- **Reusable cleaning steps**: missing values, outliers, encoding, scaling, date & text features, leakage checks.
- **Feature blocks**: numerical, categorical, datetime, NLP-lite, target encoding (safe!), interactions, binning.
- **Ready-to-plug pipelines** (Scikit-Learn `Pipeline`/`ColumnTransformer`).
- **Before/After EDA** snapshots to see impact.
- **Notebook recipes** + minimal scripts for CLI use.

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZGNlM2M0MjMzMTg1ZGQ1Zjg2ZTkzYzA1M2I5NzA3Y2Y3MzM5OWE3OCZjdD1n/3oEduQAsYcJKQH2XsI/giphy.gif" width="520" alt="Clean & Transform">
</p>

---

## 🧭 Quick Start

```bash
# 1) Clone
git clone https://github.com/<YOUR-USER>/<YOUR-REPO>.git
cd <YOUR-REPO>

# 2) Create env (any tool works; here is venv)
python -m venv .venv && source .venv/bin/activate  # Windows: .venv\Scripts\activate

# 3) Install
pip install -r requirements.txt

# 4) Run a sample pipeline on data/
python scripts/run_cleaning.py --input data/raw/train.csv --output data/clean/train_clean.csv

# 5) Open the cookbook notebooks
jupyter lab
