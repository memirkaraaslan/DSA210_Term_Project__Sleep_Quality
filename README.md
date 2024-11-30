# DSA210_Term_Project_32650
The relation between my daily activities and my sleep quality

# Daily Activities and Sleep Quality Analysis

## Overview
This project investigates the relationship between my daily activities and sleep quality. By collecting data on nutrition, exercise, hydration, screen time, mood, and sleep patterns using a combination of manual logs and wearable device data (Galaxy Watch), I aim to uncover insights about factors that influence my sleep.

---

## Motivation
Sleep quality is a cornerstone of overall health and well-being. By analyzing the impact of daily activities such as diet, exercise, and mental motivation, I hope to identify habits that improve or hinder my sleep. This project also provides an opportunity to apply data science techniques to personal health data, offering actionable insights for a healthier lifestyle.

---

## Data Collection
Data is collected daily from a combination of manual tracking and Galaxy Watch measurements. Key parameters include:

### **Daily Activity Parameters**
- **Nutritional Intake**: Carbohydrates, proteins, and fats (in grams).
- **Caffeine Consumption**: Total intake (in milligrams).
- **Hydration**: Water consumption (in liters).
- **Exercise**: Duration (in minutes) and type (e.g., cardio, strength).
- **Meal Timings**: Breakfast, lunch, and dinner times.
- **Screen Time**: Total phone screen usage (in hours).
- **Mood**: Self-rated dominant mood (e.g., Happy, Tired, Stressed).
- **Stress Level**: Average stress level (scale of 1-10).
- **Steps**: Total steps taken during the day.
- **Mental Motivation**: Self-assessed motivation level (scale of 1-10).
- **Work/Study Time**: Time spent on work, education, or study activities (in hours).
- **Sleep and Wake Times**: Daily sleep and wake-up times.

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
  - Presence (yes/no) and duration (if applicable)
- **Sleep Durations**:
  - Total sleep time (hours)
- **Device-Indicated Scores**:
  - Physical Recovery Rate
  - Rest Rate
  - Mental Recovery Rate
  - Sleep Cycle Efficiency

---

## Analysis Plan
1. **Exploratory Data Analysis (EDA)**:
   - Analyze correlations between daily activities and sleep quality metrics.
   - Identify trends using scatter plots, bar charts, and heatmaps.
2. **Feature Engineering**:
   - Combine and normalize collected data for deeper insights (e.g., calorie-to-exercise ratio, caffeine impact on REM sleep).
3. **Machine Learning**:
   - Use regression models to predict sleep quality.
   - Apply clustering to categorize days with similar activity and sleep patterns.
4. **Visualization**:
   - Create dashboards to visualize relationships between variables and their impact on sleep.

---

## Tools and Libraries
- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Wearable Device**: Galaxy Watch (for sleep quality and biometric data)
- **Jupyter Notebook**: For data analysis and visualization
- **GitHub**: For project tracking and collaboration

---

## Repository Structure
```plaintext
|-- data/
|   |-- daily_logs.csv         # Collected data (processed)
|-- notebooks/
|   |-- eda.ipynb              # Exploratory Data Analysis
|   |-- modeling.ipynb         # Modeling and Predictions
|-- README.md                  # Project overview and details
|-- requirements.txt           # Python dependencies

