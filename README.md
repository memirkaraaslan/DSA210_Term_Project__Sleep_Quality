# DSA210_Term_Project__Sleep_Quality
The Relation Between My Daily Activities, Health Information, and My Sleep Quality

# Daily Activities and Sleep Quality Analysis

## Overview
This project explores the relationship between my daily activities and my sleep quality. By analyzing factors such as dietary intake, caffeine consumption, exercise routines, and meal timings, I aim to uncover patterns and insights to improve my sleep quality and overall well-being.

---

## Motivation
Sleep is a critical component of physical and mental health. Understanding how my daily choices—such as nutrition, caffeine intake, and exercise—affect my sleep quality can help me make informed decisions for a healthier lifestyle. This project also provides a hands-on opportunity to apply data science techniques to real-life data.

---

## Data Collection
Data is collected daily from a combination of manual tracking and Galaxy Watch measurements. Key parameters include:

### **Daily Activity Parameters**
- **Nutritional Intake**: Carbohydrates, proteins, and fats (in grams).
    - The nutritional intake is measured using the app "FatSecret" to calculate the correspondent calories of foods.
- **Caffeine Consumption**: Total intake (in milligrams).
    - The caffeine content of beverages is recorded based on information from the product packaging or reliable online databases, such as the USDA FoodData Central or other trusted nutrition websites.
- **Hydration**: Water consumption (in liters).
- **Exercise**: Presence (yes / no) and duration (in minutes) and type (e.g., cardio, strength).
- **Meal Timings**: Breakfast, lunch, and dinner times.
- **Screen Time**:
    - Total phone screen usage (in hours).
    - Total time spent with computer games (in hours).
- **Mood**: Self-rated dominant mood (e.g., Happy, Tired, Stressed).
- **Stress Level**: Average stress level (scale of 1-10), measured using Galaxy Watch.
- **Steps**: Total steps taken during the day.
- **Mental Motivation**: Self-assessed motivation level (scale of 1-10).
- **Work/Study Time**: Time spent on work, education, or study activities (in hours).
- **Social Time**: Time spent socializing, including activities such as meeting with friends, participating in extracurricular activities (e.g., student clubs), and spending quality time with family.
- **Sleep and Wake Times**: Daily sleep and wake-up times.
- Additional Parameters for Better Insights:
      - Weather conditions: Daily weather condition data collected from "The Weather Channel" and manual tracking.
          - Temperature: Average air temperature during the day measured in degrees Celsius (°C).
          - Humidity: Recorded as a percentage (%).
          - Weather Conditions: Described as sunny, rainy, cloudy, etc.
      - Body composition information: The information collected daily regarding body composition and ratios between;
          - Mass (kg) information for: Body (measured with a scale) , Skeletal muscle, Fat, Body water
          - Body analysis: Body fat percentage, BMI (Body Mass Index) calculated using mass informations

### **Sleep Quality Parameters**
Collected via Galaxy Watch:
- **Sleep Stages**:
  - Wake time (minutes)
  - REM sleep (minutes)
  - Light sleep (minutes)
  - Deep sleep (minutes)
- **Oxygen Levels**:
  - Minimum blood oxygen percentage during sleep
- **Temperature**:
  - Highest and lowest skin temperature during sleep
- **Heart Rate**:
  - Average, minimum, and maximum heart rates during sleep
- **Snoring Data**:
  - Presence (yes/no) and duration (if applicable).
  - Detected by the "Samsung Health" application installed on my smartphone.
- **Sleep Durations**:
  - Total sleep time (hours)
- **Device-Indicated Scores**:
  - Physical Recovery Rate
  - Rest Rate
  - Mental Recovery Rate
  - Sleep Cycle Efficiency

**Planned Tools for Data Logging**:
- Manual input into a spreadsheet application (e.g., Excel or Google Sheets).
- Galaxy Watch for biometric and sleep quality measurements.

**Note**: Data collection will begin shortly and is planned for a duration of 2-3 weeks.

---

## Analysis Plan
1. **Exploratory Data Analysis (EDA)**:
   - Identify trends in sleep quality with respect to different variables.
   - Visualize the data using scatter plots, bar charts, and heatmaps.

2. **Feature Engineering**:
   - Derive new features, such as total caloric intake or caffeine-to-sleep ratios.
   - Normalize and preprocess the data for modeling.

3. **Modeling**:
   - Use regression models to predict sleep quality based on daily activity metrics.
   - Perform clustering to group days with similar sleep patterns.

4. **Visualization**:
   - Create dashboards to illustrate findings and patterns clearly.

---

## Current Status
As of now, data collection and coding have not started. The following steps are planned:
1. **Data Collection**:
   - Daily logging of nutritional intake, exercise, caffeine consumption, and sleep metrics.
   - Syncing Galaxy Watch data for detailed sleep analysis (e.g., REM, deep sleep, heart rate).
2. **Exploratory Data Analysis**:
   - Initial analysis to identify potential correlations and trends.
3. **Implementation of Machine Learning**:
   - Develop models to predict sleep quality and identify key factors affecting it.

This README will be updated regularly as the project progresses.

---

