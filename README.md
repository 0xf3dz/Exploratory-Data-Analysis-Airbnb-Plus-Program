### README Description

**Exploring the Impact of Airbnb’s Plus Program on Platform Performance**  

This project presents a detailed analysis of the Airbnb Plus program, a premium accommodation initiative launched in 2018. Using a dataset of **14,605 observations** across **11 U.S. cities** and spanning **99 variables**, this study evaluates whether differentiating high-quality services improves platform performance. The analysis adopts a quantitative approach, employing descriptive statistics, hypothesis testing, and regression analysis to measure the program's effects.

#### **Key Components of the Analysis**

1. **Dataset Overview**:  
   - **Timeframe**: August 2017 (timeperiod = 8) to October 2019 (timeperiod = 34).  
   - **Geographic Scope**: Includes five Plus program cities (San Francisco, Denver, Nashville, New Orleans, Washington DC) and six non-Plus cities.  
   - **Performance Metrics**: 
     - **Primary**: Booking rate, total bookings, listing average review, and average booked nights.  
     - **Derived**: Variables for city names and date conversions to enhance temporal and geographic context.  

2. **Data Quality Assessment**:  
   - **Handling Missing Values**: Missing values (e.g., 1,374 for booking rate) were imputed using city-time period means, preserving temporal continuity and minimizing bias.  
   - **Outlier Treatment**: Outliers (e.g., reviews outside the 1-5 range) were carefully analyzed, with "0" values treated as missing data.  
   - **Integrity Checks**: Ensured no duplicate rows and validated complete timeline coverage for key cities.  

3. **Exploratory Data Analysis**:  
   - **Temporal Trends**: Mean booking rates and average reviews were plotted over time, highlighting shifts pre- and post-implementation of the Plus program.  
   - **Comparative Analysis**: Distinct patterns emerged, showing a **notable increase in booking rate (from ~0.24 to 0.26)** in San Francisco following the program's pilot introduction in February 2018. Other cities exhibited smaller or inconsistent improvements.  
   - **Key Insights**: Total bookings in San Francisco decreased despite improved booking rates, suggesting higher cancellations.

4. **Hypothesis Testing**:  
   - **Booking Rate**: A left-tailed t-test confirmed a statistically significant increase in booking rate post-implementation (t = -4.00, p < 0.001).  
   - **Customer Satisfaction**: Two-tailed t-tests on average reviews found no significant changes post-implementation in secondary cities (t = -0.73, p = 0.465).  
   - **Program Effectiveness**: Regression analysis showed an insignificant relationship between Plus program introduction and booking rates in non-pilot cities (β = -0.002, p > 0.05).  

#### **Conclusions**:  
The study concludes that:  
- **Booking Rate Improvement**: The Plus program significantly increased booking rates in San Francisco but had negligible effects in other cities.  
- **Customer Satisfaction**: Average reviews remained high but did not show statistically significant improvement post-implementation.  
- **Demographic and Seasonal Factors**: Variability in success suggests potential influences such as city size, economic factors, and seasonal timing.  

This analysis highlights the need for tailored strategies when scaling pilot initiatives and raises questions about broader demographic and market dynamics that influence program success.
