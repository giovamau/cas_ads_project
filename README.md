# CAS in Applied Data Science — Final Project

This repository contains materials for a **CAS in Applied Data Science** final project, including Jupyter notebooks, minimal local datasets (kept out of version control), and the project poster. The goal is to make the work easy to understand, review, and reproduce.

---

## 🧭 Overview

* **Notebooks** document the end-to-end workflow: exploration, feature engineering, modeling, and evaluation.
* **Poster** includes the final presentation artifact and any supporting files.
* **Data** is stored locally under `data/` and excluded from version control to keep the repo lean and compliant with data policies.

---

## 📁 Repository Structure

```
cas_ads_project/
├─ Notebooks/        # Analysis and modeling notebooks
├─ Poster/           # Poster and related source files
├─ data/             # Local data only (ignored by git)
│  └─ README.md      # Where to get data / how to regenerate it
├─ requirements.txt  # Python dependencies
└─ README.md
```

**Data policy:** The `data/` directory is intentionally **not** tracked in version control. Keep raw, interim, and processed files here. Use `data/README.md` to explain where data comes from and how to obtain or recreate it (e.g., links, scripts, or generation steps).

---

## ▶️ Working With the Notebooks

* Use a recent Python 3 environment and install the packages listed in `requirements.txt`.
* Open the notebooks in your preferred Jupyter interface.
* Run notebooks top-to-bottom. If a notebook expects files, place them under `data/` and adjust any paths if needed.
* For heavy or external datasets, provide a small sample and describe the full source in `data/README.md` so others can test quickly.

---

## 📊 Poster / Report

The **Poster** folder contains the final poster and, when applicable, its editable source (e.g., presentation file or LaTeX). Include brief notes on how the poster was generated or exported so that it can be reproduced.

---

## 🔁 Reproducibility Guidelines

* Keep dependencies pinned in `requirements.txt`.
* Prefer relative paths (e.g., `data/...`) inside notebooks.
* Consider caching intermediate artifacts (e.g., cleaned data or features) under a `data/processed/` subfolder to speed up reruns.
* Note any randomness and set seeds where relevant; document versions for critical libraries.

---

## 📬 Contact

Questions or suggestions can be opened as issues or shared with **@giovamau** on GitHub.

