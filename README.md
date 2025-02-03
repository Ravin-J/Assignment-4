Data Analysis- Building Energy Benchmarking Data: Summary Report

The purpose of this report is to present an in-depth analysis of the City of Calgary’s Building Energy Benchmarking dataset. The analysis focuses on identifying key trends in energy consumption, greenhouse gas emissions, and efficiency across various property types. Additionally, the report examines correlations between energy usage, emissions, and property size to provide insights into energy management practices.

Key Trends in Energy Consumption and Emissions

An initial review of the Property Gross Floor Area (GFA) data reveals that the mean (4,753 m²) is significantly higher than the median (1,807 m²), indicating a right-skewed distribution. This suggests that a small number of large properties are inflating the average. Similarly, Site Energy Use shows a mean of 8,266 GJ, while the maximum value exceeds 243,000 GJ which shows that there are significant outliers. 
The Total GHG Emissions column displays a wide range, from 15 to 13,067 metric tons of CO2e, indicating substantial variation among properties. Notably, the Direct GHG Emissions column includes minimum values of zero, likely attributable to properties powered by clean energy sources. Conversely, some properties exhibit exceptionally high emissions, possibly due to reliance on fossil fuels, such as coal. Both Electricity Use and Natural Gas Use data reveal extreme outliers, with maximum values far exceeding the mean, pointing to a minority of properties with exceptionally high energy demands.

Energy Use Intensity and Property Type Variations

The analysis indicates that Energy Use Intensity (EUI) is highest for Fitness Centers/Health Clubs/Gyms, likely due to significant heating and cooling requirements driven by large HVAC systems. Additionally, Total GHG Emissions by year show a notable decline in 2019, which can be attributed to the COVID-19 pandemic. This decline reflects reduced occupancy and operational activities in public buildings during lockdown periods. Looking at the graph below, you can see the decline present during the Covid years. 

Observations on Specific Buildings

Examining individual properties, the Water Center emerges as the top GHG emitter, while the Killarney Aquatic and Recreation Center records the lowest emissions. 
In terms of Total Energy Usage, fire stations lead, followed by fitness centers and office buildings. The high energy consumption in fitness centers is likely due to intensive heating during winter and cooling in summer, which requires large HVAC operation and energy.
 
Correlation Analysis

A correlation matrix was utilized to explore relationships between Site Energy Use, Total GHG Emissions, and Property Size. Key findings include:

•	Site Energy Use and Property Size: Strong positive correlation (0.7259), indicating that larger buildings tend to consume more energy.
•	Site Energy Use and Total GHG Emissions: Weak correlation (0.187), suggesting that energy consumption does not directly translate to higher emissions, likely due to variations in energy sources and efficiency practices.
•	Total GHG Emissions and Property Size: Weak correlation (0.1708), reflecting that larger buildings do not necessarily emit more GHGs, possibly due to operational efficiencies or the use of cleaner energy.

These correlations highlight that while building size significantly influences energy consumption, factors such as energy efficiency measures and renewable energy adoption play critical roles in determining emissions levels.

Recommendations

Based on the analysis, the following recommendations are proposed to enhance energy efficiency and reduce emissions:
1.	Standardize Energy Audits: Improve data collection practices to address gaps, several columns had missing values. 
2.	Retrofit Older Buildings: Implement energy-efficient technologies, such as modern HVAC systems, LED lighting, and improved insulation.
3.	Optimize Seasonal Energy Management: Adjust energy strategies to account for seasonal variations in demand.
4.	Promote Renewable Energy: Encourage the integration of onsite renewable energy systems to reduce dependency on fossil fuels.

Data Cleaning and Methodology

Regular expressions (regex) were instrumental in data cleaning, particularly for numerical fields like Natural Gas Use (GJ) and Weather Normalized Source Energy Use (GJ). Regex was used to remove non-numeric characters (e.g., commas) to facilitate accurate data conversion and analysis. This step ensured the reliability of statistical calculations and supported effective handling of missing data.


Conclusion

This report provides a comprehensive overview of energy consumption patterns, property-specific trends, and correlations within the City of Calgary’s Building Energy Benchmarking dataset. The insights derived from the analysis will allow city officials to better understand how to make changes to the energy market. 
