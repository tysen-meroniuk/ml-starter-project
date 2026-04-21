# ml-starter-project

Self-study project: predict SPY direction using technical indicators, evaluated with proper walk-forward backtesting.

Plan lives at `/Users/tysenmeroniuk/quant-ml-project-plan.md`.

## Setup

```bash
python3.11 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

Then open the `notebooks/` folder in Cursor and work through them in order.

## Layout

```
.
├── data/          # cached market data (gitignored)
├── notebooks/     # one notebook per chunk
│   └── 01_data_loading.ipynb
└── src/           # reusable functions, imported into notebooks
    ├── data.py
    ├── features.py
    └── backtest.py
```
