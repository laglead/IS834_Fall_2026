# Datasets

Every dataset used in this course lives here — one copy each, no per-week duplicates.

Notebooks read these files directly over HTTPS, so there is **nothing to download
and nothing to upload**. A notebook opened in a fresh Google Colab tab runs
end-to-end as-is.

Each notebook defines the location once:

```python
DATA = "https://raw.githubusercontent.com/elhamod/IS834_Fall_2026/main/data/"
df = pd.read_csv(DATA + "diamonds.csv")
```

`sample-database.db` is a SQLite database rather than a flat file, so it is
downloaded to the Colab session first and then opened — the notebook that uses
it shows how.
