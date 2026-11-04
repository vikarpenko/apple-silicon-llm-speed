# Predicting Local LLM Inference Speed on Apple Silicon

## How to run

### Google Colab

1. Open notebook.ipynb in Google Colab (File -> Upload notebook).
2. Open the Files panel on the left (folder icon) and upload the three data files from the data folder: llmcheck_benchmarks.csv, chips.csv and quant_bits.csv. Colab cannot read them from this repository by itself, so they must be uploaded by hand.
3. In the Setup cell, change the data path to the folder where you uploaded the files. If you uploaded them straight into the Files panel (not into a folder), use:

   ```python
   DATA_DIR = "/content/"
   ```

   If you created a folder named data and uploaded the files into it, keep `DATA_DIR = "data/"`.

4. Run all cells (Runtime -> Run all).
