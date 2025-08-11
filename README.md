# India Census 2011 Data Analysis
## Project Overview
This project provides an in-depth analysis of the India Census 2011 dataset. The goal of this analysis is to explore various demographic and administrative data points to understand population distribution, density, and key metrics across different administrative levels of India.
The analysis is performed using a Jupyter Notebook and leverages popular Python libraries for data manipulation and visualization.
## Key Features
Data Cleaning and Preprocessing: The notebook demonstrates how to handle missing values, drop duplicate records, and filter the dataset to focus on relevant information.
Exploratory Data Analysis (EDA): The analysis includes a series of statistical summaries and visualizations to understand the dataset's structure and contents.
Population Density Analysis: The report focuses on comparing population density across states, districts, and sub-districts.
Visualization: Matplotlib and Seaborn are used to create informative plots, including bar charts and scatter plots, to visualize the distribution of population metrics.
## Jupyter notebook Structure
The Indiacensusreport.ipynb notebook is structured into the following sections:
Library Imports: Importing essential libraries like pandas, matplotlib.pyplot, and seaborn.
Data Loading: Reading the India Census 2011.xlsx file into a pandas DataFrame.
Data Inspection: Initial inspection of the dataset to check for data types, non-null counts, and sample records.
Data Cleaning: Steps to clean the data by dropping records with Rural/Urban as 'Total' and Level as 'INDIA', as well as handling missing and duplicate values.
Common Analysis: A series of code cells to perform basic statistical analysis, such as counting the number of rural and urban states, districts, and sub-districts.
Top 10 Analysis: Calculating and visualizing the top 10 administrative regions (states, districts, sub-districts) based on population density (Population per sqkm).
## Dependencies
The following Python libraries are required to run the notebook in this repo:
* pandas
* matplotlib
* seaborn
* openpyxl (to read the .xlsx file)

### You can install these dependencies using pip:
pip install pandas matplotlib seaborn openpyxl
* How to Run
Clone this repository.
* Ensure you have the India Census 2011.xlsx file in the same directory as the notebook, or update the file path in the notebook.
* Install the required dependencies listed above.
* Open the Indiacensusreport.ipynb file in a Jupyter environment (e.g., Jupyter Notebook, JupyterLab, VS Code with the Jupyter extension).
Run the cells sequentially to reproduce the analysis and visualizations.
# Output
The notebook generates several outputs, including:
DataFrames showing the top 10 states, districts, and sub-districts by population density.
Visualizations comparing population density across different administrative levels.

Disclaimer: This analysis is based on the India Census 2011 data and may not reflect current population metrics.
