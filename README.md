# **Florida Building Permit Classification and Cost Forecasting**

## Project Overview
This project analyzes Florida building permit data to uncover trends in construction activity, zoning patterns, and development costs. Using Python (pandas, matplotlib, seaborn), the workflow includes data cleaning, transformation, exploratory analysis, and predictive modeling. The analysis highlights how permit data can support clearer planning, more efficient review processes, and better understanding of regional growth.

Beyond descriptive insights, the project applies machine learning models to classify permits as Residential or Commercial and uses time‑series forecasting to project average permit costs over the next five years. Together, these components demonstrate how data science can turn raw administrative records into actionable information for planners, developers, and community stakeholders.

## Features
1. **Data cleaning & preprocessing**
> Standardization of permit fields, handling missing values, and preparing structured     datasets for analysis.

2. **Exploratory data analysis (EDA)**
> Descriptive statistics and visual summaries of permit activity, zoning distribution, and cost patterns.
   

3. **Predictive Modeling**
> Classification of permits using Logistic Regression, Random Forest, and XGBoost, with XGBoost achieving the strongest performance and highest recall for Commercial permits

4. **Cost Forecasting**
> ARIMA and Prophet models used to forecast average permit costs, revealing a stable to slightly declining trend through 2026.

5. **Insights for Planning & Development**
> Interpretation of model outputs to identify key drivers such as zoning codes, project scales, and cost dynamics, supporting more informed decision-making.

<br></br>

## Tools & Libraries
* Python: pandas, matplotlib, seaborn, scikit-learn, XGBoost, statsmodels, Prophet

* Jupyter Notebook: analysis, documentation, and visualization environment

<br></br>

## Contributors
This project was developeded collaboratively by:

* **Carl Legros** – Quantitative research, data wrangling, feature engineering, statistical modeling, visualization

* **Joao Vitor Jeronimo** – Research analysis, academic writing, data exploration, methodological design

* **Rose Kerlande Jeanmary** – Applied research, presentation design, exploratory data analysis, contextual framing, interpretation

* **Pablo Olmedo** – Model assessment, presentation design, visual storytelling, audience‑focused communication
  
<br></br>
## License
This project is licensed under the MIT License. Reuse or sharing must include attribution to all contributors listed above.


### MIT License

Copyright (c) 2025
Carl Legros, Joao Vitor Jeronimo, Rose Kerlande Jeanmary, Pablo Olmedo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Project"), to deal
in the Project without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Project, provided that clear attribution is given to all contributors listed above.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE
AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE PROJECT OR THE USE OR OTHER DEA
