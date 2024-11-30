# DSA210_Term_Project_32650
The relation between my daily activities and my sleep quality

# Daily Activities and Sleep Quality Analysis

## Overview
This project explores the relationship between my daily activities and my sleep quality. By analyzing factors such as dietary intake, caffeine consumption, exercise routines, and meal timings, I aim to uncover patterns and insights to improve my sleep quality and overall well-being.

---

## Motivation
Sleep is a critical component of physical and mental health. Understanding how my daily choices—such as nutrition, caffeine intake, and exercise—affect my sleep quality can help me make informed decisions for a healthier lifestyle. This project also provides a hands-on opportunity to apply data science techniques to real-life data.

---

## Data Collection
The data used in this project is collected manually on a daily basis and includes:
- **Nutritional Intake**: Carbohydrates, proteins, and fats (in grams).
- **Caffeine Consumption**: Total intake (in milligrams).
- **Exercise**: Duration (in minutes) and type (if applicable).
- **Meal Timings**: Breakfast, lunch, and dinner times.
- **Sleep Data**: Duration (in hours) and quality (rated on a scale of 1-5).

**Tools for Data Logging**: A simple spreadsheet application (e.g., Excel or Google Sheets) is used to log the data.

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

## Tools and Libraries
- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Jupyter Notebook**: For data exploration and analysis
- **GitHub**: For version control and project collaboration

---

## Findings
The insights derived from this project will include:
- How dietary habits (e.g., high-carb meals) impact sleep quality.
- The effect of caffeine consumption on sleep duration.
- Correlations between exercise routines and sleep improvement.
- An overall understanding of what activities promote better sleep.

---

## Limitations and Future Work
### Limitations:
- The dataset is self-reported, which may introduce bias.
- Limited to personal lifestyle habits and not generalizable to a larger population.

### Future Work:
- Automate data collection using wearable devices (e.g., smartwatches).
- Expand the dataset over a longer period for more robust insights.
- Compare with other individuals' data to generalize findings.

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
