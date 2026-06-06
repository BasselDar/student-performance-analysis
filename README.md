# Statistical Analysis of Student Performance

**Author:** Bassel Mostafa Darwesh  
**Purpose:** Application material for the M.Sc. Data Science program at TU Dortmund University (Winter Semester 2026/2027).

## Project Overview
This repository contains a complete statistical analysis investigating the disparities in student academic outcomes based on demographic factors, specifically gender and parental education levels. 

The analysis processes a dataset of 486 students, utilizing robust descriptive and inferential statistical methods to answer two primary research questions:
1. Is there a statistically significant difference between male and female students in Mathematics and Language scores?
2. Is there a difference in scores across varying levels of parental education?

## Repository Structure
* `Scores.csv`: The raw dataset containing student IDs, demographics, and test scores.
* `Analysis_of_Student_Performance.ipynb`: The Jupyter Notebook containing the full data pipeline, including preprocessing, visualization, variance analysis (ANOVA), and post-hoc testing (Tukey HSD).
* `README.md`: Project documentation.

## Methodology
The analysis was conducted entirely in Python. The statistical pipeline includes:
* **Data Cleaning:** Pivoting long-format data to wide-format to ensure independent group assumptions.
* **Descriptive Statistics:** Arithmetic means, standard deviations, and boxplot visualizations.
* **Hypothesis Testing:** Welch's Two-Sample t-tests (for binary gender comparisons) and One-Way ANOVA followed by Tukey's Honest Significant Difference test (for multi-level educational comparisons).

## Dependencies
To reproduce the environment and run the notebook, the following Python libraries are required:
* `pandas`
* `numpy`
* `scipy`
* `statsmodels`
* `matplotlib`
* `seaborn`

## Usage
To execute the analysis locally:
1. Clone this repository.
2. Ensure the dependencies listed above are installed in your Python environment.
3. Launch Jupyter Notebook and run `Analysis_of_Student_Performance.ipynb` from top to bottom.

## License
[MIT License](LICENSE)
