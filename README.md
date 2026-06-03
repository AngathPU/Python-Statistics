# 📊 Statistics Questions — Course Completion Project

A hands-on statistics project built with Python to demonstrate core statistical concepts learned during the course. The notebook covers descriptive statistics, data analysis, and probability distributions using real-world-style datasets.

---

## 🗂️ Project Structure

The notebook contains **3 independent problem sets**, each targeting a different statistical concept:

### Problem 1 — Student Grade Analysis
- Generates a synthetic dataset of **500 students** with random marks (out of 500)
- Calculates each student's **percentage** and assigns a **letter grade** (A/B/C/D/F)
- Visualizes the **grade distribution** using a pie chart
- Computes the **mean** and **mode** of student percentages

### Problem 2 — Descriptive Statistics on Two Datasets
- Compares two numeric arrays: `A = [1..10]` and `B = [11..20]`
- Calculates for both:
  - **Median**
  - **Variance**
  - **Standard Deviation**
- Demonstrates how shifting values (adding a constant) affects spread vs. central tendency

### Problem 3 — Poisson Probability Distribution
- Uses `scipy.stats.poisson` to compute the probability of exactly **k = 3 events** occurring when the average rate **μ = 2**
- Applies the Poisson Probability Mass Function (PMF) to model discrete event counts

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| `numpy` | Numerical operations, random data generation |
| `pandas` | DataFrame creation and manipulation |
| `matplotlib` | Data visualization (pie chart) |
| `scipy.stats` | Probability distributions (Poisson PMF) |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.7+ and the following libraries installed:

```bash
pip install numpy pandas matplotlib scipy
```

### Run the Notebook

```bash
jupyter notebook Statistics_questions__1_.ipynb
```

Or open it directly in **VS Code**, **Google Colab**, or **JupyterLab**.

---

## 📈 Key Concepts Covered

- **Measures of Central Tendency** — Mean, Median, Mode
- **Measures of Spread** — Variance, Standard Deviation
- **Grade Classification** — Conditional logic applied to data
- **Data Visualization** — Pie charts with `matplotlib`
- **Probability Distributions** — Poisson distribution using `scipy`

---

## 📁 Output Files

| File | Description |
|---|---|
| `Grade.png` | Pie chart showing grade distribution of 500 students |

---

## 👤 Author

Built as a **course completion project** to consolidate and apply statistical concepts using Python.

---

## 📝 License

This project is for educational purposes.
