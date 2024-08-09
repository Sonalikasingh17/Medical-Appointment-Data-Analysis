# Medical Appointment Data Analysis

This project investigates the factors influencing no-shows in medical appointments using a dataset of 110,527 medical appointments and 14 associated variables.

## Project Overview

The primary objectives of this analysis are to:
- Determine the percentage of no-shows.
- Identify important factors that predict whether a patient will show up for their appointment.
- Analyze the relationship between various attributes (e.g., gender, age, scholarship status) and appointment attendance.

## Dataset

The dataset includes the following variables:
- `PatientId`: Unique identifier for each patient.
- `AppointmentID`: Unique identifier for each appointment.
- `Gender`: Gender of the patient.
- `ScheduledDay`: The day the appointment was scheduled.
- `AppointmentDay`: The day of the actual appointment.
- `Age`: Age of the patient.
- `Neighbourhood`: Location of the hospital.
- `Scholarship`: Whether the patient is enrolled in the welfare program.
- `Hypertension`: Whether the patient has hypertension.
- `Diabetes`: Whether the patient has diabetes.
- `Alcoholism`: Whether the patient is an alcoholic.
- `Handcap`: Whether the patient is handicapped.
- `SMS_received`: Whether the patient received a reminder SMS.
- `No-show`: Whether the patient showed up for the appointment.

## Data Analysis

- **Percentage of No-Shows**: 20.19% of patients did not show up for their appointments.
- **Gender Influence**: Females are nearly twice as likely to miss their appointments compared to males.
- **Scholarship Status**: Patients with scholarships are more likely to miss their appointments.
- **SMS Reminders**: Surprisingly, patients who received an SMS reminder were more likely to miss their appointments.
- **Time Difference**: The longer the period between scheduling and the appointment, the more likely the patient is to miss the appointment.
- **Age Factor**: Younger patients are more likely to miss their appointments.

## Conclusion

The analysis reveals several interesting findings, including the impact of gender, scholarship status, and SMS reminders on appointment attendance. However, the dataset has some limitations, such as missing time details and potential data inconsistencies.

## Authors

- Mostafa Abdelaleem
- Mridul Bhandari

## Disclaimer

I made this repository as a reference. Please do not copy paste the solution as is.
