Human vs Bot Traffic Analysis
 Project Overview
This project focuses on analyzing website traffic data to differentiate between human users and automated bot activity. The goal is to understand traffic behavior, detect anomalies, and generate actionable insights for improving website performance and security.

Data Source
Data was collected using the Cloudflare API, which provides real-time web traffic information.
Timestamp
Human Traffic (%)
Bot Traffic (%)

Data Processing
The raw data was enhanced by creating derived features:
Human_Traffic_Ratio
Bot_Traffic_Ratio
Traffic_Difference
Bot_Activity_Level (Low / Medium / High)
Traffic_Health_Status (Healthy / Risky)
Bot_Spike (Anomaly Indicator)
Bot_Change
Bot_Trend
Date, Time, Weekday

Exploratory Data Analysis (EDA)
Performed using:
df.info() → Data types
df.shape() → Dimensions
df.describe() → Statistical summary
Null value check

 Statistical Analysis
✔ Central Tendency
Mean, Median, Mode
Shows data concentration
✔ Measure of Spread
Variance
Standard Deviation
Shows data variability
✔ Measure of Shape
Skewness → Distribution symmetry
Kurtosis → Tail behavior


Visualization
🔹 Univariate Analysis
Human Traffic Distribution (Histogram + KDE)
Bot Trend Distribution (Bar Chart)
Bot Activity Level (Pie Chart)
🔹 Bivariate Analysis
Average Bot Traffic by Hour (Line Chart)
Human vs Bot Distribution (Violin + Box Plot)
Correlation Matrix (Heatmap)
Traffic Over Time (Subplots)
Human Traffic vs Bot Activity Level (Box Plot)
🔹 Multivariate Analysis
Traffic Health vs Weekday (Heatmap)
Human vs Bot by Weekday (Heatmap)
Bot Activity vs Hour (Box Plot)
Traffic Features Across Weekdays (Heatmap)

Key Insights
Human traffic is consistently dominant (~70%)
Bot traffic shows controlled fluctuations (~30%)
Strong negative correlation between human and bot traffic
Bot activity increases during nighttime
Traffic behavior is stable with minimal anomalies

Types of Analysis Performed
Descriptive → Understanding data
Diagnostic → Identifying relationships
Predictive → Estimating future trends
Prescriptive → Recommending actions

Recommendations
Monitor bot activity during peak hours
Implement security checks during high bot activity
Use anomaly detection for sudden spikes
Optimize server resources based on traffic patterns

Conclusion
This project demonstrates how data analytics techniques can be used to monitor and analyze web traffic effectively. By combining statistical analysis and visualization, it provides meaningful insights into human and bot behavior, helping improve website performance and security.
