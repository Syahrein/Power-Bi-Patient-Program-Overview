# Power BI Dashboard - Patient Program Dashboard

## Overview
This Power BI report is designed to monitor and visualize key metrics for the **Patient Program**. It tracks patient demographic information, engagement, interactions, and educational usage across various stages of the program. The dashboard consists of seven main pages, each providing unique insights into different aspects of the program, helping healthcare providers improve patient outcomes, monitor trends, and optimize the overall effectiveness of the program.

The insights derived from this report enable data analysts and program managers to identify bottlenecks, track program progress, and offer actionable recommendations for patient engagement and operational efficiency improvements.

## Dashboard Pages

### 1. **Overview Page**
The **Overview** page provides a high-level summary of patient demographics, including enrollment data, treatment types, gender breakdown, age distribution, and more. It also shows the growth of patient enrollments over time in the CRM and app platforms.

![1 Overview (clean)](https://github.com/user-attachments/assets/574c4068-0dd0-4379-a748-b5c0b9d174dc)

#### Key Metrics:
- Total Patients Enrolled: 9444
- Gender Breakdown: 3655 Male, 4813 Female
- Average Patient Age: 54.95 years
- Starting Dosage Breakdown: Various pen types with starting dosages tracked across the enrolled patient base.
- Age Distribution: Visual breakdown of patient age categories for CRM and App users.

### 2. **DNE Interactions Page**
The **DNE (Diabetes Nurse Educator) Interactions** page tracks the interactions between DNEs and patients, highlighting the types of meetings and the frequency of engagement. It also shows how patient interactions are distributed across genders, platforms, and topics discussed during meetings.

![2 DNE Interaction (clean)](https://github.com/user-attachments/assets/8a2a47f1-03a0-4c52-b0c8-7d774dcaa394)

#### Key Metrics:
- Total Calls: 42,523
- Average Call Duration: 12.2 minutes
- Total Face-to-Face Meetings: 2,047
- Interaction Patterns: Shows engagement trends by day of the week and month, helping DNEs optimize their schedules.

### 3. **Patient Trends Page**
The **Patient Trends** page tracks key health metrics, including fasting plasma glucose (FPG), postprandial glucose (PPG), and HbA1c readings, over time. This page also analyzes dosage changes and the number of medication logs per patient.

![3 Patient Trends (clean)](https://github.com/user-attachments/assets/ac7b2e84-1674-4446-a14d-f376595a1a67)

#### Key Insights:
- Dosage Change Over Time: Tracks average dosage changes for various pen types.
- FPG/PPG/HbA1c Readings: Visualized trends of key health metrics categorized by the duration of patient enrollment.
- Number of Patients Processed: 214 patients with dosage change logs.

### 4. **App/DP Usage Page**
The **App/DP Usage** page analyzes patient interactions with the Company's app and doctor portal (DP). It provides insights into the types of logs entered by patients (e.g., blood sugar, medication) and the demographics of app users, broken down by age, gender, and treatment phases.

![4 App DP Usage (clean)](https://github.com/user-attachments/assets/49ed1d13-6b97-48f2-aab4-8d3b4ed7ea10)

#### Key Features:
- Number of App Logs: 35.22K total logs, broken down by blood sugar, medication, and HbA1c.
- App Loggers by Gender: 1108 male, 1540 female.
- DNE Usage of Doctor Portal: Tracks the number of patients linked to DNEs through the portal.

### 5. **Education Module Usage Page**
The **Education Module Usage** page focuses on tracking patient engagement with educational materials, showing the frequency with which patients access various modules. This helps in understanding which topics are most useful or relevant to patients.

![5 Education Module Usage (clean)](https://github.com/user-attachments/assets/5ba12386-d956-4abc-9435-3572d46d8ca1)

#### Key Metrics:
- Most Accessed Modules: "How to Inject Lantus" (660 views), "Diabetes Patient Manual" (460 views).
- Topics Covered: Includes a variety of educational topics like carbohydrate counting, diabetes myths, and managing blood glucose.

### 6. **Patient Drop-Offs Page**
The **Patient Drop-Offs** page analyzes patient attrition, providing insights into the reasons why patients drop off from the program. This page helps program managers identify areas for improvement in patient engagement and retention.

![6 Patient Drop-Offs (clean)](https://github.com/user-attachments/assets/5e918bb0-9f6e-4174-b077-6c99036b0254)

#### Key Insights:
- Total Drop-Offs: 1,572 confirmed Phase 2 drop-offs.
- Drop-Off Reasons: Includes reasons such as "Patient Uncontactable" and "Stopped using Pen."
- Duration in Program: Tracks how long patients remained enrolled before dropping off.

### 7. **E-Enrollment Page**
The **E-Enrollment** page tracks the progress of patient enrollments in the program, showing key statistics on total enrollments, failures, and doctor endorsements. This page helps monitor the efficiency of the enrollment process.

![7 E-Enrollment (clean)](https://github.com/user-attachments/assets/a445867a-d5e0-4306-bcf2-8c4e237777fd)

#### Key Metrics:
- Total Endorsed Patients: 6,565
- Enrollment Failures: 192 failures due to reasons like "Patient Uncontactable."
- Doctor Endorsements: Tracks the number of endorsements by each doctor and the time since their last endorsement.

## Technologies Used
- **Data Source:** Patient and program data sourced from internal CRM systems.
- **SQL:** Used to extract relevant data for use in Power BI.
- **Power BI:** For creating dynamic, interactive visualizations and reports.
- **DAX (Data Analysis Expressions):** Used to create custom measures and enhance the interactivity of the dashboard.
- **Visualization Types:** Includes bar charts, pie charts, line graphs, and summary tables.

## Contact Information
Feel free to reach out if you have any questions or would like to discuss the insights from this dashboard:
- **Email:** syahrein01@gmail.com
- **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/syahrein/)
