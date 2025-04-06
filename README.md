#  IMDb Movies Dataset – Excel Data Cleaning Project

**Author:** [Antonio3010](https://github.com/Antonio3010)  
**Tool used:** Microsoft Excel  
**Dataset:** IMDb Movies Dataset (Kaggle)  
**Focus:** Data cleaning, formatting, and preparation for analysis

---

##  Project Overview

This project focuses on cleaning and preparing the **IMDb Movies Dataset** using Excel. The goal was to transform a disorganized dataset into a structured, analysis-ready file by applying core data cleaning techniques such as handling missing values, fixing inconsistent formats, and identifying outliers.

---

## 🔧 Steps Performed

1. **Initial Review**
   - Converted the dataset into table format for easier filtering.
   - Identified missing values in key fields (`Certificate`, `Metascore`, `Gross`).
   - Used boxplots to detect outliers in numeric fields like `Gross` and `IMDB_Rating`.

2. **Missing Data Handling**
   - Categorical nulls were filled with `"Unknown"`.
   - Numeric nulls were replaced with the **median**.
   - Dropped irrelevant fields like `Poster_Link`.

3. **Data Type & Format Fixes**
   - Standardized numeric formats (e.g., removing symbols from `Gross`, converting `Runtime` to minutes).
   - Ensured all numerical columns had the correct data type.

4. **Text & Category Cleanup**
   - Corrected UTF-8 encoding issues (e.g., “AmÃ©lie” → “Amélie”).
   - Cleaned textual fields using Excel functions like `TRIM`, `CLEAN`, `SUBSTITUTE`.
   - Simplified `Genre` by keeping only the primary genre.
   - Cleaned and standardized `Director` and `Stars`.
   - Removed symbols from `Overview` to prepare for future NLP.

5. **Duplicates & Structure**
   - No exact duplicates were found.
   - Added unique IDs for better referencing in SQL or BI tools.
   - Dataset was fully reorganized and structured for further analysis.

---

##  Output

- ✅ Cleaned and documented Excel file
- ✅ Ready for Power BI dashboards, SQL queries, or modeling in Python
- ✅ Ideal for showcasing data cleaning skills using Excel

---

## 🔗 Let’s Connect!

If you're interested in beginner-friendly data projects or Excel-based cleaning techniques:

- GitHub: [Antonio3010](https://github.com/Antonio3010)
- LinkedIn: [www.linkedin.com/in/antonio-alvarez-b9542b275]
