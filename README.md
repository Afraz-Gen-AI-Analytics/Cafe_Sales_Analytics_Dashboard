# Cafe Sales Data Analysis, Prediction, and Interactive Power BI Dashboard

## Project Description
This project demonstrates a complete **end-to-end data analytics and machine learning workflow** using a real-world cafe sales dataset. The dataset was initially sourced from Kaggle in a raw and unstructured format (`dirty_cafe_sales.csv`) and underwent extensive cleaning, transformation, and analysis to produce actionable insights and a professional Power BI dashboard.

The work was completed in three main phases:
1. **Data Cleaning & Preprocessing (Python)**
2. **Exploratory Data Analysis (EDA) & Machine Learning (Python)**
3. **Interactive Dashboard Development (Power BI)**

---

## Phase 1 – Data Cleaning & Preprocessing

- **Dataset Source:** Kaggle (`dirty_cafe_sales.csv`)  
- **Data Size:** 10,000 rows × 8 columns  
- **Issues in Raw Data:**
  - Missing values in `Item`, `Quantity`, `Price Per Unit`, `Total Spent`, `Payment Method`, `Location`, and `Transaction Date`.
  - Inconsistent formatting for categorical values (e.g., “UNKNOWN”, “In-store”, “In-Store”).
  - Erroneous numeric entries such as `"ERROR"` in `Price Per Unit`.
  - Duplicate transaction dates preventing proper data modeling.

- **Cleaning Steps Implemented:**
  1. Removed leading/trailing spaces from text fields.
  2. Standardized categorical values to a uniform format.
  3. Converted numeric columns (`Quantity`, `Price Per Unit`, `Total Spent`) to `float` and handled non-numeric entries.
  4. Parsed `Transaction Date` as `datetime`.
  5. Handled missing values using imputation or removal based on business logic.
  6. Removed duplicate records.
  7. Final dataset saved as `cleaned_cafe_sales.csv` for further analysis.
  
## For More Information on about this project
02_Cafe_Sales_Analytics_Dashboard_Project_Report.pdf
[Access Here](https://github.com/Afraz-Gen-AI-Analytics/Cafe_Sales_Analytics_Dashboard/blob/main/02_Cafe_Sales_Analytics_Dashboard_Project_report.pdf)

## Project Assets
Google Drive Link (Dataset, PBIX File, Presentation and Documentation):  
[Access Here](https://drive.google.com/drive/folders/1uAZW5WhPnl0W_UsPSsgxbkN4eTuDR1m_?usp=sharing)

## Contact
**Muhammed Mufinuddin Afraz**  
- Email: afrazaffu31@gmail.com  
- LinkedIn: [www.linkedin.com/in/afraz-analytics](https://www.linkedin.com/in/afraz-analytics)  
- GitHub: [Afraz-Gen-AI-Analytics](https://github.com/Afraz-Gen-AI-Analytics)  
- Google Drive (Project Portfolio): [Click Here](https://drive.google.com/drive/folders/1szbdGJg2_2VrmIE9xfYVot_eu2GqoM3c)


