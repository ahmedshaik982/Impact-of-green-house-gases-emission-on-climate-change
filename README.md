# Analyzing the Impact of Greenhouse Gas Emissions on Climate Change

## Introduction:
Climate change is one of the most pressing challenges of our time, with greenhouse gas emissions being a primary contributor. The aim of this project is to investigate the impact of greenhouse gas emissions on temperature change. Using data on CO2 and green house gas emisisons per country, sector, and per captia as well as temperature data per country and year, I conducted a detailed analysis to uncover any trends and patterns. My analysis includes data acquisition, data preparation, exploratory data analysis, regression analysis, and data visualization. Through this project, I hope to provide valuable insights into the impact of greenhouse gas emissions on climate change and contribute to the ongoing efforts to combat this global issue.

## Background Information
Before delving into the project methodology, it is essential to understand the background information that drives the project. Climate change has become a significant global challenge, with rising temperatures, sea-level rise, and extreme weather events affecting the lives of people and ecosystems. The primary cause of climate change is attributed to the increasing concentration of GHGs in the atmosphere. The combustion of fossil fuels, deforestation, and other human activities have led to the release of these gases in the atmosphere, trapping heat and causing the Earth's temperature to rise. Therefore, it is essential to understand the link between GHG emissions and climate change to mitigate the adverse effects.

## Methodology
The project methodology involves the following steps:

### Step 1: Data Acquisition
Acquired the yearly GHG emissions data from https://edgar.jrc.ec.europa.eu/report_2021?vis=ghgpop#emissions_table.
and daily temperatures data from https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data

The GHG emissions data consists of six datasets: 
<ul>
    <li>yearly data of total CO2 emissions per country</li>
    <li>total CO2 emissions per sector</li>
    <li>total CO2 emissions per capita</li>
    <li>total GHG emissions per country</li>
    <li>total GHG emissions per sector</li>
    <li>total GHG emissions per capita.</li>
</ul>


### Step 2: Data Preparation
We combined the temperature dataset with each of the six datasets from GHG emissions data, taking variance, mean, maximum temperatures into consideration. We then prepared six fully prepared datasets ready for analysis.

### Step 3: Data Analysis
We analyzed every dataset, including descriptive statistics and distribution plots of temperature features and emissions. We calculated the top 10 countries with high emissions of both CO2 and GHG and analyzed sector-wise emissions. We also performed correlation analysis, regression analysis, and time-series analysis of temperatures and emissions.

**Descriptive Statistics and Distribution Plots**
We first looked at the descriptive statistics and distribution plots of temperature features and emissions for each country. We observed that the temperature and emissions data for each country followed a normal distribution.

**Top 10 Countries with High Emissions**
We calculated the top 10 countries with the highest CO2 and GHG emissions. We found that China, the United States, and India were the top emitters of both CO2 and GHG.

**Sector-wise Emissions**
We analyzed sector-wise emissions for each country. We found that the power generation sector was the most significant emitter of CO2 and GHG.

**Correlation Analysis**
We performed a correlation analysis to investigate the relationship between temperature and emissions. We found that the two variables had a negative correlation of 20%.

**Regression Analysis**
We performed a regression analysis to model the relationship between temperature and emissions. We found that there was a significant linear relationship between the two variables.

**Time-series Analysis**
We analyzed the time-series data of temperatures and emissions to observe any trends and patterns. We found that both temperature and emissions had an increasing trend over the years.

### Step 4: Data Visualization
We created various visualizations to better understand the data and the relationships between variables. We created scatter plots, line plots, heatmaps, and bar charts to visualize the data and observed patterns and trends.

## Conclusion
In conclusion, this project aimed to study the impact of GHG emissions on climate change using data analysis and visualization techniques. The project involved acquiring data from various


