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
Combined the temperature dataset with each of the six datasets from GHG emissions data, taking variance, mean, maximum temperatures into consideration. Then prepared six fully prepared datasets ready for analysis.

### Step 3: Data Analysis
Analyzed every dataset, including descriptive statistics and distribution plots of temperature features and emissions. Also calculated the top 10 countries with high emissions of both CO2 and GHG and analyzed sector-wise emissions. Performed correlation analysis, regression analysis, and time-series analysis of temperatures and emissions.

**Descriptive Statistics and Distribution Plots**
First looked at the descriptive statistics and distribution plots of temperature features and emissions for each country. Observed that the temperature and emissions data for each country followed a normal distribution.

**Top 10 Countries with High Emissions**
Calculated the top 10 countries with the highest CO2 and GHG emissions. Found that Japan, China, the United States, and Russia were the top emitters of both CO2 and GHG.

**Sector-wise Emissions**
Analyzed sector-wise emissions for each country. Found that the power generation sector was the most significant emitter of CO2 and GHG.

**Correlation Analysis**
Performed a correlation analysis to investigate the relationship between temperature and emissions.

**Regression Analysis**
Performed a regression analysis to model the relationship between temperature and emissions. Found that there was a significant linear relationship between the two variables.

**Time-series Analysis**
Analyzed the time-series data of temperatures and emissions to observe any trends and patterns. Found that both temperature and emissions had an increasing trend over the years.

### Step 4: Data Visualization
Created various visualizations to better understand the data and the relationships between variables. Also created scatter plots, line plots, heatmaps, and bar charts to visualize the data and observed patterns and trends.


Dashboard links:
<div><iframe title="co2_report" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiNmYzYjEyM2EtMWNiYS00M2ExLTliNzItZWI1MzkzOTQ0MGFjIiwidCI6IjA0ODI4NGUzLTljYjYtNGE3ZC1iMjU0LTA3ZDQ3N2Y4YzgzMiJ9" frameborder="0" allowFullScreen="true"></iframe></div>

<iframe title="Report Section" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiOWUwNzNiYTMtZWNjOS00M2JjLTllM2YtZTdhMWE4Yzg1MzRhIiwidCI6IjA0ODI4NGUzLTljYjYtNGE3ZC1iMjU0LTA3ZDQ3N2Y4YzgzMiJ9" frameborder="0" allowFullScreen="true"></iframe>

## Conclusion
<br>

<ul>
    <li><strong>Japan</strong> is the country which emits CO2 in high quantity.</li> 
    
<li>CO2 emissions and Variance of temperature are <strong>36%</strong> positively correlated with each other.</li>
    
<li>By using linear regression, predicted the CO2 emissions for the future years:</li>
<ul>
    
<li>At 2030, there will be approximately <strong>18028.504142</strong> metric tonnes of CO2 emissions.</li>
<li>At 2040, there will be approximately <strong>19502.314573</strong> metric tonnes of CO2 emissions.</li>
<li>At 2050, there will be approximately <strong>20976.125004</strong> metric tonnes of CO2 emissions.</li>
</ul>
<li>There is a trend of increasing CO2 and greenhouse gases emissions and average temperature over the years.</li>


<li>The <strong>power industry</strong> has been producing more CO2 emissions and Greenhouse gases over the years, making it a major contributor to environmental pollution.</li>

<li><strong>Qatar</strong> has the highest CO2 emissions per person compared to any other country.</li>


<li>There is a positive correlation of <strong>38%</strong> between CO2 emissions per capita and temperature variance. This means that as CO2 emissions per person increase, there is a corresponding increase in the variability of temperature.</li>


<li>The <strong>United States</strong> produces a large quantity of greenhouse gases compared to any other country.</li>

<li>There is a moderate correlation of <strong>26%</strong> between total greenhouse gas emissions and temperature variance. This suggests that as greenhouse gas emissions increase, there is a corresponding impact on the variability of temperature.</li>

<li>By using linear regression, predicted the Total green house gases emissions for the future years:</li>
<ul>
<li>At 2030, there will be approximately <strong>50964.282836</strong> metric tonnes of green house gases emissions.</li>
<li>At 2040, there will be approximately <strong>56105.610036</strong> metric tonnes of green house gases emissions.</li>
<li>At 2050, there will be approximately <strong>61246.937235</strong> metric tonnes of green house gases emissions.</li>
    </ul>
<li><strong>Palau</strong> has the highest greenhouse gases emissions per person compared to any other country.</li>

<li>There is a positive correlation of <strong>15%</strong> between greenhouse gases emissions per capita and temperature variance. This means that as CO2 emissions per person increase, there is a corresponding increase in the variability of temperature.</li>


</ul>



