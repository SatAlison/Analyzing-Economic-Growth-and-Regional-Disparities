# Global Economic Analysis: Trends and Disparities in GDP

## Table of Contents
1. [Project Overview](#project-overview)
2. [Motivation and Objectives](#motivation-and-objectives)
   - [Objectives](#objectives)
3. [Data Sources and Timeline](#data-sources-and-timeline)
4. [Tools](#tools)
5. [Project Workflow](#project-workflow)
6. [Insights and Recommendations](#insights-and-recommendations)
   - [Key Insights](#key-insights)
   - [Recommendations](#recommendations)
7. [Limitations](#limitations)
8. [Impact and Future Plans](#impact-and-future-plans)
9. [References](#references)
10. [Contact Information](#contact-information)

## Project Overview
This project analyzes global GDP data to identify trends and differences in economic performance across various regions. Using a detailed dataset that includes GDP information from around the world, the analysis explores key factors that affect economic growth rates. The goal is to gain insights into these patterns and understand the underlying dynamics of global economic performance.

## Motivation and Objectives
The motivation for this project stems from the desire to understand global economic trends and how certain regions perform relative to others. Economic growth is a key indicator of a country’s well-being, and by examining global GDP data, we can pinpoint areas where growth is either accelerating or lagging. This analysis aims to uncover key patterns that could inform policy decisions or economic strategies.

### Objectives

1. **Analyze Global GDP and GDP PPP (Purchasing Power Parity)**
   - Examine GDP and GDP PPP across regions in 2023.
   - Calculate the average GDP and GDP PPP for each region.
   - Assess the GDP percentage increase for each region from 1991 to 2023.
     
2. **Analyze GDP per Capita (PPP)**
   - Evaluate the GDP per capita (PPP) for each region in 2023.
   - Track changes in GDP per capita over the past decades and identify percentage changes for each region.

3. **Analyze GDP Growth Rates**
   - Identify regions with the highest and lowest average annual GDP growth rates from 1991 to 2023.
   - Investigate GDP growth recovery in regions post-2008 and 2020 economic downturns.

4. **Assess Economic Disparities Across Income Levels**
   - Explore disparities in economic growth between low-income and high-income regions.
   - Determine the percentage contribution of each income group to global GDP.


## Data Sources and Timeline
- **World Bank Database**: The dataset used in this project is sourced from the World Bank, containing a wide range of GDP and related economic indicators. The dataset spans from the year **1991 to 2023**, allowing for a thorough examination of recent global economic trends.

## Tools
- **Excel**: used for initial cleaning and organisation of data
- **Python**: Used for data analysis and visualization with the following libraries:
  - `Pandas`: For data manipulation and analysis.
  - `Numpy`: For numerical computations.
  - `Plotly`: For interactive visualizations.
  - `Seaborn` and `Matplotlib`: For static visualizations.
- **Jupyter Notebook**: The project was carried out in a Jupyter Notebook to allow easy, interactive exploration of the data and results.

![Screenshot (23)](https://github.com/user-attachments/assets/003a59a8-a9ef-41d7-b02b-e425eab1d15a)

## Project Workflow


### 1. Data Cleaning
- **Data Import**: The dataset is imported and stored in a Pandas DataFrame.
- **Handling Missing Data**: Missing values are  removed to maintain data quality.
- **Data Standardization**: Formats for GDP values, dates, and other numerical data are standardized for consistency.

### 2. Exploratory Data Analysis (EDA)
   - **Global GDP per Capita (PPP) Analysis**
     - Regional evaluation of GDP per capita (PPP) for each region in 2023.
     - Analysis of historical changes in GDP per capita over past decades.
   - **GDP Growth Rates Analysis**
     - Identification of regions with the highest and lowest average GDP growth rates.
     - Investigation of GDP growth recovery post-2008 and 2020 downturns.
     - Correlation study between GDP per capita growth and GDP growth across regions.
   - **Economic Disparities by Income Levels**
     - Assessment of economic disparities between low and high-income regions.
     - Calculation of global GDP contributions for each income group.
     - Evaluation of growth rates and projection analysis for income groups.


### 3. Correlation Analysis
- **Relationship Insights**: Correlation analysis was conducted to explore the relationships between GDP, GDP per capita, GDP growth rates, and other macroeconomic indicators.
- **Key Findings**: Significant correlations were highlighted to emphasize patterns and relationships between variables.

### 4. Data Visualization
- **Interactive Visualizations**: Plotly is used to create interactive charts for exploring regional GDP trends and disparities.
- **Static Visualizations**: Seaborn and Matplotlib generate bar charts, line plots, scatter plots, and heatmaps to clearly communicate findings.

## Insights and Recommendations

## Key Insights


1.  **Global GDP Concentration and Economic Disparities**
- **Regional Concentration**: Over **80% of the world’s GDP** comes from East Asia & Pacific, North America, and Europe & Central Asia. In contrast, regions like Latin America & Caribbean, Middle East & North Africa, and Sub-Saharan Africa contribute much less, showing clear **global economic imbalances**.
- **Income Level Disparities**: High-income regions make up **64.17%** of global GDP, while middle-income regions contribute **34.89%**. Low-income regions account for only **0.61%**, highlighting vast **economic gaps** among different income groups.
  
![gdp](https://github.com/user-attachments/assets/594e2515-bdf9-4c42-8055-680ab32bce21)



2. **GDP Growth Trends and Patterns**
- **2008 Financial Crisis Impact**: The 2008 financial crisis slowed GDP growth significantly in **2009**, particularly hurting trade-dependent regions like **Sub-Saharan Africa**.
- **2020 Pandemic Impact**: The **COVID-19 pandemic** led to another major economic slowdown in **2020**. However, regions like **Latin America & Caribbean**, the **Arab World**, and **Middle East & North Africa** rebounded well thanks to effective government support.
- **Post-Crisis Recovery**: **North America** had the strongest recovery after 2009 . Meanwhile, regions like **Africa Western and Central** faced challenges because of limited industrialization and lower foreign investment.

![newplot (4)](https://github.com/user-attachments/assets/a6b8781d-8150-43a5-9262-ee6640f89886)


3. **Regional Growth Rates**
- **Fast-Growing Regions**: **East Asia & Pacific** and **Africa Western and Central** achieved impressive GDP growth rates of **153.20%** and **130.24%** over the past three decades, indicating strong economic progress.
- **Slower-Growing Regions**: **Europe & Central Asia** and the **European Union** saw slower growth rates of **56.45%** and **53.26%**, partly due to economic downturns and the effects of the global financial crisis.

4. **Income Level Growth Patterns**
- **High-Income Regions**: Even though high-income regions have the largest GDP, they show the slowest growth rate of **2.07%**, which is typical for more developed economies.
- **Lower-middle-Income Regions**: Low-middle-income regions have the highest GDP growth Percentage Increase of **152.26%** over the past three decades, showing potential for rapid growth, but they still struggle to catch up with high-income countries.

![avg gdp income](https://github.com/user-attachments/assets/e77c913c-d869-43be-92ac-c1a2a0faa2a4)

 
5. **GDP Per Capita Differences**
- **High vs. Low-Income Disparities**: High-income countries have an average GDP per capita of around **45,584 USD**, while low-income countries average only **1,974 USD**. This significant difference makes it hard for low-income regions to close the gap.
  - It will take about **139.08 years** for low-income countries to reach the current GDP average of high-income countries.
  - Middle-income countries need approximately **45.40 years**, while upper middle-income countries have a shorter timeframe of **11.80 years** to reach current high-income levels. The economic gap remains substantial.

![newplot (6)](https://github.com/user-attachments/assets/febbf22d-7840-4858-abce-89a9da1c09bd)


## Recommendations
1. **Invest in Lower-Income Regions**: Focus on increasing foreign investment to support growth in lower-income areas.
2. **Encourage Economic Diversification**: Help regions with low income countries to diversify their economies for better resilience.
3. **Promote Technology Development**: Invest in technology and infrastructure in low-income regions to foster growth.


## Limitations

1. **Regional Classification**: The regions in this analysis were determined using the **World Bank database**, which does not categorize regions by continent. This may limit the ability to make continent-specific comparisons and insights.

2. **Data Availability**: Some key indicators that could enhance the analysis were unavailable. For instance, the **Gini coefficient**, which measures income inequality, and the **Human Development Index (HDI)**, which assesses overall human well-being, could not be included. The absence of these metrics limits the depth of the economic analysis.

3. **External Factors**: The analysis does not account for external factors such as political stability, natural disasters, or global market fluctuations that could influence GDP growth and economic disparities. These factors could provide a more comprehensive understanding of the economic landscape.

4. **Causation vs. Correlation**: While the analysis highlights trends and relationships between GDP growth and income levels, it does not establish causation. Further research is necessary to understand the underlying causes of observed economic patterns.


## Impact and Future Plans

This project has revealed important global economic trends and disparities. The insights gained will form a foundation for future efforts aimed at developing tailored strategies to boost economic growth in specific regions, especially those that are often overlooked.

I also plan to work with a team to create user-friendly dashboards that policymakers can use to monitor global economic performance. This will help ensure that data drives decisions that promote economic inclusion.

In the future, I may explore adding social and political indicators to better understand how governance and social policies affect economic development, particularly for young people and marginalized communities. Another potential extension of this project is to forecast future GDP trends using historical data, providing insights that can guide investment and policy decisions.


## References
- **World Bank Database**: The primary data source for economic indicators. [World Bank Database](https://databank.worldbank.org/source/world-development-indicators)
- **Pandas Documentation**: Official documentation for the Pandas library, used for data manipulation. [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)

## Contact Information
For inquiries or collaboration opportunities, please contact:

**Email**: satalisonn@gmail.com
