# Student Performance Analysis 📊

## Project Overview

This project focuses on analyzing student academic performance using Python. The Student Performance dataset is explored, cleaned, analyzed, and visualized to understand students' final grades and the relationship between study time and academic performance.

The project demonstrates the basic Data Science workflow, from loading raw data to generating meaningful insights through visualization.

## Objectives

- Load and explore the Student Performance dataset.
- Identify missing values and duplicate records.
- Calculate the average final grade.
- Identify the number of students scoring above 15.
- Analyze the correlation between study time and final grades.
- Compare the average academic performance of male and female students.
- Visualize the results using graphs.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

**Dataset:** Student Performance – Mathematics (`student-mat.csv`)

The dataset contains 395 student records and 33 columns, including:

- Student demographics
- Family background
- Study time
- Absences
- Previous grades (G1 and G2)
- Final grade (G3)

## Data Cleaning

The following data-cleaning operations were performed:

- Checked missing values using `isnull()`.
- Checked duplicate records using `duplicated()`.
- Removed duplicate records using `drop_duplicates()`.
- Inspected dataset shape and data types.

**Cleaning Results:**
- Total records: 395
- Total columns: 33
- Missing values: 0
- Duplicate records: 0

## Data Analysis and Key Findings

| Analysis | Result |
|---|---|
| Average Final Grade (G3) | 10.42 |
| Students scoring above 15 | 40 |
| Study Time Correlation | 0.098 |
| Female Average Grade | 9.97 |
| Male Average Grade | 10.91 |

### Key Insights

1. The average final grade of students is approximately 10.42 out of 20.
2. A total of 40 students scored above 15.
3. Study time has a very weak positive correlation with final grades.
4. Male students achieved a slightly higher average final grade than female students in this dataset.

## Data Visualizations

Three visualizations were created:

### 1. Histogram of Final Grades
Displays the distribution of students' final mathematics grades.

### 2. Scatterplot: Study Time vs Final Grades
Shows the relationship between students' study-time categories and their final grades.

### 3. Bar Chart: Gender-wise Average Performance
Compares the average final grades of male and female students.

## Project Structure

```text
Student-Performance-Analysis/
│
├── Student_Performance_Analysis.ipynb
├── student-mat.csv
└── README.md
```

## How to Run This Project

1. Clone this repository:

```bash
git clone https://github.com/your-username/Student-Performance-Analysis.git
```

2. Navigate to the project directory:

```bash
cd Student-Performance-Analysis
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Student_Performance_Analysis.ipynb` and run the cells.

## Conclusion

This project helped me understand the fundamentals of Data Science using Python. I gained practical experience in data loading, data cleaning, exploratory data analysis, statistical analysis, and data visualization.

It provided hands-on experience with the complete Data Science workflow and helped me interpret data to discover meaningful insights.

---

**Project Type:** Data Science – Beginner Level

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook
