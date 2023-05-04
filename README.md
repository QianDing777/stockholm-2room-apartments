# Project Title: Analyzing affordability of 2-room apartments in Stockholm for Junior Data Analysts

The goal of this project is to determine whether a junior data analyst can afford a 2-room apartment in the 5 most popular areas of Stockholm. This was done by scraping data from Hemnet, cleaning it, and then analyzing it to answer the following questions:

- What is the median salary for data analysts/engineers in Stockholm, and how does this compare to the prices of two-room apartments in the different areas?
- How much money should we save up before moving in order to be able to afford a two-room apartment in one of the areas, and how long would that take us?
- Are there any trends or patterns in the prices of two-room apartments in the areas over time (e.g. increases or decreases in prices)?

To answer these questions, data visualizations were created using the matplotlib library. In addition, data modeling was performed to predict how long it would take for a junior data analyst to save up for the down payment on a 2-room apartment in each of the 5 areas. Linear regression was initially tested, but ultimately, Random Forest was found to be the best model for this data.

However, it is important to note that the data only includes factors such as monthly fee (avgift) and size of the apartment. Other factors such as inflation and the size of the data set could affect the prediction. Additionally, outliers were removed from the data set to ensure more accurate results.

## File Description
- `clean.ipynb`, `analysis_intro.ipynb`, `analysis.ipynb`, `modeling.ipynb`: Jupyter notebook containing the data cleaning, analysis, and modeling process
- `data.csv`: CSV file containing the cleaned data
- `analysis_results.ipynb`: Jupyter notebook containing the analysis results
- `README.md`: Markdown file containing a description of the project

## Getting Started
1. Clone this repository
2. Install the necessary packages from `requirements.txt`
3. Run `clean.ipynb`, `analysis_intro.ipynb`, `analysis.ipynb`, `modeling.ipynb` to view the data cleaning, analysis, and modeling process
4. The resulting cleaned data and analysis results can be found in `data.csv`(cleaned the original raw data), `no_outlier_price.csv`(removed outliers for modeling) and `analysis_results.ipynb`, respectively.

## Conclusion
This project provides insight into the affordability of 2-room apartments in Stockholm for junior data analysts. While there are limitations to the data set and the prediction model, this project demonstrates the importance of data analysis in making informed decisions about where to live and how much to save.
