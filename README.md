**1\. Project Goals:**

This project aims to analyze energy consumption patterns and their relationship with production output in a steel manufacturing facility over the course of one year (2018). The primary goals are to:

*   **Understand Energy Consumption Profiles:** Identify trends, seasonality, and daily/weekly variations in electricity usage.
*   **Analyze Power Quality:** Investigate reactive power characteristics and power factor to assess electrical system efficiency.
*   **Evaluate Environmental Impact:** Quantify CO2 emissions associated with electricity consumption and identify potential areas for reduction.
*   **Assess Energy Intensity of Production:** Determine the amount of energy consumed per unit of steel produced and analyze its trends.
*   **Explore the Impact of Operational Factors:** Examine how factors like production levels and planned maintenance affect energy consumption.
*   **Develop Interactive Visualizations:** Create a dynamic Power BI report and dashboard to effectively communicate key findings and insights to stakeholders.

**2\. Datasets:**

This project utilizes two datasets:

*   **Primary Dataset: Steel Industry Energy Consumption Data:**
    
    *   **Source:** This data is gathered from DAEWOO Steel Co. Ltd in Gwangyang, South Korea. It produces several types of coils, steel plates, and iron plates. (dataset taken from https://www.kaggle.com/datasets/nimapourmoradi/steel-dataset) 
    *   **Timeframe:** January 1, 2018, to December 31, 2018.
    *   **Granularity:** Multiple timestamped records per day.
    *   **Key Columns:**
        *   `Date Time`: Timestamp of the energy reading.
        *   `Usage_kWh`: Electricity consumption in kilowatt-hours.
        *   `Lagging_Current_reactive_power_kVarh`: Lagging reactive power.
        *   `Leading_current_reactive_power_kVarh`: Leading reactive power.
        *   `Co2(tCo2)`: CO2 emissions in metric tons.
        *   `Lagging_current_power_factor`: Lagging power factor.
        *   `Leading_current_power_factor`: Leading power factor.
        *   `NSM`: Normalized Solar Energy.
        *   `WeekStatus`: Whether the day is a 'Weekday' or 'Weekend'.
        *   `Day_of_week`: The day of the week.
        *   `Load_Type`: Categorical variable indicating different types of electrical loads.
        *   `Electricity_Cost_USD_per_kWh`: Calculated electricity cost per kWh in USD.
    
*   **Secondary Dataset: Steel Production Output and Operational Data:**
    
    *   **Source:** Fictitious data simulating daily steel production and operational events.
    *   **Timeframe:** January 1, 2018, to December 31, 2018.
    *   **Granularity:** One record per day.
    *   **Key Columns:**
        *   `Date`: Date of production and operational data.
        *   `Total_Production_Tons`: Total tons of steel produced on that day.
        *   `Number_of_Production_Units_Active`: Number of production units active on that day.
        *   `Planned_Maintenance_Hours`: Number of hours of planned maintenance on that day.

**3\. Analytical Steps:**

The project will involve the following analytical steps using Power BI:

*   **Data Loading and Transformation:** Load both datasets into Power BI and ensure data types are correct.
*   **Data Modeling:** Establish a relationship between the two datasets using the `Date` column.
*   **Energy Consumption Analysis:**
    *   Calculate total and average daily/weekly/monthly energy consumption.
    *   Analyze energy consumption patterns by time of day, day of the week, and week status.
    *   Investigate trends and seasonality in energy consumption.
    *   Compare energy consumption across different load types.
*   **Power Quality Analysis:**
    *   Calculate total reactive power.
    *   Analyze trends in lagging and leading reactive power.
    *   Calculate overall power factor and identify periods of inefficiency.
*   **CO2 Emissions Analysis:**
    *   Analyze the trend of CO2 emissions over time.
    *   Explore the relationship between energy consumption and CO2 emissions.
    *   Compare CO2 emissions by load type and operational factors.
*   **Energy Intensity Analysis:**
    *   Calculate daily energy consumed per ton of steel produced.
    *   Analyze the trend of energy intensity over time and its correlation with production levels.
*   **Impact of Operational Factors:**
    *   Investigate how the number of active production units affects energy consumption.
    *   Analyze the impact of planned maintenance on energy consumption and production.
*   **Cost Analysis:**
    *   Calculate total and average daily/weekly/monthly electricity costs.
    *   Analyze the trend of electricity costs.
    *   Calculate the cost of energy per ton of steel produced.

**4\. Project Output:**

The primary output of this project will be an interactive Power BI report and a summary dashboard. These will provide insights into:

*   **Key Energy Consumption Metrics:** Total consumption, peak usage times, and variations.
*   **Power Quality Indicators:** Trends in reactive power and power factor.
*   **Environmental Performance:** CO2 emission patterns.
*   **Production Efficiency:** Energy and cost intensity of steel production.
*   **Operational Efficiency:** Impact of production levels and maintenance on energy use.
*   **Actionable Insights:** Identification of potential areas for energy optimization, cost reduction, and improved operational planning.

The Power BI report and dashboard will be designed to be dynamic and interactive, allowing users to explore the data at different levels of granularity and gain a deeper understanding of the energy and production dynamics within the steel manufacturing facility.

Below are the report pages and dashboards that cover the project output:

**2018 Energy and Production Overview:**
![Updated_page-0001](https://github.com/user-attachments/assets/caddf3c5-e770-4eda-bc50-beef393eb867)

**Energy Consumption Analysis:**
![Updated_page-0002](https://github.com/user-attachments/assets/fb623d64-4a22-4d30-8d87-6a2caa6fe974)

**Power Quality Analysis:**
![Updated_page-0003](https://github.com/user-attachments/assets/bba69b7f-8465-4b0a-9ce0-ec22446e35e5)

**Production and Energy Intensity Analysis:**
![Updated_page-0004](https://github.com/user-attachments/assets/8dd23aa4-9f51-401c-9aa2-7e2e9c006a45)

**Cost and Emission Analysis:**
![Updated_page-0005](https://github.com/user-attachments/assets/ad468638-144f-4573-afc4-8649fbcc9209)

**Executive Summary:**
![Executive Summary](https://github.com/user-attachments/assets/7dc19a21-de6d-4439-8632-d5f0bb410e2b)
