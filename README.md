# Rproj

📈 R-Project: Inflation & Crime Dynamics in Europe (2013–2022)
Exploring the Econometric Link Between Cost of Living and Public Safety
🧐 The Research Question

Does rising inflation lead to increased social instability and crime? This project investigates the theory that economic pressure, by deteriorating purchasing power, may increase social stress and incentivize criminal behavior. By analyzing data across 35 countries over a decade, we aim to provide policymakers with insights into how economic shifts impact public security.
🛠️ The Analytical Stack

    The Language: R.

    Key Libraries: tidyverse (dplyr, ggplot2) for data manipulation and visualization, and regression tools for econometric modeling.

    The Data:

        Independent Variable (X): Harmonized Index of Consumer Prices (HICP), including annual average index and variation rates.

        Dependent Variable (Y): Crimes and Homicides per 100,000 inhabitants, covering intentional homicides and sexual offenses.

    Methodology:

        Data Merging: Combined datasets using Country and Year as keys.

        Cleaning: Reduced the dataset from 360 to 322 valid observations after removing incomplete data.

        Econometrics: Implemented OLS regressions, quadratic models, and high-dimensional fixed-effects models (Country and Year FE).

📂 Repository Contents

    final project r .pdf: The complete academic report detailing the full analysis, from data cleaning to final econometric results.

    exam.pdf: Associated examination materials or project guidelines.

    full_stats.csv: The master dataset containing the merged and cleaned indicators for all 35 countries.

📈 Key Insights & Findings

    Descriptive Trends: Most observed HICP values concentrate between 100% and 105%, while crime rates typically range from 0 to 2 per 100,000 inhabitants.

    The "France vs. Germany" Case: A specific comparison highlights that despite similar economic structures and HICP trends, France shows higher crime rates, potentially due to factors like urbanization levels and specific historical shocks (e.g., terrorist acts).

    The Inflation Shock: While a simple linear regression initially suggests a positive link, more rigorous testing reveals that the relationship is often non-significant when controlling for country-specific factors.

    Final Conclusion: Within this European sample, there is no statistically significant evidence that intra-country inflation directly causes an increase in crime and homicide rates.

🚀 How to Run the Analysis

    Clone the repo.

    Load the Data: Import full_stats.csv into your R environment.

    Run the Scripts: Execute the provided R code (documented in the PDF report) to regenerate the histograms, time-series plots, and fixed-effect tables.

👥 The Research Team

    Lucas SIMATOVIC

    Aymen MEHDID

    Danélius Dègnon ADJENIA
