# 📊 Power BI Sales Dashboard

## 📌 Overview

This project is a Power BI dashboard designed to analyze and visualize sales data. It provides insights into regional performance, monthly trends, and key business metrics to support data-driven decision-making.

## 🚀 Features

* Interactive dashboards
* Monthly sales trends
* Region-wise performance analysis
* KPI tracking (Revenue, Orders, Returns)
* Clean and user-friendly visuals

## 🛠️ Tools & Technologies

* Power BI
* SQL (for data queries)
* Excel / CSV (data source)

## 📂 Project Structure

```
├── data/               # Raw dataset files
├── images/             # Dashboard screenshots
├── reports/            # Power BI (.pbix) file
└── README.md           # Project documentation
```

## 📈 Dashboard Preview

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/353bb370-4103-4196-832f-72c8b091effd" />


## ⚙️ How to Use

1. Download the `.pbix` file from the repository
2. Open it using Power BI Desktop
3. Refresh the dataset if needed
4. Explore the interactive dashboard

## 📊 Key Insights

* Identifies top-performing regions
* Tracks monthly revenue growth
* Highlights cancellation and return rates

## 🧠 Learning Outcomes

* Data cleaning and transformation
* Building interactive dashboards
* Writing efficient SQL queries

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

## 📜 License

This project is open-source and available under the MIT License.

## 📬 Contact

For any queries or feedback, feel free to reach out.
<p align="center">
  <img src="https://capsule-render.vercel.app/api?text=Student+Management+System&animation=fadeIn&type=waving&color=gradient&height=100"/>
</p>

<p align="center">
  <img width="300" src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif">
</p>

# Student Management System

A Python project for managing student records.

## Features

- Add students
- Delete students
- Search students
- Generate reports

## Installation

```bash
git clone https://github.com/username/project.git
cd project
pip install -r requirements.txt
```

## Usage

```bash
python main.py
```

## Author

Your Name

---



