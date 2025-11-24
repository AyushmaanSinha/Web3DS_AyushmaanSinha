# Web3 Trading — Data Science

This repository enforces safe I/O rules so that **input files are never overwritten**.

It does not contain the '**historical_data.csv**'(45.3MB) file as GitHub supports maximum file size of 25MB, nevertheless the file does exist in the Google Colab Sheet
Link to the Sheet : 

## Structure

```
Web3DS_AyushmaanSinha/
├── csv_files/           <-- contains input CSVs and generated CSV outputs (no overwrites)
├── outputs/             <-- contains generated image outputs (PNGs)
├── notebooks/
│   └── ds_AyushmaanSinha.ipynb
├── README.md
└── ds_report.pdf
```

## Important behavior
- Generated CSV outputs are saved to `csv_files/`. If a generated filename collides with an existing file, the notebook appends a timestamp to the filename so the input file is never replaced.
- Generated image outputs are saved to `outputs/`.
- The Colab notebook `notebooks/ds_AyushmaanSinha.ipynb` is the main entry point.

## How to run in Colab
1. Upload your input CSVs into `/content/csv_files/` (create the folder in the Files pane).
2. Open `notebooks/ds_AyushmaanSinha.ipynb`.
3. Run all cells.
4. Download outputs from `/content/csv_files/` (generated CSVs) and `/content/outputs/` (images).
