# Sprint 06 - Games Dataset Analysis

## 📌 Project Overview
This project is part of the TripleTen Data Analytics Post Graduation (Sprint 06).  
The goal was to analyze the video games dataset (`games.csv`) to understand patterns in game sales, ratings, and platform performance. The analysis aimed to provide insights into trends across years, genres, publishers, and regions.

The tasks included data loading, cleaning, transformation, aggregation, visualization, and exploratory analysis.

## 🎯 Objective
Analyze global and regional video game sales, identify top-performing genres, platforms, and publishers, and explore trends over time.

## 📂 Dataset
**Files:**  
- `/datasets/games.csv`  

**Columns (examples):**  
- `Name`, `Platform`, `Year_of_Release`, `Genre`, `Publisher`, `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`, `Global_Sales`, `Critic_Score`, `Critic_Count`, `User_Score`, `User_Count`, `Rating`

## 📝 Steps

1. **Data Loading & Libraries**  
   - Loaded the dataset into a DataFrame.  
   - Imported Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`.

2. **Data Preprocessing**  
   - Checked for missing values and handled them (e.g., filling or dropping).  
   - Converted `Year_of_Release` to numeric.  
   - Standardized categorical variables (e.g., genre names, platform codes).  
   - Converted `User_Score` to numeric and handled exceptions like 'tbd'.

3. **Data Aggregation**  
   - Calculated total sales per platform, genre, and publisher.  
   - Aggregated sales by year to observe historical trends.  
   - Created regional summaries (NA, EU, JP, Other) and global totals.

4. **Exploratory Data Analysis (EDA)**  
   - Visualized distribution of global and regional sales using bar plots and histograms.  
   - Analyzed trends over time: which genres and platforms dominated which years.  
   - Examined correlation between critic scores, user scores, and sales.  
   - Identified top-selling games, genres, and publishers.

5. **Statistical Hypothesis Testing**
   - Tested whether sales differ significantly between genres, platforms, or regions.
   - Example tests:
     - Null hypothesis: mean sales are equal across genres.
     - Result: rejected null hypothesis → some genres have significantly higher sales.
   - Tested correlation between critic scores and sales to see if higher-rated games sell more.

6. **Insights & Patterns**  
   - Certain platforms (e.g., PS2, DS, Wii) dominated global sales in specific periods.  
   - Action and Sports genres generally had higher sales across regions.  
   - Positive correlation observed between Critic_Score and Global_Sales, while User_Score showed weaker correlation.  
   - Publisher performance varied, with some consistently producing high-selling games.

## 📊 Results
- Top-selling genres: Action, Sports, Shooter.  
- Leading platforms historically: PS2, DS, Wii, PS3.  
- Regional sales trends differ; e.g., Japan favors RPGs, NA favors Action/Sports.  
- Critic scores are a better predictor of sales than user scores.  
- Global sales peaked in mid-2000s and declined with emergence of mobile gaming.

## 🏁 Conclusion
- Sales trends are platform- and region-dependent.  
- Publishers can optimize releases targeting high-selling genres per region.  
- Critic reviews have a significant impact on sales, highlighting the importance of quality evaluation.  
- Historical data provides actionable insights for future game development and marketing strategies.

## 🛠 Tools & Technologies
- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## 🗂 Repository Structure
sprint-06-games/  
│  
├── README.md  
├── sprint-06-games.ipynb  
└── games.csv  

- `README.md` – Project documentation and overview  
- `sprint-06-games.ipynb` – Jupyter Notebook containing all tasks, EDA, and visualizations  
- CSV file – raw data used for analysis
