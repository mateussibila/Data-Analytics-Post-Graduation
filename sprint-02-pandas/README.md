# 🐼 Sprint 02 - Pandas

## 📌 Project Overview
This project is part of the TripleTen Data Analytics Post Graduation (Sprint 02).  
The main goal was to practice data manipulation and analysis using Python and pandas, focusing on cleaning and exploring a small music streaming dataset.

The tasks included examining the dataset for missing or inconsistent values, normalizing column names, handling explicit and implicit duplicates, filling missing data, and performing group-based analysis to test a hypothesis about user activity across different days and cities.

## 🎯 Objective
Test whether user activity differs by day of the week and city (Springfield vs Shelbyville).

## 📂 Dataset
**File:** `/datasets/music_project_en.csv`  
**Columns:** `userID`, `Track`, `artist`, `genre`, `City`, `time`, `Day`.

## 📝 Steps

1. **Data Overview**  
   - Checked column types and missing values.  
   - Observed inconsistencies in headers.

2. **Data Preprocessing**  
   - Normalized column names (`snake_case`).  
   - Filled missing values in `track`, `artist`, `genre` with `'unknown'`.  
   - Removed explicit duplicates and corrected implicit duplicates in `genre`.

3. **Hypothesis Testing**  
   - Counted tracks per city and per day.  
   - Created function `number_tracks(day, city)` to filter and count tracks.  
   - Observed activity patterns for Monday, Wednesday, and Friday.

## 📊 Results
- Springfield has higher overall activity.  
- Springfield drops on Wednesday; Shelbyville increases on Wednesday.  
- Differences suggest user activity depends on day and city.

## 🏁 Conclusion
The hypothesis that user activity differs by day and city is partially supported.  
Analysis is limited to three days, so results are indicative but not definitive.

## 🛠 Tools & Technologies
- Python 3.x  
- Pandas  
- Jupyter Notebook  

## 🗂 Repository Structure
sprint-02-pandas/  
│  
├── README.md  
└── sprint-02-pandas.ipynb  

README.md – Project documentation and overview
sprint-02-pandas.ipynb – Jupyter Notebook containing all tasks and solutions

## 📄 License
This project is licensed under the MIT License.
