# pandas-playground

> The Holy Grail of pandas. A pile of notebooks, one `.venv`, and absolutely no
> supervision.

Somewhere in here is the secret to clean data. Mostly there are Pokémon.

## Getting started

```bash
uv sync
```

Open a notebook, point the kernel at `.venv`, and start mangling. If a cell
errors, that's not a bug, that's the journey.

## The notebooks

More will show up here over time. So far:

| Notebook | Quest |
|---|---|
| `pandas_workbook.ipynb` | Series and DataFrames from first principles. The "wait, it's just a dict?" chapter. |
| `pandas_import.ipynb` | CSVs, `.loc` vs `.iloc`, boolean masks. Pikachu's Attack stat gets interrogated. |
| `pandas_data_cleaning.ipynb` | Dropping columns, hunting NaNs, and one column containing three different date formats, because of course it does. |

## Data

Everything in `data/` comes from [Kaggle](https://www.kaggle.com/datasets) —
a small exercise log, and 800 Pokémon who did not consent to being a dataset.
All credit to the original uploaders; none of it is mine.

## House rules

1. If a cell works, don't look at it.
2. `df.head()` is a personality trait.
3. Restart the kernel before blaming pandas.
4. There is always one more NaN.

*No DataFrames were harmed. Several were reindexed against their will.*
