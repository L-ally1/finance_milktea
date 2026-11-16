# README

# Financial & Business Analysis: Bawang Chaji vs Nayuki

This project conducts quarterly financial and operational analysis for two leading new-tea listed companies.
Raw financial data was extracted from corporate earnings releases. The original dataset contained annual cumulative figures in Dec, which cannot be directly used as quarterly value.

## Project Workflow

1. Data cleaning: Convert cumulative annual data into real Q4 quarterly metrics; distinguish flow metrics vs point-in-time metrics.
2. KPI calculation: Gross margin, net margin, GMV-revenue conversion ratio.
3. Visualization: Revenue, profit margin, single-store GMV and store expansion trends.
4. Business interpretation: Compare franchise model (Bawang Chaji) vs direct model (Nayuki).

## Folder Structure

- `data/`: raw original csv and cleaned processed csv
- `charts/`: output visualization figures
- `notebooks/`: Jupyter notebook with full analysis code

## Key Insights

- Fast store expansion leads to single store GMV dilution.
- Different business models create big differences between GMV and accounting revenue recognition.

## Tools

Python, Pandas, Matplotlib