# 🎯 Expectation Decider
### Probability & Statistics Based Student Performance Prediction Model

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Statistics](https://img.shields.io/badge/Statistics-Probability-red?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange?style=for-the-badge&logo=numpy)
![SciPy](https://img.shields.io/badge/SciPy-Statistical%20Analysis-blue?style=for-the-badge&logo=scipy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow?style=for-the-badge)

---
# 📌 Table of Contents
<table>
<tr>
<td valign="top" width="65%">

- 🎯 [Project Objectives](#project-objectives)
- 🚀 [Features](#features)
- 📊 [Dataset Attributes](#dataset-attributes)
- 📂 [Project Structure](#project-structure)
- 🧠 [Statistical Concepts Used](#statistical-concepts-used)
- 🔬 [Technologies Used](#technologies-used)
- ⚙️ [Installation](#installation)
- ▶️ [How to Run](#how-to-run)
- 📈 [Visualizations](#visualizations)
- 📋 [Sample Results](#sample-results)
- 📚 [Learning Outcomes](#learning-outcomes)
- 💡 [Future Improvements](#future-improvements)
- 👨‍💻 [Author](#author)
- ⭐ [Support](#support)
- 🏆 [Final Conclusion](#final-conclusion)

</td>

<td valign="top" align="right">

<img src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" width="400"/>

</td>
</tr>
</table>

# 🎯 Project Overview

The **Expectation Decider** is a Probability and Statistics project designed to analyze student academic performance and estimate the likelihood of passing a competitive mathematics examination.

The model uses student-related factors such as:

- Study Hours
- Attendance Percentage
- Group Discussion Participation
- Previous Test Scores

to perform statistical analysis and derive meaningful probability-based insights.

This project demonstrates practical applications of Probability Theory, Random Variables, Probability Distributions, Conditional Probability, Contingency Tables, and Bayes Theorem using Python.

---

# 🎯 Project Objectives

The objectives of this project are:

- Generate and analyze student performance data.
- Apply probability concepts to real-world scenarios.
- Understand random variables and probability distributions.
- Calculate empirical and theoretical probabilities.
- Analyze relationships between variables.
- Use Bayes Theorem for prediction.
- Visualize statistical patterns using charts.
- Develop data-driven decision-making skills.

---

# 🚀 Features

✅ Synthetic Dataset Generation

✅ Probability Analysis

✅ Empirical Probability

✅ Theoretical Probability

✅ Random Variable Modeling

✅ Binomial Distribution

✅ Mean & Variance Calculation

✅ Venn Diagram Analysis

✅ Contingency Tables

✅ Joint Probability

✅ Marginal Probability

✅ Conditional Probability

✅ Independence Testing

✅ Bayes Theorem Application

✅ Data Visualization

✅ CSV Export

---

# 📊 Dataset Attributes

| Feature | Description |
|----------|-------------|
| study_hours | Number of study hours per week |
| attendance | Attendance percentage |
| group_discussion | Participation in group discussions |
| previous_test_score | Marks obtained in previous test |
| final_exam_pass | Pass or Fail result |

---

# 📂 Project Structure

```text
Expectation-Decider/
│
├── expectation_decider.py
├── expectation_decider_dataset.csv
├── README.md
│
├── charts/
│   ├── pass_fail_chart.png
│   ├── attendance_histogram.png
│   └── study_vs_score.png
│
└── requirements.txt
```

---

# 🧠 Statistical Concepts Used

---

## 1️⃣ Probability

Probability measures how likely an event is to occur.

### Formula

```math
P(E)=\frac{Favorable\ Outcomes}{Total\ Outcomes}
```

### Example

Suppose:

- 120 students pass
- Total students = 200

```math
P(Pass)=\frac{120}{200}
```

```math
P(Pass)=0.60
```

Meaning:

There is a **60% chance** that a randomly selected student passes.

---

## 2️⃣ Empirical Probability

Empirical probability is calculated using observed data.

### Formula

```math
P(E)=\frac{Number\ of\ times\ event\ occurs}{Total\ observations}
```

### Example

Passes observed = 120

Total students = 200

```math
P(Pass)=\frac{120}{200}=0.60
```

---

## 3️⃣ Theoretical Probability

Calculated mathematically before observing data.

### Example

Choosing a day randomly from a week:

```math
P(Weekend)=\frac{2}{7}
```

```math
P(Weekend)=0.2857
```

---

## 4️⃣ Random Variable

Let:

```math
X = Number\ of\ students\ passing\ among\ 3\ selected\ students
```

Possible values:

```text
0,1,2,3
```

---

## 5️⃣ Binomial Distribution

Used when:

- Fixed number of trials
- Only Pass/Fail outcomes
- Independent observations

### Formula

```math
P(X=x)=\binom{n}{x}p^x(1-p)^{n-x}
```

### Example

Assume:

```math
n=3
```

```math
p=0.60
```

Find probability that exactly 2 students pass.

```math
P(X=2)=\binom{3}{2}(0.60)^2(0.40)
```

```math
P(X=2)=0.432
```

---

## 6️⃣ Mean of Binomial Distribution

### Formula

```math
\mu=np
```

### Example

```math
\mu=(3)(0.60)
```

```math
\mu=1.8
```

Meaning:

Expected passing students = **1.8**

---

## 7️⃣ Variance of Binomial Distribution

### Formula

```math
\sigma^2=np(1-p)
```

### Example

```math
\sigma^2=(3)(0.60)(0.40)
```

```math
\sigma^2=0.72
```

---

## 8️⃣ Joint Probability

Probability that two events occur simultaneously.

### Formula

```math
P(A \cap B)
```

### Example

Student:

- Participates in group discussion
- Passes exam

Suppose:

90 students satisfy both conditions.

```math
P(Group\cap Pass)=\frac{90}{200}
```

```math
P(Group\cap Pass)=0.45
```

---

## 9️⃣ Marginal Probability

Probability of a single event.

### Example

Passes Exam

```math
P(Pass)=\frac{120}{200}
```

```math
P(Pass)=0.60
```

---

## 🔟 Conditional Probability

Probability of passing given participation in group discussion.

### Formula

```math
P(A|B)=\frac{P(A\cap B)}{P(B)}
```

### Example

90 students:

- Participate in discussion
- Pass exam

120 students:

- Participate in discussion

```math
P(Pass|Group)=\frac{90}{120}
```

```math
P(Pass|Group)=0.75
```

Meaning:

Students participating in discussions have a **75% probability** of passing.

---

## 1️⃣1️⃣ Independent vs Dependent Events

Events are independent if:

```math
P(A\cap B)=P(A)P(B)
```

### Example

Suppose:

```math
P(Group)=0.60
```

```math
P(Pass)=0.60
```

```math
P(Group\cap Pass)=0.45
```

Check:

```math
P(Group)P(Pass)=0.36
```

Since:

```math
0.45 \neq 0.36
```

The events are **Dependent**.

---

## 1️⃣2️⃣ Bayes Theorem

### Formula

```math
P(A|B)=\frac{P(B|A)P(A)}{P(B)}
```

### Example

Given:

```math
P(H|Pass)=0.70
```

```math
P(H)=0.60
```

```math
P(Pass)=0.6667
```

Find:

```math
P(Pass|H)
```

Calculation:

```math
P(Pass|H)=\frac{(0.70)(0.6667)}{0.60}
```

```math
P(Pass|H)=0.7778
```

Result:

Students with high attendance have a **77.78% probability** of passing.

---

# 🔬 Technologies Used

- Python
- NumPy
- Pandas
- SciPy
- Matplotlib

---

# ⚙️ Installation

```bash
git clone https://github.com/yourusername/Expectation-Decider.git
```

```bash
cd Expectation-Decider
```

```bash
pip install numpy pandas scipy matplotlib
```

---

# ▶️ How to Run

```bash
python expectation_decider.py
```

---

# 📈 Visualizations

The project generates:

### Pass vs Fail Distribution

```text
Bar Chart
```

### Attendance Distribution

```text
Histogram
```

### Study Hours vs Previous Test Score

```text
Scatter Plot
```

---

# 📋 Sample Results

| Metric | Value |
|----------|---------|
| Pass Probability | 0.60 |
| Attendance >80% | 0.45 |
| Group Discussion Participation | 0.60 |
| Conditional Probability | 0.75 |
| Bayes Prediction | 0.7778 |

---

# 📚 Learning Outcomes

After completing this project, you will understand:

- Probability Theory
- Statistical Inference
- Random Variables
- Probability Distributions
- Conditional Probability
- Bayes Theorem
- Data Visualization
- Statistical Decision Making

---

# 💡 Future Improvements

- Machine Learning Prediction Models
- Logistic Regression
- Student Risk Analysis
- Interactive Dashboard
- Web Application Deployment
- Real Educational Data Integration

---

# 👨‍💻 Author

**Your Name**

Data Analytics & Statistics Enthusiast

GitHub: https://github.com/yourusername

---

# ⭐ Support

If you found this project useful:

⭐ Star the Repository

🍴 Fork the Repository

📢 Share with Others

---

# 🏆 Final Conclusion

The **Expectation Decider** project demonstrates how Probability and Statistics can be used to evaluate student performance and make informed academic predictions.

Through the use of Probability Theory, Binomial Distribution, Conditional Probability, Contingency Tables, and Bayes Theorem, the project provides meaningful insights into the factors that influence exam success and supports data-driven decision-making.

The **Expectation Decider** project demonstrates how Probability and Statistics can be used to make data-driven academic predictions. By combining probability theory, conditional probability, contingency tables, and Bayes theorem, the model provides meaningful insights into student success factors and supports intelligent decision-making.


# 🧠 Statistical Concepts Used

---

## 1️⃣ Probability

Probability measures how likely an event is to occur.

### Formula

```math
P(E)=\frac{Favorable\ Outcomes}{Total\ Outcomes}
```

### Example

120 students passed out of 200 students.

```math
P(Pass)=\frac{120}{200}=0.60
```

### Python Code

```python
total_students = 200
passed_students = 120

probability_pass = passed_students / total_students

print(probability_pass)
```

**Output**

```text
0.60
```

---

## 2️⃣ Empirical Probability

Empirical probability uses observed data.

### Formula

```math
P(E)=\frac{Observed\ Successes}{Total\ Observations}
```

### Python Code

```python
empirical_probability = len(
    df[df["final_exam_pass"] == "Pass"]
) / len(df)

print(empirical_probability)
```

---

## 3️⃣ Theoretical Probability

Probability calculated mathematically.

### Example

Selecting a weekend day from a week.

```math
P(Weekend)=\frac{2}{7}
```

### Python Code

```python
theoretical_probability = 2 / 7

print(theoretical_probability)
```

---

## 4️⃣ Random Variable

Let:

```math
X = Number\ of\ students\ passing\ among\ 3\ students
```

### Python Code

```python
from scipy.stats import binom

p = 0.60
n = 3

for x in range(4):
    print(
        f"P(X={x}) =",
        round(binom.pmf(x, n, p), 4)
    )
```

---

## 5️⃣ Binomial Distribution

### Formula

```math
P(X=x)=\binom{n}{x}p^x(1-p)^{n-x}
```

### Python Code

```python
from scipy.stats import binom

probability = binom.pmf(
    k=2,
    n=3,
    p=0.60
)

print(probability)
```

**Output**

```text
0.432
```

---

## 6️⃣ Mean of Binomial Distribution

### Formula

```math
\mu=np
```

### Python Code

```python
n = 3
p = 0.60

mean = n * p

print(mean)
```

**Output**

```text
1.8
```

---

## 7️⃣ Variance of Binomial Distribution

### Formula

```math
\sigma^2=np(1-p)
```

### Python Code

```python
n = 3
p = 0.60

variance = n * p * (1 - p)

print(variance)
```

**Output**

```text
0.72
```

---

## 8️⃣ Joint Probability

### Formula

```math
P(A \cap B)
```

### Python Code

```python
joint_probability = len(
    df[
        (df["group_discussion"] == "Yes")
        &
        (df["final_exam_pass"] == "Pass")
    ]
) / len(df)

print(joint_probability)
```

---

## 9️⃣ Marginal Probability

### Formula

```math
P(A)
```

### Python Code

```python
marginal_probability = len(
    df[df["final_exam_pass"] == "Pass"]
) / len(df)

print(marginal_probability)
```

---

## 🔟 Conditional Probability

### Formula

```math
P(A|B)=\frac{P(A\cap B)}{P(B)}
```

### Python Code

```python
conditional_probability = (
    len(
        df[
            (df["group_discussion"] == "Yes")
            &
            (df["final_exam_pass"] == "Pass")
        ]
    )
    /
    len(
        df[
            df["group_discussion"] == "Yes"
        ]
    )
)

print(conditional_probability)
```

---

## 1️⃣1️⃣ Independent vs Dependent Events

### Python Code

```python
joint = len(
    df[
        (df["group_discussion"] == "Yes")
        &
        (df["final_exam_pass"] == "Pass")
    ]
) / len(df)

product = (
    (df["group_discussion"] == "Yes").mean()
    *
    (df["final_exam_pass"] == "Pass").mean()
)

print("P(A∩B) =", joint)
print("P(A)P(B) =", product)

if abs(joint - product) < 0.02:
    print("Independent")
else:
    print("Dependent")
```

---

## 1️⃣2️⃣ Bayes Theorem

### Formula

```math
P(A|B)=\frac{P(B|A)P(A)}{P(B)}
```

### Python Code

```python
P_H_given_Pass = 0.70
P_H_given_Fail = 0.40
P_H = 0.60

P_Pass = (
    (P_H - P_H_given_Fail)
    /
    (P_H_given_Pass - P_H_given_Fail)
)

P_Pass_given_H = (
    P_H_given_Pass * P_Pass
) / P_H

print(P_Pass_given_H)
```

**Output**


# 🧠 Statistical Concepts Used

This project demonstrates core Probability and Statistics concepts through practical Python implementation.

---

## 1️⃣ Probability

Probability measures the likelihood that an event will occur.

### Formula

```math
P(E)=\frac{Favorable\ Outcomes}{Total\ Outcomes}
```

### Example from Project

Probability that a student passes the final exam.

### Python Code

```python
P_pass = (df["final_exam_pass"] == "Pass").mean()

print(P_pass)
```

---

## 2️⃣ Empirical Probability

Calculated using actual observed data.

### Example

Probability of passing based on generated student records.

### Python Code

```python
empirical_probability = P_pass

print(empirical_probability)
```

---

## 3️⃣ Theoretical Probability

Calculated mathematically without observed data.

### Example

Probability of selecting a weekend day from a week.

```math
P(Weekend)=\frac{2}{7}
```

### Python Code

```python
theoretical_probability = 2 / 7

print(theoretical_probability)
```

---

## 4️⃣ Random Variable

Define:

```math
X = Number\ of\ students\ passing\ among\ 3\ randomly\ selected\ students
```

Possible values:

```text
0, 1, 2, 3
```

### Python Code

```python
p = P_pass
n_students = 3

distribution = pd.DataFrame({
    "X": range(4),
    "P(X=x)": [
        binom.pmf(x, n_students, p)
        for x in range(4)
    ]
})

print(distribution)
```

---

## 5️⃣ Probability Distribution

The project models passing students using a Binomial Distribution.

### Formula

```math
P(X=x)=\binom{n}{x}p^x(1-p)^{n-x}
```

### Python Code

```python
from scipy.stats import binom

for x in range(4):
    print(
        x,
        binom.pmf(
            x,
            n_students,
            p
        )
    )
```

---

## 6️⃣ Mean of Random Variable

Expected number of passing students.

### Formula

```math
\mu=np
```

### Python Code

```python
mean_x = n_students * p

print(mean_x)
```

---

## 7️⃣ Variance of Random Variable

Measures spread in outcomes.

### Formula

```math
\sigma^2=np(1-p)
```

### Python Code

```python
variance_x = n_students * p * (1 - p)

print(variance_x)
```

---

## 8️⃣ Venn Diagram Analysis

Used to analyze overlap between:

- Students studying more than 10 hours
- Students with attendance above 80%

### Python Code

```python
A = df["study_hours"] > 10
B = df["attendance"] > 80

only_A = np.sum(A & ~B)
only_B = np.sum(~A & B)
both = np.sum(A & B)
neither = np.sum(~A & ~B)

print(only_A)
print(only_B)
print(both)
print(neither)
```

### Example

```text
Only Study >10 Hours
Only Attendance >80%
Both Conditions
Neither Condition
```

---

## 9️⃣ Contingency Table

Used to compare:

- Group Discussion Participation
- Final Exam Result

### Python Code

```python
contingency_table = pd.crosstab(
    df["group_discussion"],
    df["final_exam_pass"]
)

print(contingency_table)
```

### Example Output

```text
final_exam_pass  Fail  Pass
group_discussion
No                45    35
Yes               65    55
```

---

## 🔟 Joint Probability

Probability of:

```text
Participates in Group Discussion
AND
Passes Exam
```

### Formula

```math
P(A\cap B)
```

### Python Code

```python
joint_probability = len(
    df[
        (df["group_discussion"] == "Yes")
        &
        (df["final_exam_pass"] == "Pass")
    ]
) / len(df)

print(joint_probability)
```

---

## 1️⃣1️⃣ Marginal Probability

Probability of a single event.

### Example

Probability that a student passes.

### Python Code

```python
marginal_probability = len(
    df[df["final_exam_pass"] == "Pass"]
) / len(df)

print(marginal_probability)
```

---

## 1️⃣2️⃣ Conditional Probability

Probability that a student passes given participation in group discussion.

### Formula

```math
P(A|B)=\frac{P(A\cap B)}{P(B)}
```

### Python Code

```python
conditional_probability = (
    len(
        df[
            (df["group_discussion"] == "Yes")
            &
            (df["final_exam_pass"] == "Pass")
        ]
    )
    /
    len(
        df[
            df["group_discussion"] == "Yes"
        ]
    )
)

print(conditional_probability)
```

---

## 1️⃣3️⃣ Independent vs Dependent Events

Check whether:

```text
Group Discussion
```

and

```text
Passing Exam
```

are independent.

### Formula

```math
P(A\cap B)=P(A)P(B)
```

### Python Code

```python
left_side = joint_probability

right_side = (
    (df["group_discussion"] == "Yes").mean()
    *
    (df["final_exam_pass"] == "Pass").mean()
)

if abs(left_side - right_side) < 0.02:
    print("Independent")
else:
    print("Dependent")
```

---

## 1️⃣4️⃣ Bayes Theorem

Used to predict the probability of passing when attendance is high.

### Formula

```math
P(A|B)=\frac{P(B|A)P(A)}{P(B)}
```

### Python Code

```python
P_H_given_Pass = 0.70
P_H_given_Fail = 0.40
P_H = 0.60

P_Pass = (
    (P_H - P_H_given_Fail)
    /
    (P_H_given_Pass - P_H_given_Fail)
)

P_Pass_given_H = (
    P_H_given_Pass * P_Pass
) / P_H

print(P_Pass_given_H)
```

### Output

```text
0.7778
```

Meaning:

A student with high attendance has approximately **77.78% probability of passing**.

---

## 1️⃣5️⃣ Data Visualization

The project visualizes statistical patterns using charts.

### Pass vs Fail Distribution

```python
df["final_exam_pass"].value_counts().plot(kind="bar")
plt.show()
```

### Attendance Distribution

```python
plt.hist(df["attendance"], bins=10)
plt.show()
```

### Study Hours vs Previous Score

```python
plt.scatter(
    df["study_hours"],
    df["previous_test_score"]
)
plt.show()
```

```text
0.7778
```
hiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiii
# ⚙️ How the Code Works

This project follows a complete Probability & Statistics workflow, starting from data generation and ending with statistical conclusions and visualizations.

---

## Step 1: Import Required Libraries

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from scipy.stats import binom
```

### Explanation

- **NumPy** is used for random number generation and mathematical operations.
- **Pandas** is used to create and manipulate datasets.
- **Matplotlib** is used for charts and visualizations.
- **SciPy** provides statistical functions such as the Binomial Distribution.

---

## Step 2: Generate Student Dataset

```python
study_hours = np.random.randint(2, 21, n)
attendance = np.random.randint(50, 101, n)
group_discussion = np.random.choice(
    ["Yes", "No"],
    n,
    p=[0.6, 0.4]
)
previous_test_score = np.random.randint(
    40,
    101,
    n
)
```

### Explanation

This section creates synthetic student data.

Example:

| Student | Study Hours | Attendance | Group Discussion | Previous Score |
|----------|------------|------------|------------------|----------------|
| 1 | 12 | 88 | Yes | 74 |
| 2 | 8 | 65 | No | 55 |

The project generates 200 such records automatically.

---

## Step 3: Create Performance Score

```python
score = (
    0.25 * study_hours +
    0.30 * (attendance / 10) +
    0.35 * (previous_test_score / 10) +
    np.where(group_discussion == "Yes", 2, 0)
)
```

### Explanation

This formula creates a weighted academic performance score.

Factors affecting performance:

| Factor | Weight |
|----------|----------|
| Study Hours | 25% |
| Attendance | 30% |
| Previous Score | 35% |
| Group Discussion | Bonus Points |

Students with better academic behavior receive higher scores.

---

## Step 4: Predict Pass or Fail

```python
final_exam_pass = np.where(
    score >= np.percentile(score, 45),
    "Pass",
    "Fail"
)
```

### Explanation

The program calculates the 45th percentile score.

Students above that threshold:

```text
Pass
```

Students below:

```text
Fail
```

This creates the target variable for analysis.

---

## Step 5: Create DataFrame

```python
df = pd.DataFrame({
    "study_hours": study_hours,
    "attendance": attendance,
    "group_discussion": group_discussion,
    "previous_test_score": previous_test_score,
    "final_exam_pass": final_exam_pass
})
```

### Explanation

All generated information is stored in a Pandas DataFrame.

This acts like an Excel spreadsheet inside Python.

Example:

| study_hours | attendance | group_discussion | previous_test_score | final_exam_pass |
|-------------|-------------|-------------|-------------|-------------|
| 12 | 88 | Yes | 74 | Pass |

---

## Step 6: Calculate Basic Probabilities

```python
P_pass = (
    df["final_exam_pass"] == "Pass"
).mean()
```

### Explanation

The expression:

```python
df["final_exam_pass"] == "Pass"
```

creates:

```text
True
False
True
True
...
```

Since:

```python
True = 1
False = 0
```

The mean becomes the probability of passing.

---

## Step 7: Build Binomial Distribution

```python
distribution = pd.DataFrame({
    "X": range(4),
    "P(X=x)": [
        binom.pmf(
            x,
            n_students,
            p
        )
        for x in range(4)
    ]
})
```

### Explanation

The project calculates:

```text
P(X=0)
P(X=1)
P(X=2)
P(X=3)
```

where:

```text
X = Number of students passing among 3 students
```

This creates a complete probability distribution table.

---

## Step 8: Calculate Mean and Variance

```python
mean_x = n_students * p

variance_x = n_students * p * (1 - p)
```

### Explanation

These formulas summarize the probability distribution.

Mean:

```text
Expected number of passing students
```

Variance:

```text
How spread out the outcomes are
```

---

## Step 9: Venn Diagram Logic

```python
A = df["study_hours"] > 10
B = df["attendance"] > 80
```

### Explanation

Set A:

```text
Students studying more than 10 hours
```

Set B:

```text
Students with attendance above 80%
```

The project then calculates:

```python
A & B
```

which finds students satisfying both conditions.

---

## Step 10: Create Contingency Table

```python
pd.crosstab(
    df["group_discussion"],
    df["final_exam_pass"]
)
```

### Explanation

Creates a table such as:

| Group Discussion | Pass | Fail |
|------------------|------|------|
| Yes | 55 | 25 |
| No | 35 | 85 |

This table is the foundation for:

- Joint Probability
- Marginal Probability
- Conditional Probability

---

## Step 11: Calculate Conditional Probability

```python
conditional_probability = (
    pass_and_group
    /
    total_group
)
```

### Explanation

Answers:

> What is the probability that a student passes given that they participate in group discussions?

This is useful for measuring the impact of collaborative learning.

---

## Step 12: Test Independence

```python
P(A∩B)
```

vs

```python
P(A) × P(B)
```

### Explanation

If both values are equal:

```text
Independent Events
```

Otherwise:

```text
Dependent Events
```

The project determines whether group discussion influences exam performance.

---

## Step 13: Apply Bayes Theorem

```python
P(Pass|HighAttendance)
```

### Explanation

This is the predictive component of the project.

Question answered:

> If a student has high attendance, what is the probability that they will pass?

Bayes Theorem reverses conditional probabilities and provides a more realistic prediction.

---

## Step 14: Visualize Results

### Bar Chart

```python
df["final_exam_pass"].value_counts().plot(
    kind="bar"
)
```

Purpose:

```text
Compare Pass vs Fail counts
```

---

### Histogram

```python
plt.hist(
    df["attendance"],
    bins=10
)
```

Purpose:

```text
Analyze attendance distribution
```

---

### Scatter Plot

```python
plt.scatter(
    df["study_hours"],
    df["previous_test_score"]
)
```

Purpose:

```text
Identify relationships between study hours and performance
```

---

## Step 15: Generate Insights

The final section interprets all statistical results and identifies:

- Which students are most likely to pass
- How attendance affects success
- Whether group discussions improve outcomes
- The usefulness of Bayes Theorem for prediction

This transforms raw data into actionable educational insights.

