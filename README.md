# Cricket World Cup 2019 — data analysis

Ball-by-ball analysis of matches from the 2019 Cricket World Cup, worked
through in a Jupyter notebook against hand-collected spreadsheets.

## Contents

| Path | What it is |
| --- | --- |
| `CWC2019.ipynb` | The analysis |
| `Match 8/` | Per-innings spreadsheets and charts |
| `Match 14/` | Same, including India vs Australia |

Each match directory holds a workbook per side plus a `Stats per over` sheet,
with generated charts under `IMGS/`.

## Running it

```bash
pip install pandas matplotlib openpyxl jupyter
jupyter notebook CWC2019.ipynb
```

`openpyxl` is required — pandas cannot read `.xlsx` without it.

## Licence

MIT.
