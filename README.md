# Pharma-appointments-eda
Medical appointments exploratory data analysis to find insights

## Objective
The objective of this EDA is to gain insights and understanding from the medical appointments dataset, focusing on patient appointments, attributes, and factors affecting appointment attendance.

## Data Description
The dataset contains the following columns:
- PatientId
- AppointmentID
- Gender
- ScheduledDay
- AppointmentDay
- Age
- Neighbourhood
- Scholarship
- Hipertension (Hypertension)
- Diabetes
- Alcoholism
- Handcap (Handicap)
- SMS_received
- No-show

## Data Preparation
1. Load the dataset into a Pandas DataFrame.
2. Check for missing values, duplicate entries, and data types.
3. Convert data types (e.g., ScheduledDay, AppointmentDay to datetime).

## Initial Exploration
1. Display a few rows of the dataset using `head()` to understand its structure.
2. Get basic information about the dataset using `info()`.

## Exploratory Data Analysis
1. **Demographics and Gender Distribution**
   - Calculate the distribution of gender using `value_counts()`.
   - Create a bar plot to visualize gender distribution.

2. **Age Distribution**
   - Plot a histogram to show the distribution of ages.

3. **Appointment Attendance**
   - Calculate the percentage of no-shows using `value_counts()`.
   - Visualize appointment attendance using a pie chart or bar plot.

4. **Scheduled vs. Appointment Day Analysis**
   - Calculate the time difference between ScheduledDay and AppointmentDay.
   - Analyze the distribution of time differences.

5. **Factors Affecting Attendance**
   - Explore how factors like Scholarship, Hypertension, Diabetes, Alcoholism, Handicap, and SMS_received relate to appointment attendance.

6. **Neighbourhood Analysis**
   - Analyze the distribution of appointments across different neighborhoods.
   - Identify neighborhoods with higher no-show rates.

## Data Visualization
1. Create visualizations using libraries like Matplotlib and Seaborn to support the analysis steps.

## Insights and Conclusion
Summarize the findings and insights obtained from the EDA, highlighting key takeaways related to appointment attendance and patient characteristics.

