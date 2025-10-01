# GAMU: Interactive webR App for Data Analysis

This is an **interactive HTML + webR application** that lets you run R code directly in your browser. Everything runs client-side — no R installation or server required.

## Features

* **Upload ZIP files** containing folders with CSV files.
* **Explore files** inside extracted folders.
* **Select any CSV file** to load and analyze.
* **Plot your data** using `ggplot2` with customizable titles.
* **Fit linear regression models** (`Width ~ Size * Type`).
* **Plot fitted regression lines** along with your original data.
* **Download results**: regression coefficients as CSV and plots as PNG.

## Example Data

For testing, you can use the example CSV files included in this repository inside a ZIP file:

* `Results_simple.zip`
* `Results_complicated.zip`

Upload a ZIP file containing these files or your own data. After extraction, select the folder and CSV file you want to analyze.

## How to Run

### Online

If the app is hosted via GitHub Pages, visit:

```
https://tomas-pompa.github.io/webR-demo/
```

## Notes

* Uses **webR** with `ggplot2` and `dplyr`.
* All computations are performed in your browser; no server required.
* After extracting a ZIP, you can inspect all folders and files before selecting the CSV to analyze.

