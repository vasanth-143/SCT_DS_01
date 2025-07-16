=>Top 20 Most Populous Countries (2024)
This Jupyter Notebook uses World Bank data and Python (pandas + Matplotlib) to visualize the twenty most populous countries in 2024.

->Data set
- API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv — raw World Bank dataset.
- Metadata_Country_API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv - This metadata CSV file provides descriptions and classifications for the countries or regions included in the main population dataset, such as:
Column Name	Description
  * Country Code	ISO 3-letter code (e.g., IND, USA, CHN)
  * Region	World Bank regional classification (e.g., South Asia)
  * Income Group	Country’s income level (e.g., Low income, Upper middle income)
  * Special Notes	Notes about data collection or country-specific context
  * Table Name	Country name as shown in data tables
  * Short Name	Common name (e.g., India, China).
- Metadata_Indicator_API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv - This file contains metadata for the indicator itself — in this case, "SP.POP.TOTL", which stands for Total Population (as defined by the World Bank).
  * Code: SP.POP.TOTL
  * Name: Total Population
  * What: Mid-year total residents
  * Source: UN/World Bank
  * Use: For planning and analysis.

 -> How to Get Started
1. Launch Jupyter
   jupyter notebook
2. Open `countries.ipynb` in your browser.
3. run each cell by shift+enter.

-> What the Notebook Does
1. Reads the CSV file (skipping metadata rows).
2. Extracts columns for **Country Name** and **2024 population**.
3. Converts and cleans the data.
4. Sorts and displays the **top 10** most populous countries.
5. Plots a bar chart with readable labels and gridlines.

-> Notebook Highlights
* Clear markdown explanations between cells.
* Beautiful bar chart using `plt.bar(...)` with `skyblue` color.

 ->Requirements
* pandas
* matplotlib
* jupyter

# SCT_DS_01
