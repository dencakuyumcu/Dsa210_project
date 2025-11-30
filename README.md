# Dsa210_project: Coffee Consumption and Sleep Quality Analysis
##  Overview
Understanding personal habits and lifestyle factors can provide valuable insights into daily energy levels and overall well-being. This project aims to analyze my personal coffee consumption and sleep patterns over the past few months, identifying correlations between coffee intake, sleep quality, and daily energy levels. The goal is to explore trends and develop a predictive model estimating sleep quality or energy levels based on coffee consumption.
##  Motivation
Coffee is a major part of my daily routine, and sleep is critical for productivity and health. I drink coffee almost every day, and I want to understand how daily coffee consumption affects my sleep quality and overall well-being. This project investigates whether higher coffee intake or specific timing of coffee consumption influences sleep duration and sleep quality ratings throughout the semester.
## Objectives
- Analyze daily coffee consumption and sleep patterns over several months.
- Identify factors influencing energy levels and sleep quality (like time of coffee intake, day of the week, academic workload, and weather conditions).
- Build a predictive model for sleep quality or energy level based on these factors.
- Apply data science techniques in personal data context.
## Research Questions
How do daily coffee consumption patterns and personal lifestyle habits, such as sleep schedule, academic workload, and daily routines, influence energy levels and overall well-being, and can these factors be used to better understand and predict daily productivity and alertness?
## Data Collection & Sources
The analysis is conducted using both personal data collected daily and additional influencing factors from external sources:

### Primary Data Source
I will collect my own daily data using Google Sheets or a CSV file.  
Each day, I will record:
- Daily coffee consumption (time, amount)
- Sleep patterns (bedtime, wake-up time, sleep duration, sleep quality)
- Daily energy level (self-reported, scale 1-5)
### External Influencing Factors
- Day of the week (weekend and weekday)
- Academic calender (exam days, assignment deadlines; collected from Sabancı University calendar)
- Weather conditions (precipitation from Weather API)
## Data Cleaning & Analysis Plan
The dataset will be processed before analysis.  
Cleaning and analysis steps will include:
- Checking for missing values and filling or removing them if necessary  
- Converting all units to a standard format (ml, hours, 1-5 scales)   
- Marking weekends, exam days, and stressful periods  
- Detecting unusual outliers in caffeine or sleep duration  
- Creating visual analyses such as correlations, scatter plots, and trend charts
## Modeling Approach
When enough data is collected, I will apply different models.  
Possible approaches include:
- Linear Regression for predicting sleep hours or quality  
- Logistic / Ordinal Regression for classifying sleep quality levels  
- Random Forest or Decision Tree for understanding influential factors  
- Optional: A simple time-series model for pattern prediction
Model results will be evaluated using metrics such as R², MSE, MAE, or accuracy.
### **Hypothesis 1: CoffeeAmount_ml → EnergyLevel**
**Null Hypothesis (H₀):**  
Coffee consumption does not significantly affect energy level.
**Alternative Hypothesis (H₁):**  
Coffee consumption has a statistically significant effect on energy level.
**Tests used:**  
- Pearson correlation (linear)  
- Spearman correlation (monotonic)

### **Hypothesis 2: SleepDuration_hr → EnergyLevel**
**Null Hypothesis (H₀):**  
Sleep duration does not significantly affect energy level.

**Alternative Hypothesis (H₁):**  
Sleep duration significantly affects energy level.

## Expected Outcomes
- Visualize how coffee intake and sleep are related
- Gain personal insight to improve my caffeine habits and sleep routine
- Build a prediction model for sleep quality or energy level
