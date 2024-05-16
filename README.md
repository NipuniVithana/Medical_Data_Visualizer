# Medical Data Visualizer

This project visualizes and performs calculations on medical examination data using matplotlib, seaborn, and pandas. The dataset contains information collected during medical examinations, with rows representing patients and columns representing body measurements, blood test results, and lifestyle choices. The main goal is to explore the relationship between cardiovascular disease, body measurements, blood markers, and lifestyle choices.

## Dataset Description

The dataset (`medical_examination.csv`) includes the following features:

- **Age**: Age of the patient in days.
- **Height**: Height of the patient in centimeters.
- **Weight**: Weight of the patient in kilograms.
- **Gender**: Gender of the patient (categorical code).
- **Systolic Blood Pressure**: The higher number in a blood pressure reading (mmHg).
- **Diastolic Blood Pressure**: The lower number in a blood pressure reading (mmHg).
- **Cholesterol**: Level of cholesterol in the blood (1: normal, 2: above normal, 3: well above normal).
- **Glucose**: Level of glucose in the blood (1: normal, 2: above normal, 3: well above normal).
- **Smoking**: Whether the patient smokes or not (binary).
- **Alcohol Intake**: Whether the patient consumes alcohol or not (binary).
- **Physical Activity**: Whether the patient is physically active or not (binary).
- **Cardiovascular Disease**: Presence or absence of cardiovascular disease (binary).

## Tasks

The tasks performed in this project include:

1. Adding an "overweight" column to the data to identify overweight patients.
2. Normalizing the data by converting cholesterol and glucose values to binary (0 for good, 1 for bad).
3. Drawing a categorical plot to visualize the counts of categorical features split by cardiovascular disease status.
4. Cleaning the data by filtering out incorrect patient segments.
5. Creating a correlation matrix and plotting it as a heatmap.

## catplot
![catplot](https://github.com/NipuniVithana/Medical_Data_Visualizer/assets/99274261/0569dfea-a3b3-4d97-a771-1d925614163d)

## heatmap
![heatmap](https://github.com/NipuniVithana/Medical_Data_Visualizer/assets/99274261/9d492408-0c17-401c-907d-d69a88baeaad)
