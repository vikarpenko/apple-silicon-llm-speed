# Predicting Local LLM Inference Speed on Apple Silicon

## How to run

**Locally**

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```

Then run all cells.

**Google Colab**

Upload `notebook.ipynb`, create a `data` folder and upload the three files from `data/` into it (`llmcheck_benchmarks.csv`, `chips.csv`, `quant_bits.csv`), then run all cells.

The full run takes a few minutes. Tested with Python 3.13.
