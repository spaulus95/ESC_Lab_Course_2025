# ESC_Lab_Course_2025

This repository contains Python code for performing Fluorescence Recovery After Photobleaching (FRAP) analysis and curve fitting using experimental data. The code generates plots for visualizing fluorescence intensity over time and performs curve fitting to extract key parameters like half-time, mobile fraction, and immobile fraction.

## Features

- Load experimental data from Google Sheets or CSV files.
- Perform FRAP analysis by plotting fluorescence recovery curves.
- Apply exponential curve fitting using the scipy library.
- Calculate and visualize key parameters including:
  - Half-time (t₁/₂)
  - Mobile Fraction (%)
  - Immobile Fraction (%)
- Export the results in table format.

## Dependencies

Make sure you have the following Python libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `scipy`

You can install them using:

```bash
pip install pandas numpy matplotlib scipy
```

## How to Use

1. Clone the repository and navigate to the directory.
2. Run the code using a Python environment with Jupyter Notebook support.
3. The data is fetched from Google Sheets using provided URLs. Make sure you have access to the data.
4. Adjust plot parameters such as color maps, axis labels, and titles if necessary.
5. View the generated plots and summary tables.

## Code Overview

- **Data Loading:** Data is read using `pandas.read_csv` from a Google Sheets link.
- **Plotting:** Matplotlib is used to generate line plots of fluorescence recovery over time.
- **Curve Fitting:** Non-linear curve fitting is applied using `scipy.optimize.curve_fit`.
- **Parameter Calculation:** Extracted parameters include recovery half-time and fractions.
- **Visualization:** Results are annotated on the plot with color-coded lines.

## Example Output

- Plots representing recovery curves for different genotypes.
- Tables with recovery parameters.

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.

## Acknowledgments

Special thanks to the Leonhardt Group for Human Biology and Bioimaging for hosting the Embryonic Stem Cells Lab course 2025 and providing the data and supporting the analysis.

For further questions, please reach out to the repository owner or contributors.

