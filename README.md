# NumericData

This project demonstrates data wrangling and analysis using the `StudentSurvey` dataset in R. The analysis is performed in the R Markdown file `NumericData.Rmd` and covers several key data manipulation and summary tasks:

## Overview
The following steps are performed:

1. **Calculate and Add BMI**
	- A new BMI column is calculated using the formula $BMI = 701 \times \frac{Weight}{Height^2}$ and rounded to one decimal place.
	- The first 6 rows of Sex, Weight, Height, and BMI are displayed.

2. **Binning for Weight Status**
	- BMI values are categorized into "Underweight", "Healthy Weight", "Overweight", and "Obese" using the `cut` function.
	- The first 6 rows with the new Status column are shown.

3. **BMI Range by Sex**
	- The minimum and maximum BMI values are summarized for each sex.

4. **Max SAT Score per Student**
	- For each student, the greater of their VerbalSAT and MathSAT scores is computed and displayed alongside the original scores.

5. **Z-Scores for Total SAT**
	- The total SAT score (VerbalSAT + MathSAT) is calculated for each student.
	- Z-scores for the total SAT are computed and shown for the first 6 students.

## How to Reproduce
Open `NumericData.Rmd` in RStudio or another R Markdown-compatible editor and knit the document to view the analysis and output tables.

## Requirements
- R
- Packages: `Lock5Data`, `tidyverse`, `knitr`

## Author
Mia Fitzgerald
