## Exogenous Shocks Analysis

#### Project Overview

Evolving US tariff policy provided ample motivation for this independent project, which seeks to understand how countries, economic variables and prices have responded to exogenous shocks.  ESA (Exogenous Shocks Analysis) leverages advanced analytics methods to explore the macro-financial impact of five past shocks:

•	GFC (Global Financial Crisis)

•	CPC (Commodities Price Collapse, 2014)

•	Covid-19 Pandemic

•	Russia-Ukraine War

•	BOJ (Bank of Japan) Rate Pivot
 
The topic selection assumes that the past can teach us something about the future, even though US tariff policy represents a different type of shock from those analyzed.

#### Scope

Timeframe: *Jan 2006 - Mar 2025*

Countries: *Australia, Germany, Japan, Norway, South Korea, Switzerland, United States*

#### Project Goal

This independent project is designed for senior management at multinational firms.

Examining past shocks may help anticipate future disruptions, and refine risk mitigation strategies.

#### Data Sources

Macroeconomic time series data: OECD Data Explorer online tool (OECD = Organisation for Economic Co-operation and Development)

Shock periods: Google search.

Commodities prices, except gold: IMF DataMapper onine tool (IMF = International Monetary Fund)

Gold prices: www.datahub.io

Foreign currency exchange rates: www.ofx.com

VIX (Cboe Volatility Index): CBOE (www.cboe.com)

#### Tools

•	Languages & Libraries: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels, Math, Folium, Json, Datetime, Pylab, Mpl_toolkits)

•	Software: Jupyter Notebooks, Excel, Tableau Public

#### Techniques Used

•	Data wrangled, cleaned, merged, grouped, aggregated, interpolated, summarized, transformed (log returns, first difference percentages, z-score normalization)

•	Created new variables

•	Supervised learning: Univariate linear regression

•	Time series data preprocessed, decomposed, stationarity-tested, stationarized for forecasting

•	Univariate time series forecasting using an ARIMA model

•	PCA (Principal Component Analysis)

•	K-means linear clustering analysis

•	Data visualized in Python (3D & 2D scatterplots, choropleth maps, matrices of line plots, stacked bar histograms, correlation heatmaps, lagged correlation line plots, and tables) and Tableau Public environments (choropleth map, line plots, scatterplots, stacked bar histograms)

•	Interactive chart rotations via parameter controls & calculated fields in Tableau Public

•	Co-created a bespoke model using Python, Excel and PCA + k-means clustering analysis results to score and rank countries on their shock-response economic resilience

#### Attribution

The Shock Resilience Score (SRS) model and scoring methodology were co-developed with OpenAI's ChatGPT, powered by GPT-4o, based on an iterative process combining human insight and AI-aided reasoning.  ChatGPT was also enlisted to customize grid-plotting functions for hundreds of exploratory visualizations with categorical variable overlays.  Assistance extended to code debugging, RAM conservation practices, feedback on univariate linear regression limitations for financial time series data, and elaboration on data science or data analytics topics and methods.

#### Key Findings


•	Covid-19 and the GFC classify as major shocks with asymmetric impact on the seven OECD countries and range of variables examined. The CPC might classify as moderate, with the Russia-Ukraine War and BOJ Rate Pivot as minor despite disrupting crude oil and natural gas prices to Europe and provoking a partial unwind of the global carry trade, respectively.

•	PCA + k-means clustering analysis revealed groups of like-behavior variables that primarily trend (inflation and stock market indices, gold price), mean-revert (AUDJPY, oil price, unemployment rate, 10-year interest rate) or display non-cyclical volatility (the VIX) over the 20-year period reviewed. Mean-reversion manifested as a secondary effect for trending variables.

•	Shocks magnified the pendulum swings, as expected. Cause-effect lens on mankind: the mean-reversion phenomenon revealed in the charts highlights government and private sector effective risk mitigation responses, reversing adverse pendulum swings.

•	Currency cross-rate movements during shock periods confirmed that the CHF (Swiss Franc) retained its position as the world's #1 safe haven currency, JPY (Japanese Yen) as #2, and USD (US Dollar) as #3. The commodities-driven AUD (Australian Dollar), a global "risk-on" speculative currency favorite, saw increased demand once crises ended. Separately, the price of gold was the only shock-immune variable, trending inexorably higher (with a few pauses) across two decades.

•	Norway ranked #1 on our bespoke SRS (Shock Resilience Score) model measuring economic resilience against shock adversity, South Korea #2. The United States ranked #7, dead last. Size matters not: a country's economic resilience does not positively correlate with its population or GDP size. In fact, the opposite may be true, although the scope of analysis should extend to more countries.

#### Folders

•	01 Visualizations: Small subset of some types of visualizations from the Python scripts, as a sample.

•	02 Data: Original Data and Prepared Data sub-folders with datasets.

•	03 Project Management: Project Brief.

•	6.1 to 6.6 "ESA" folders: Python scripts for data analysis, differentiated by topics.

**Comment:**  The Excel file "Definitions - Original Raw Data Variables.xlsx", in the "Original Data" sub-folder of the "Data" folder, provides definitions for each original raw data variable examined.  The Excel file "SRS Component Data - Rankings.xlsx" in the "Prepared Data" folder, which was uploaded in the Python script file "6.5 Task 6.5 SRS derivation", has the per-country SRS model individual metric rankings.  The Python script file has the SRS model code, metric descriptions and weightings. The Excel file "all_countries_srs_raw_regressions.xlsx", in the "Prepared Data" folder, has the raw data and linear regression results that were used to calculate the per-metric rankings of countries recorded in the "SRS Component Data - Rankings.xlsx" file.

#### Deliverables

•	Tableau Storyboard: Synthesizes, condenses and summarizes the project's Python-based analysis and key findings.

•	GitHub Repository: Stores Jupyter Notebooks with Python scripts and visualizations, Excel data files.

#### Project Links


•	["Exogenous Shocks Analysis" Tableau Storyboard]( https://public.tableau.com/views/ExogenousShocksAnalysis/ESASTORYBOARD?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

