# Final Individual Project: Predicting Body Weight from Height and Gender

## Student Information
Name: 李瑞澄
Student ID: 113370208

## Project Repository
https://github.com/[你的帳號]/[你的專案名稱]

## Presentation Video
https://youtube.com/[你的影片連結]

---

## Project Overview
This project explores the physiological relationship between high school students' height, biological sex, and body weight, using data from the 2007 Youth Risk Behavior Survey (YRBS).

* **Research Question**: Can a high school student's height and biological sex significantly predict their weight?
* **Methodology**: Multiple Linear Regression (OLS)
* **Key Findings**: Both height and sex are highly significant predictors of weight ($p < 0.001$). The regression model ($R^2 = 0.265$) demonstrates a positive correlation between height and weight, alongside a distinct baseline weight difference between male and female students.

---

## Directory Structure

* `data/`: Contains the original `YRBS_2007.csv` dataset.
* `notebooks/`: Contains the Jupyter Notebook (`.ipynb`) with the full Python code, data cleaning, and statistical workflow.
* `output/`: Contains the generated data visualizations (scatter plot and box plot).
* `infographic.pdf`: The one-page visual summary of the research project.
* `README.md`: Project documentation and links.

---

## Variable Notes

The following variables from the original `YRBS_2007.csv` dataset were selected, cleaned, and renamed for this regression analysis:

| Renamed Variable | Original Variable Name | Description | Data Type |
| :--- | :--- | :--- | :--- |
| **Sex** | `WhatIsYourSex` | Biological sex of the student (1=Female, 2=Male). Converted to string. | Categorical |
| **Height** | `HowTallAreYouWithoutShoesInMeters` | The student's height measured in meters. | Continuous |
| **Weight** | `HowMuchDoYouWeighWithoutShoesInKG` | The student's body weight measured in kilograms. | Continuous |

---

## References

### Data Reference
* Centers for Disease Control and Prevention (CDC). *2007 Youth Risk Behavior Survey (YRBS) Data and User Guide*.

### Code Reference
* [pandas: powerful Python data analysis toolkit](https://pandas.pydata.org/)
* [Matplotlib: Visualization with Python](https://matplotlib.org/)
* [seaborn: statistical data visualization](https://seaborn.pydata.org/)
* [statsmodels: Statistical models, hypothesis tests, and data exploration](https://www.statsmodels.org/)# Final-Project-cycle4
