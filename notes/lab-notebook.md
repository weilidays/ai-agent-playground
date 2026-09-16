# Lab Notebook

Add a dated entry every time you make a change to this repo. Newest entries at the top.

## 2026-09-16 — weili.zhong@nm.org
- Ran `analysis/summarize.py`; it crashed with `KeyError: 'cohort'` in `load_groups` because the script read a `cohort` column, but `data/reaction_times.csv` actually has the group label under a column named `group`.
- Fixed by changing `row["cohort"]` to `row["group"]` in `load_groups` (analysis/summarize.py).
- Re-ran the script successfully: `control: n=10, mean=504.7 ms`, `treatment: n=10, mean=430.8 ms`.

## Example — 2026-01-01 — A. Researcher
- Ran `analysis/summarize.py` for the first time; confirmed the repo and my tool are connected.
- No changes made yet — just checking the pipeline works end to end.

<!-- Add your own entry above this line -->