## Tools and Libraries
The following tools and libraries will be utilized throughout the project as the coding and analysis phase progresses:
- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Jupyter Notebook**: For data exploration and analysis
- **GitHub**: For version control and project collaboration
- **Spreadsheet Software**: Excel or Google Sheets for data collection


### Sample Data
| Date       | Carbs (g) | Protein (g) | Fat (g) | Caffeine (mg) | Hydration (L) | Steps  | Mood       | Stress Level (1-10) | Mental Motivation (1-10) | Work/Study Time (hrs) | Social Time (hrs) | Screen Time (hrs) | Exercise (min) | Sleep Time | Wake Time | Sleep Duration (hrs) | Sleep Quality (1-10) | REM Sleep (min) | Deep Sleep (min) | Light Sleep (min) | Snoring (mins) | Body Weight (kg) | Skeletal Muscle (kg) | Body Fat (%) | Temperature (°C) | Humidity (%) |
|------------|-----------|-------------|---------|---------------|---------------|--------|------------|---------------------|---------------------------|-----------------------|-------------------|-------------------|----------------|-----------|-----------|----------------------|-----------------------|-----------------|------------------|------------------|----------------|-----------------|----------------------|---------------|------------------|---------------|
| 2024-01-01 | 200       | 80          | 60      | 150           | 2.0           | 8000   | Happy      | 3                   | 9                         | 5.0                   | 2.0               | 4.5               | 30             | 23:00     | 07:00     | 8.0                  | 8                     | 90              | 60               | 250              | 0              | 70.0            | 30.0                 | 18.0          | 25.0             | 60            |
| 2024-01-02 | 180       | 90          | 50      | 120           | 1.8           | 10000  | Stressed   | 5                   | 7                         | 4.5                   | 1.5               | 5.0               | 20             | 23:30     | 06:30     | 7.0                  | 7                     | 85              | 50               | 260              | 5              | 69.5            | 29.8                 | 17.5          | 22.0             | 55            |
| 2024-01-03 | 250       | 100         | 70      | 200           | 2.5           | 12000  | Relaxed    | 2                   | 10                        | 6.0                   | 2.5               | 3.0               | 40             | 22:30     | 06:00     | 7.5                  | 9                     | 100             | 70               | 230              | 2              | 71.0            | 31.0                 | 19.0          | 20.0             | 65            |


---



## Findings
The insights derived from this project are expected to include:
- The impact of dietary habits (e.g., high-carb vs. high-protein meals) on specific sleep stages such as REM or deep sleep.
- The effect of caffeine consumption on sleep duration, quality, and recovery rates (physical, mental, and restfulness scores).
- The relationship between hydration levels and biometric sleep parameters such as heart rate, blood oxygen levels, and skin temperature.
- Correlations between exercise routines (e.g., intensity, duration) and sleep improvement, particularly in physical recovery metrics.
- How external factors like screen time, stress levels, and mood influence sleep stages and overall restfulness.
- Patterns observed in sleep cycles (e.g., how consistent wake-up and bedtimes contribute to better sleep quality).
- Insights into the role of environmental factors such as weather conditions on sleep efficiency.
- An overall understanding of what combinations of daily activities (e.g., exercise, meal timings, and mental motivation) promote the best sleep outcomes.

---

## Limitations and Future Work
### Limitations:
- **Self-Reported Data**: Daily activity logs (e.g., nutrition, screen time, stress) are manually recorded and may contain biases or inaccuracies.
- **Device Accuracy**: While Galaxy Watch provides detailed sleep and biometric data, its measurements are limited by the precision and reliability of the device.
- **Individual Scope**: The analysis is limited to my personal lifestyle and may not generalize to a wider population.
- **Short Observation Period**: The dataset may not cover a sufficient time period to identify long-term patterns and trends.

### Possible Improvements:
- **Enhanced Data Collection**:
  - Develop or use an automated logging system that integrates wearable device data with external APIs (e.g., weather or stress tracking apps).
  - Incorporate additional metrics such as daily caloric intake or detailed exercise intensity levels using fitness trackers.
- **Longer Study Period**: Extend the data collection over several months or even a year to observe seasonal and long-term trends.
- **Comparative Analysis**: Compare my data with anonymized datasets from other individuals to identify broader patterns and validate findings.
- **Advanced Modeling Techniques**:
  - Utilize time-series analysis to predict sleep quality based on historical data.
  - Apply clustering techniques to categorize "high-quality sleep days" vs. "low-quality sleep days" and analyze contributing factors.
- **Visualization and Dashboards**:
  - Create an interactive dashboard to visualize relationships between variables and allow for scenario testing (e.g., "How does skipping caffeine impact sleep quality?").
- **Environmental Data**:
  - Integrate weather API data (temperature, humidity, air quality) to explore correlations with sleep metrics like deep sleep duration or physical recovery.
- **Public Sharing**:
  - Share findings through a user-friendly web application or generalizable sleep-quality improvement framework.
  - Publish a report or blog post summarizing the key insights and actionable recommendations for others.

---

## Repository Structure in Progress
```plaintext
|-- data/
|   |-- daily_logs.csv         # Collected data (processed)
|-- notebooks/
|   |-- eda.ipynb              # Exploratory Data Analysis
|   |-- modeling.ipynb         # Modeling and Predictions
|-- README.md                  # Project overview and details
|-- requirements.txt           # Python dependencies
