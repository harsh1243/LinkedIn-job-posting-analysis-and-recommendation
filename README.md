# LinkedIn-job-posting-analysis-and-recommendation

> ## 📦 This repository has moved
>
> This analysis now lives in **[TalentSync](https://github.com/harsh1243/TalentSync)** under the
> [`market-analysis/`](https://github.com/harsh1243/TalentSync/tree/main/market-analysis) folder,
> alongside the CV↔job matching engine it supports.
>
> **This repo is archived and read-only.** Its full commit history was preserved in the move —
> nothing was lost. Please use TalentSync for anything current.

---

## What was here

Exploratory analysis of 1.3M+ LinkedIn job postings:

- `data_clearning.ipynb` — cleaning and normalizing the raw postings
- `eda.ipynb` — top titles, companies, locations, job types, posting-time patterns
- `clustering.ipynb` — K-Means over skill vectors to find role clusters
- `assosication_rules.ipynb` — FP-Growth mining of skill co-occurrence rules
- `harsh.pbix` — Power BI dashboard

**Dataset:** [1.3M LinkedIn Jobs and Skills 2024](https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024) by *asaniczka* (Kaggle)
