# Hospital Patient Analysis Dashboard

## Project Overview

The **Hospital Patient Analysis Dashboard** is an interactive data visualization project developed using Microsoft Power BI. It analyzes patient records to provide insights into patient demographics, treatment costs, hospital stays, readmissions, patient outcomes, and satisfaction.

The dashboard combines DAX measures, KPI cards, interactive slicers, and multiple chart types in a single-page report to make the data easier to explore and understand.

## Objectives

- Analyze patient demographics and medical conditions.
- Monitor total patient records and recorded treatment costs.
- Evaluate average length of stay and readmission rates.
- Understand patient outcomes and satisfaction levels.
- Build an interactive dashboard using Power BI visualizations and DAX.
- Publish the report to Power BI Service.

## Technologies Used

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Power BI Service
- CSV dataset

## Dataset

The dataset includes the following fields:

- Patient ID
- Age
- Gender
- Condition
- Procedure
- Cost
- Length of Stay
- Readmission
- Outcome
- Satisfaction

The dataset is used for educational and analytical purposes. Results represent the supplied records and should not be interpreted as real-time hospital statistics.

## Dashboard Features

- KPI cards for total patients, total cost, average patient cost, average length of stay, readmission rate, and average satisfaction.
- Interactive slicers for gender, condition, outcome, and readmission.
- Patient distribution and outcome analysis.
- Cost analysis by medical condition.
- Readmission analysis.
- Age-group analysis.
- Satisfaction and length-of-stay analysis.
- DAX-based calculations and interactive filtering.

## DAX Measures

The project uses DAX measures to calculate metrics such as:

- Total Patients
- Total Patient Cost
- Average Patient Cost
- Average Length of Stay
- Readmitted Patients
- Readmission Rate
- Recovered Patients
- Recovery Rate
- Average Satisfaction

## Project Structure

```text
hospital-patient-analysis-dashboard/
├── README.md
├── Dataset/
│   └── hospital data analysis.csv
└── PowerBI/
    ├── HospitalDashboard.pbip
    ├── HospitalDashboard.Report/
    └── HospitalDashboard.SemanticModel/
```

The folder and file names above are examples. The actual structure depends on the files included in the project.

## How to Use

1. Download or clone this repository.
2. Open the `.pbip` project file using a compatible version of Power BI Desktop.
3. If required, update the dataset source path in Power Query.
4. Refresh the data.
5. Explore the dashboard using the slicers and visualizations.

## Publishing

The report can be published to Power BI Service, subject to account, workspace, and sharing permissions.

## Disclaimer

This project is intended for educational and analytical purposes. The dataset and dashboard do not provide medical advice and should not be used to make clinical decisions.

## Author

Created as a Power BI data analytics project.
