<H1>Retail Inventory Forecasting & Visualization using Python and Tableau</H1>

<H4>Author: Bhavikaben Radadiya</h4>
<H4>Affiliation: Berlin School of Business and Innovation (BSBI) – MSc Data Analytics</H4>
<H4>Year: 2025</H4>

<H3>📘 Project Overview</H3>
This repository accompanies the MSc dissertation titled “Optimizing Retail Inventory Management using Python Forecasting Models with Tableau Insights.”
The research integrates machine learning forecasting techniques (ARIMA, XGBoost, and LSTM) with interactive Tableau dashboards to enhance decision-making accuracy, speed, and confidence in retail inventory management.

The study demonstrates how predictive analytics and visualization tools can be combined to improve managerial forecasting and decision support under realistic retail scenarios.
 <H3>🎯Research Objectives</H3>

To evaluate the forecasting accuracy of ARIMA, XGBoost, and LSTM models using retail inventory data.

To integrate the best-performing model (XGBoost) into Tableau for visual insight generation.

To assess whether visual dashboards improve decision-making accuracy, confidence, and speed compared to raw tabular data.

<H3>📘 Research Flow Diagram</H3>

![Research Flow Diagram](https://github.com/bhavikaradadiya/Retail-Data-Forecasting/blob/main/Research%20Flow%20Diagram.png)


<H3>🧠 Methodology </H3>

The research follows a two-phase approach:

<B>1️⃣ Forecasting Phase (Python)</B>

Data cleaning and preprocessing.

Model development: ARIMA, XGBoost, and LSTM.

Evaluation using RMSE, MAE, and MAPE.

XGBoost selected as the most accurate model (Chen & Guestrin, 2016).

<B>2️⃣ Visualization & User Testing Phase (Tableau + Google Forms)</B>

Forecast outputs visualized using interactive Tableau dashboards.

Two groups of participants compared:

<B>Group A:</B> Tableau dashboard users.

<B>Group B:</B> Raw table users.

Performance analyzed on decision accuracy, speed, and confidence using descriptive statistics and t-tests.

<B>User Testing Overview</B>

Primary user testing was conducted using a Google Form experiment to compare decision-making performance between Tableau dashboard users and raw data table users.  
(For privacy reasons, the form and raw responses are not publicly shared.)

<H3>🧰 Tools & Technologies</H3>

<B>Category	Tools Used</B>

 Programming	Python (pandas, numpy, statsmodels, xgboost, keras, matplotlib)
 
Visualization	Tableau Desktop

Statistical Testing	SciPy, pandas

Survey Tool	Google Forms

Environment	Google Colab / Jupyter Notebook

<H3>📊 Key Findings</H3>

XGBoost achieved the lowest RMSE, MAE, and MAPE values → confirming its superiority over ARIMA and LSTM.

Tableau dashboards significantly improved decision speed (+22%), accuracy (+18%), and confidence (+15%) compared to raw tables.

T-test results indicated a statistically significant difference in decision performance (p < 0.05).

These results confirm both hypotheses:
<H4>✅ H1: XGBoost provides higher forecasting accuracy than ARIMA.</H4>
<H4>✅ H2: Tableau dashboards lead to faster, more accurate, and more confident decisions.</H4>

<H3>🧩 Ethics and Data</H3>

The dataset is synthetic, ensuring no privacy or confidentiality issues (Patki et al., 2016).

All participants provided informed consent prior to participation.

Raw Google Form responses are not included in this repository for confidentiality reasons.

<H3>🔗 Citation</H3>

If you reference this work, please cite as:

Radadiya, B. (2025). Retail Sales Forecasting by Model [Source code]. GitHub. Available at: https://github.com/bhavikaradadiya/Retail-Data-Forecasting

<H3>💡 How to Reproduce</H3>

Clone this repository.

Install dependencies:

pip install -r requirements.txt


Run the notebook  main / Retail_Sales_Forecasting_By_Model.ipynb

Open Tableau → Live Tableau Dashboard → [View Here] (https://public.tableau.com/app/profile/bhavikaben.radadiya/viz/Retail_sales_17571698112880/Dashboard1)

![Dashboard Overview](https://github.com/bhavikaradadiya/Retail-Data-Forecasting/blob/main/dashboard.png)

Replicate dashboards for trend and performance analysis.

<H3>🏁 Acknowledgment</H3>

This project forms part of the MSc Data Analytics dissertation at BSBI (Berlin School of Business and Innovation) under the supervision of the academic faculty.
Special thanks to students and professionals , Tableau Public, and Kaggle’s Atomic Data team for enabling transparent, reproducible research.

<H3>🔑 Keywords</H3>

Retail Forecasting · XGBoost · ARIMA · LSTM · Tableau · Visualization · Inventory Management · Decision Support · Predictive Analytics · User Testing







