# Project--Sales-Data-Analysis

# Sales Data Analysis and Behavioral Insights

## Video Presentation: Click on this Link : https://drive.google.com/file/d/1C106oSp60fnWf133dz47xEEt5rtirxRf/view?usp=sharing

## Objectives

The project aims to answer the following questions:
1. **Plot daily sales for all 50 weeks.**  
   Visualize the overall trend to understand fluctuations over time.

2. **Detect a sudden change in daily sales.**  
   Identify the date on which a notable change occurs in the sales pattern.

3. **Assess the statistical significance of the change.**  
   Determine if the change is statistically significant and report the p-value.

4. **Examine gender influence on the sales change.**  
   Investigate whether the observed change in daily sales is linked to a shift in the proportion of male versus female customers, using visual plots as evidence.

5. **Compute sales percentage across different dayparts.**  
   Divide each day into four segments:
   - Night (12:00 AM - 6:00 AM)
   - Morning (6:00 AM - 12:00 PM)
   - Afternoon (12:00 PM - 6:00 PM)
   - Evening (6:00 PM - 12:00 AM)  
   Then calculate the percentage of total sales made during each daypart across the 50 weeks.



## Methodology and Analysis

### 1. Daily Sales Trends
- **What:** Plotted daily sales over 50 weeks to visualize fluctuations and overall trends.
- **How:** Utilized Python libraries (e.g., Pandas and Matplotlib) to generate time-series plots.
- **Outcome:** The plot revealed a distinct abrupt change in the sales trend.

### 2. Identifying Sudden Changes
- **What:** Determined the specific date when the sudden change in daily sales occurred.
- **How:** Examined the time-series graph and computed differences between consecutive days.
- **Outcome:** The sudden change was observed on **[29 April 2013]**.

### 3. Statistical Significance of Sales Change
- **What:** Tested if the change in daily sales on the identified date was statistically significant.
- **How:** Performed a statistical test (e.g., a t-test or change-point analysis) comparing sales before and after the change.
- **Outcome:** The p-value obtained was **[2.27287631770394e-149]**, indicating that the change is statistically significant.

### 4. Exploring Gender Proportions
- **What:** Investigated whether the sales change could be explained by a shift in the proportion of male versus female customers.
- **How:** Created visual plots (e.g., bar or pie charts) comparing gender proportions before and after the sudden change.
- **Outcome:** The plots suggest that **[the sudden increase in the sales is becuase of the increase in purchases made by both male and females.]**.

### 5. Sales Distribution by Dayparts
- **What:** Calculated the percentage of sales in each daypart (night, morning, afternoon, evening) over the 50 weeks.
- **How:** Divided each day into the four specified segments and computed the sales percentages using aggregation functions in Pandas.
- **Outcome:** The overall distribution of sales by daypart was:  
  - Night: **[8.95%]**  
  - Morning: **[30.76%]**  
  - Afternoon: **[39.41%]**  
  - Evening: **[20.85%]**
