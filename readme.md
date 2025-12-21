# AIAttendance — CSCE580 Fall 2025

## Overview
This repository contains the project for analyzing attendance data for **CSCE580**.  
The project focuses on anonymizing attendance-related data and performing analysis using Jupyter notebooks, while ensuring data privacy.

## Repository Structure

AIAttendance-csce580fall2025/
│
├── data/
│ ├── anonymized_output # Anonymized student data (contain .xlsx files)
│ └── combined_classes.xlsx # Combined Excel file of all 26 class sheets
│
├── code/
│ ├── AIAttendance.ipynb # Main Jupyter notebook for analysis
│ └── anonymize_data.ipynb # Notebook for anonymizing original data
│
└── README.md # This file

## Usage

1. Install dependencies (if needed)

    pip install pandas numpy matplotlib openpyxl

2. Run the notebooks in order:

- Execute code/anonymize_data.ipynb to anonymize the original attendance data
- Use the anonymized Excel files in data/anonymized_studentData/
- Run code/AIAttendance.ipynb for attendance analysis and visualization


##  Notebooks Description

### 1. `anonymize_data.ipynb`
- Reads raw data containing personal identifiers
- Replaces sensitive fields (e.g., names, usernames) with anonymized values
- Outputs anonymized data in a structured format
- Ensures consistency across records while preserving privacy

### 2. `AIAttendance.ipynb`
- Uses the anonymized dataset for attendance or analytics-related processing
- Performs data cleaning and transformations as required
- Designed to work only with anonymized data (no raw personal data)


## Outputs

- 27 anonymized Excel files generated from attendance images
- combined_classes.xlsx containing all 26 class sheets combined
- Attendance analysis results and visualizations in AIAttendance.ipynb


##  Data Privacy

- No real or sensitive personal data is exposed in this repository
- All files in the data/ folder contain anonymized information only
- The original (raw) data is **not** included or published



