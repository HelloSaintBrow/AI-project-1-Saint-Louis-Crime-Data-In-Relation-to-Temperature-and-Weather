# Top Five Crime Trends Analysis in St. Louis, MO (2021-2023)

This project uses Exploratory Data Analysis (EDA) to examine the top five crime trends in St. Louis, Missouri, from 2021 to 2023. We chose to focus on St. Louis due to its designation as the city with the highest crime rates in the United States, making its dataset particularly rich and insightful for analysis. The goal of this project is to analyze how crime has evolved over this period and answer key questions about its patterns. Specifically, the project will explore whether crime has increased or decreased, how it varies by season, and how different types of crime—such as violent, property, and drug-related offenses—have changed over time. Additionally, the analysis will investigate if crime trends differ by time of day and identify the time of year with the least amount of crime. By examining these factors, the project aims to provide a clearer understanding of crime trends in St. Louis and reveal where and when crime is most concentrated throughout the year.

Understanding crime trends is crucial for developing effective public safety strategies and policies, not only for St. Louis but for other cities as well. While St. Louis provides a particularly rich dataset, the methods and insights derived from this research can be applied to other cities facing similar challenges. By identifying patterns in crime by time of day, season, and type, cities can optimize resource allocation and focus public safety initiatives during peak crime periods. If certain seasons, like winter or summer, see higher crime rates, targeted prevention measures can be put in place. Additionally, understanding how crime trends evolve over time can help cities forecast and mitigate future crime spikes more effectively.

This research empowers authorities in cities of all sizes to take proactive steps in improving safety and quality of life, leveraging the lessons learned from St. Louis' experience.


![picture of Downtown St. Louis, MO with view of The Gateway Arch](stl.jpg)
Picture sourced from [Fodor's Travel](https://www.fodors.com/)


## Table of Contents:

1. [Key Questions](#key-questions)
2. [Project Objectives](#project-objectives)
3. [Research Approach](#research-approach)
4. [Datasets](#datasets)
5. [Tools and Libraries](#tools-and-libraries)
6. [Analysis and Conclusion](#analysis-and-conclusion)
7. [Next Steps](#next-steps)

### Key Questions:

1. **Has crime decreased or increased in St. Louis from 2021 to 2023?**
2. **Does crime peak by season of the year (winter, spring, summer, fall)?**
3. **How have different types of crime (e.g., violent, property, drug-related) increased or decreased?**
4. **Do crimes trend a certain way compared to the time of day?**
5. **What time of year has the least amount of crime?**

## Project Objectives

### 1. **Data Collection & Cleaning**

- Compile and preprocess datasets that include crime records (type, location, time) and seasonal data for St. Louis.
- Ensure data consistency and accuracy for effective analysis.

### 2. **Exploratory Data Analysis (EDA)**

- Summarize key characteristics of crime data to identify overall trends.
- Use visualizations and correlation analysis to uncover relationships between crime rates and seasonal factors.
- Investigate how different types of crime (violent, property, drug-related) have evolved over time.

### 3. **Time and Seasonal Analysis**

- Examine fluctuations in crime rates across different times of the day, days of the week, and seasons of the year.
- Identify any seasonal or temporal patterns in crime incidents, such as spikes in specific months or times.

### 4. **Crime Type Analysis**

- Analyze how specific types of crime have increased or decreased over the period.
- Identify if certain crimes tend to peak during specific seasons or times of day.

## Research Approach

A **descriptive analysis method** was used, involving the summarization of raw data to provide basic insights, such as averages, counts, and trends. This approach helps answer 'what happened' questions by examining the overall patterns and changes in crime over time.

## Datasets

### 1. **St. Louis Crime Data**

- **Description**: Records of reported crimes in St. Louis from 2021 to 2023 are included in this dataset, featuring details such as crime type, location, date, and time. It provides a comprehensive overview of crime trends across the city. Focus was placed on data fields reflecting the types of crimes, times of day crimes were committed, monthly crime rates, seasonal crime trends, and yearly data values, enabling a thorough exploration of how crime patterns have evolved over time.

- **Source**: [St. Louis Metropolitan Police Department](https://slmpd.org/stats/)

## Tools and Libraries

The following tools and libraries were used for analysis and development:

- **Python**: Programming language for data processing, analysis, and visualization.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computing and data manipulation.
- **Matplotlib**: Data visualization libraries for creating plots and charts.
- **Jupyter Notebooks**: For documenting and sharing the analysis process interactively.
- **Visual Studio Code**: Development environment used for coding, debugging, and project management.

## Analysis and Conclusion

The analysis of crime trends in St. Louis from 2021 to 2023 reveals several key findings that can inform law enforcement and city planning strategies for improving public safety.

1. **Overall Crime Trends**:  
   The year 2022 saw the highest number of crimes, indicating an upward trend in criminal activity over the period studied. This suggests that crime in St. Louis peaked in the second year of the study, though further investigation into specific crime types and seasonal factors may provide additional insights.

2. **Seasonal Crime Patterns**:  
   Crime rates were consistently highest during the summer months, with July emerging as the peak month for both 2021 and 2022. However, 2023 experienced a notable shift, with January reporting the highest crime rates for that year. This seasonal variation underscores the importance of targeted interventions during the summer months while also considering potential seasonal shifts in crime patterns, such as those observed in early 2023.

3. **Time of Day and Crime Type**:  
   Analysis of the time of day when crimes were committed showed that evenings, particularly between 6 PM and 9 PM, had the highest crime occurrence across the five crime types studied. This highlights the need for increased law enforcement presence during these peak hours. Conversely, the fewest crimes were committed at night, suggesting that crime activity tends to subside after late evening.

4. **Most Common Crimes**:  
   Car theft emerged as the most frequent crime type, suggesting a targeted area for prevention efforts. Property damage (1st Degree), on the other hand, occurred less frequently than other crime types, indicating that property damage may not be as widespread as other criminal activities.

5. **Winter Crime Trends**:  
   The winter months, particularly December through February, saw the fewest crime incidents across all types, which may reflect lower overall activity due to colder weather conditions. However, this should be carefully considered when planning resource allocation, as it does not necessarily imply the absence of criminal behavior, just a reduction in volume.

### Conclusion
The findings from this analysis provide critical insights into the patterns and distribution of crime in St. Louis. By understanding when and where crimes are most likely to occur—whether in summer months, evening hours, or specific crime types like car theft—city officials and law enforcement can better allocate resources to where they are most needed. Additionally, while seasonal trends suggest lower crime in winter, the peak months in the summer, especially July, should be a focus for preventative measures.

These insights offer a foundation for further predictive modeling, resource optimization, and policy recommendations aimed at reducing crime and improving public safety in St. Louis and similar cities.


## Next Steps

1. **Predictive Modeling**  
   Develop and test predictive models to forecast future crime trends based on historical data. This could help law enforcement anticipate potential crime spikes and allocate resources more effectively.

2. **Weather Impact Study**  
   Investigate the relationship between weather conditions (e.g., temperature, precipitation) and crime rates. Understanding whether specific weather patterns influence crime could help law enforcement plan for weather-related spikes in criminal activity.

3. **Policy Recommendations**  

    Based on the analysis, develop actionable recommendations for law enforcement, policymakers, and urban planners to reduce crime and improve public safety in St. Louis.
   
  ***
  
## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
