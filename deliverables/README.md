# Correlation Analysis — Supply Chain
This repository contains the correlation matrix and Excel-style heatmap.

**Email:** 22f1001636@ds.study.iitm.ac.in

## Files
- `correlation.csv`: Correlation matrix for the first 5 numeric columns of the dataset.
- `heatmap.png`: Heatmap visualization using a Red–White–Green color scale.
- `README.md`: This file.

## Reproducing in Excel (ToolPak)
1. Enable ToolPak: File → Options → Add-ins → Excel Add-ins → Analysis ToolPak.
2. Data → Data Analysis → Correlation.
3. Select the 5 data columns (with Labels in first row).
4. Output to new worksheet.
5. Copy correlation matrix to a new sheet.
6. Select only the correlation values (not labels), then Home → Conditional Formatting → Color Scales → Red–White–Green.
7. Take a 400–512 px square screenshot as `heatmap.png`.
