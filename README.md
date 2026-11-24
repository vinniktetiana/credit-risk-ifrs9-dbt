# Credit Risk & IFRS 9 ECL — dbt on BigQuery

End-to-end credit-risk pipeline on public loan data:
staging → DPD buckets → vintage curves → roll rates → IFRS 9 staging → ECL.

**Stack:** BigQuery · dbt · GitHub Actions (planned)
**Data:** Lending Club public loan data (Kaggle)

## Status
- [x] BigQuery sandbox
- [x] Repo
- [ ] Raw data loaded
- [ ] Staging models
- [ ] Risk models (DPD, vintage, roll rates)
- [ ] IFRS 9 staging & ECL
- [ ] Results & write-up

## Notes
_Learning notes on IFRS 9, BigQuery vs ClickHouse, and EU regulation go here._