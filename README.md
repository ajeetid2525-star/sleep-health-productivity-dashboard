# sleep-health-productivity-dashboard
Power BI dashboard analyzing sleep, health, and lifestyle data from 1,000 individuals to uncover what drives workplace productivity and energy levels.
# 🛌 Sleep, Health & Productivity Dashboard

A Power BI analytics dashboard exploring the relationship between sleep, physical health, and workplace productivity across 1,000 individuals from 8 different occupations.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## 📌 Overview

Poor sleep and lifestyle habits quietly erode workplace performance — often before anyone notices. This dashboard was built to make that connection visible.

It consolidates sleep patterns, health indicators (BMI, exercise, diet), mood and stress levels, and productivity scores into a single interactive report, helping identify **what actually drives energy, wellbeing, and output** — and where targeted interventions could have the biggest impact.

**Dataset size:** 1,000 individuals · **Occupations covered:** 8 · **Report pages:** 5

---

## 📊 Dashboard Preview

| Page | Preview |
|------|---------|
| Executive Overview | `images/01_executive_overview.png` |
| Sleep Analysis | `images/02_sleep_analysis.png` |
| Health Analysis | `images/03_health_analysis.png` |
| Productivity Analysis | `images/04_productivity_analysis.png` |

> Add your exported screenshots to an `images/` folder and reference them above with `![Executive Overview](images/01_executive_overview.png)` so they render on the repo page.

---

## 🧭 Report Pages

### 01 · Executive Overview
High-level summary of overall health, sleep, and productivity across the full population.
- Total members, average wake-up time, average sleep duration, average sleep disorder score
- Occupation and gender distribution
- Sleep quality distribution across the population
- Filters: Diet Category, Gender, Occupation

### 02 · Sleep Analysis
Deep dive into sleep patterns and sleep quality.
- Wake-up time distribution across the population
- Average sleep duration by occupation
- Sleep duration vs. energy level correlation
- Sleep disorder risk distribution (Low / Medium / High)

### 03 · Health Analysis
Physical and mental health & wellness indicators.
- Healthy diet count, average exercise frequency, average BMI
- BMI distribution across the population
- Overall risk score by health category (Unhealthy / Balanced / Healthy)
- Filters: Gender, Age Group

### 04 · Productivity Analysis
Productivity drivers and performance patterns.
- Correlation between sleep, mood, and productivity
- Mood score by stress level
- Sleep duration vs. productivity trend
- Filters: Occupation, Age Group

### 05 · Recommendations
Consolidated takeaways and suggested actions based on the findings across all pages.

---

## 💡 Key Insights

| Metric | Value | Insight |
|---|---|---|
| Avg. sleep duration | 7 hours | Meets baseline, but doesn't guarantee high energy |
| Avg. energy level | 7% | Very low despite high output — possible burnout signal |
| Avg. productivity score | 76% | High even with low reported energy levels |
| Sleep–productivity correlation | 0.52 | Moderate positive impact |
| Mood–stress correlation | -0.45 | Higher mood is linked to lower stress |
| Sleep disorder risk (medium/high) | 19.8% | Nearly 1 in 5 people at elevated risk |
| Avg. BMI | 25.06 | Falls in the overweight range |
| Avg. exercise frequency | 3.65 / week | Below the recommended baseline for many |
| Healthy diet adherence | 311 people | Just under a third of the population |

---

## 🎯 Recommendations

- **Protect sleep hours** — target a consistent 7–8 hour sleep window, especially for the large mid-range sleep-quality group (score 6–8)
- **Screen for sleep disorder risk** — proactively address the ~20% in the medium-to-high risk band
- **Support diet & activity** — promote balanced diet programs and regular light exercise across all occupations
- **Investigate the burnout signal** — high productivity paired with very low energy suggests output is being sustained by strain, not capacity
- **Track sleep, mood & productivity together** — these metrics move as a system, not in isolation

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — report building and DAX measures
- **Power Query** — data cleaning and transformation
- **DAX** — calculated columns and measures for correlation and risk scoring

---

## 📁 Repository Structure

```
sleep-health-productivity-dashboard/
├── sleep_health_productivity.pbix     # Main Power BI report file
├── data/
│   └── dataset.csv                    # Source dataset
├── images/
│   ├── 01_executive_overview.png
│   ├── 02_sleep_analysis.png
│   ├── 03_health_analysis.png
│   └── 04_productivity_analysis.png
└── README.md
```

---

## 🚀 Getting Started

1. Clone this repository
```bash
   git clone https://github.com/<your-username>/sleep-health-productivity-dashboard.git
```
2. Open `sleep_health_productivity.pbix` in **Power BI Desktop**
3. Use the filters on each page (Diet Category, Gender, Occupation, Age Group) to explore the data
4. Navigate between pages using the in-report navigation buttons or page tabs

---

## 🔭 Future Improvements

- Add time-series tracking if longitudinal data becomes available
- Introduce predictive modeling for sleep disorder risk
- Publish to Power BI Service with scheduled data refresh
- Add a mobile-optimized report layout

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](../../issues) or open a pull request.

---

## 📬 Contact

Questions or feedback? Open an issue in this repository or reach out directly.
