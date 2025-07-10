# 📊 Bellabeat Case Study – Python Data Analysis

## 🔍 Overview

This project analyzes Fitbit wearable device data to understand the relationship between physical activity, sleep duration, and user engagement. The goal is to generate actionable insights and recommendations to help improve user experience and health outcomes via the Bellabeat app.

---

## 📁 Dataset

The dataset is sourced from [FitBit Fitness Tracker Data](https://www.kaggle.com/arashnic/fitbit) and contains information collected from 33 users over a span of up to 2 months.

**Key data categories:**
- Daily activity (steps, calories, distance)
- Sleep tracking (minutes asleep, time in bed)
- Usage patterns (number of active days, full-day usage)

---

## ⚙️ Tools & Libraries

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 🧪 Process

1. **Data Cleaning**
   - Removed nulls, duplicates, and inconsistent records
   - Standardized date formats and merged datasets

2. **Feature Engineering**
   - Created `SleepQuality` categories:
     - Less than 7h
     - 7–9h (recommended)
     - More than 9h
   - Created `ActivityLevel` categories based on step count
   - Calculated usage frequency (days used, full-day usage)

3. **Exploratory Data Analysis**
   - Visualized sleep vs. activity patterns
   - Segmented users by usage frequency
   - Examined engagement trends and behavior

---

## 📌 Key Insights

- **63% of users** take between 5,000–9,999 steps per day.
- Most users sleep between **5 and 9 hours**, regardless of activity level.
- Users with more than **10,000 steps/day** are more likely to get sufficient sleep.
- Only **31% of users** used the device on over 60% of available days.
- In just **47% of observations**, users wore the device the full day.

---

## 💡 Recommendations for Bellabeat App

- Send reminders to help users build better bedtime routines.
- Introduce rewards or badges for consistent device usage.
- Recommend personalized step goals based on user habits.
- Provide motivational content (e.g., health articles) in-app.
- Notify users at a set time daily to help create an exercise habit.