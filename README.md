# Tesla-Sales-Visualizing-the-Journey-of-Electric-Excellence
Visualizing the Journey of Electric Excellence

🚀 Project Overview
This project provides a comprehensive data analysis of used Tesla vehicles, utilizing data cleaning, exploratory analysis, and compelling visualizations to uncover trends and patterns in Tesla resale markets. We aimed to understand price fluctuations, geographic trends, and the role of features like Drive Assist Systems (DAS) in pricing.

Dataset Source: Kaggle - Tesla Used Cars Dataset

Tools Used: Python, Google Colab, Pandas, NumPy, Seaborn, Matplotlib, Plotly

Team Members:

Vaishnavi Mada

Jarred Carrol

Srujani Mareddy

📂 Dataset Description
The dataset includes information such as:

Price

Odometer Reading

State & Zip Code

Paint Job

Model

Drive Assist System (DAS)

Accident History

🛠️ Data Preprocessing
Removed outliers using boxplots (for price and odometer)

Eliminated redundant columns (e.g., location)

Cleaned missing values for driveTrain, year, and state using zip-code mapping

Converted and standardized categorical and numerical fields

📈 Exploratory Data Analysis
📌 Univariate Analysis
Histograms and boxplots for price, odometer, and model distributions

Pie chart for paint job popularity using a custom Seaborn color palette

🔁 Bivariate Analysis
Scatterplots for price vs. odometer

Boxplots for DAS vs. odometer

Pairplots across numerical and categorical features (e.g., accident history vs. model)

📍 Geographic Insights
Choropleth map showing average prices by U.S. state

Interactive insights into model demand and pricing variations state-wise

🧠 Drive Assist System (DAS) Insights
DAS correlation with odometer and price

Breakdown of DAS-equipped vehicles across models and states

📊 Visualization Highlights
Bar Charts: Tesla model frequency

Scatterplots: Price vs. odometer

Choropleth Map: Price variation by state

Boxplots: Odometer and DAS comparisons

Pairplots: Comprehensive variable interrelation analysis

📌 Conclusion
Our analysis uncovered several key insights:

States show strong variation in used Tesla prices

Drive Assist Systems impact both pricing and usage patterns

Certain Tesla models have significantly different resale trends

The project showcases how real-world data can be transformed into actionable insights using visualization and statistical analysis.

📎 Useful Links
📓 Google Colab Notebook

📁 Dataset CSV
