# 🏫 PyCitySchools — School District Analysis with Pandas

## 📊 Overview

As the new **Chief Data Scientist** for your city's school district, this project focuses on helping local officials make data-driven decisions about school funding and performance. Using **Python**, **Pandas**, and **Jupyter Notebook**, you'll analyze standardized test scores and school spending data to uncover key trends and performance metrics across the district.

---

## 🎯 Objectives

The goal of this analysis is to generate detailed performance summaries using **Pandas**:

### 🏙️ District Summary
- Total number of schools and students
- Total budget
- Average math and reading scores
- Percent passing math and reading
- Overall passing rate (math **and** reading)

### 🏫 School Summary
- Breakdown by each school:
  - Budget
  - Scores
  - Per-student spending
  - Passing percentages

### 🏆 Top & Bottom Performing Schools
- Rank schools by overall passing percentage
- Show top 5 and bottom 5 schools

### 📈 Grade-Level Performance
- Math and reading score trends by grade (9–12)
- Per school breakdown

### 💸 Scores by School Spending
- Analyze trends based on per-student budget
- Use spending bins:
  - `<$585`
  - `$585–630`
  - `$630–645`
  - `$645–680`

### 🧍‍♂️ Scores by School Size
- Small (<1000), Medium (1000–2000), Large (2000–5000)
- Compare math, reading, and passing percentages

### 🏷️ Scores by School Type
- Public vs Charter
- Average test scores and passing rates

---

## 🧪 Sample Output

### ✅ District Summary (Example)
Total Schools: 15
Total Students: 39,170
Total Budget: $24,649,428.00
Average Math Score: 79.00
Average Reading Score: 81.88
% Passing Math: 74.98%
% Passing Reading: 85.81%
% Overall Passing: 65.17%

### ✅ Top Performing Schools (by % Overall Passing)
	1.	Cabrera High School         91.33%
	2.	Thomas High School          90.95%
	3.	Griffin High School         90.60%
…
---

## 🧠 Key Takeaways (from Written Report)

- **Conclusion 1:** Schools with **lower per-student spending** (under $630) generally performed **better** than those with the highest spending — possibly due to overfunding lower-performing schools.
- **Conclusion 2:** **Charter schools** consistently outperformed district schools in both math and reading, especially in passing rates — pointing to potentially more efficient academic environments.

---

## 🛠️ Technologies Used

- Python 3.x  
- Pandas  
- Jupyter Notebook  
- Matplotlib (optional)  
- CSV File I/O  

---

## ✅ Requirements Checklist

| Task                                      | Status |
|-------------------------------------------|--------|
| District Summary                          | ✅     |
| School Summary                            | ✅     |
| Top & Bottom Schools                      | ✅     |
| Math/Reading Scores by Grade              | ✅     |
| Scores by School Spending                 | ✅     |
| Scores by School Size                     | ✅     |
| Scores by School Type                     | ✅     |
| Written Report with 2 Conclusions         | ✅     |

---

## 💡 How to Run

1. Clone this repository.
2. Open `PyCitySchools/PyCitySchools.ipynb` in Jupyter Notebook.
3. Run all cells to generate tables and visualizations.
4. Refer to the written report in `analysis/summary_report.md` for conclusions.

---

## 📚 Acknowledgments

This project is part of the [edX Data Analytics Boot Camp], designed to simulate a real-world scenario using real education-based data and practical data analysis with Pandas.

---

## 👩‍💻 Author

**Aditi Nankar**  
Aspiring Data Analyst | Education Analytics Enthusiast  
