# EdTech Funnel Analysis & Experimentation Strategy

**Live Dashboard:** (https://sidis9-edtech-funnel.streamlit.app)

## Overview
An interactive growth analytics dashboard analyzing where students drop off in an EdTech platform and what experiments could improve activation, retention, and revenue.

Built using the **Open University Learning Analytics Dataset (OULAD)** — 32,593 real students across 7 courses.

## Problem Statement
Many students register on EdTech platforms but never complete their first assessment. This project identifies exactly where drop-off occurs, diagnoses why, and proposes data-backed experiments to fix it.

## Key Findings
- **18% of students log in but never start a course** — the biggest drop-off in the funnel
- **Only 30% of students never activate** within 30 days of registration
- **Activated students are 2.4x more likely to pass** — 57.5% vs 23.9% retention rate
- A 10% improvement in activation could generate **$652,000 in additional revenue**

## Dashboard Sections
1. **Funnel Drop-off Analysis** — conversion rates at each stage of the student journey
2. **Activation Analysis** — breakdown of activated vs non-activated students
3. **Retention Analysis** — retention comparison by activation status
4. **Experimentation Strategy** — 3 proposed experiments with hypothesis and expected lift
5. **Business Impact Simulator** — interactive slider to model revenue impact of activation improvements

## Experiments Proposed
| Experiment | Target Stage | Expected Lift |
|---|---|---|
| Guided Onboarding Flow | Login → Course Start | 8-12% |
| Progress Streak & Nudges | Course Start → Assessment | 10-15% |
| Micro Assessment in Lesson 1 | Activation Rate | 15-20% |

## Tools & Technologies
- **Python** — core analysis
- **Pandas** — data manipulation and cohort logic
- **Plotly** — interactive visualizations
- **Streamlit** — live dashboard deployment
- **Scipy** — statistical significance testing

## Dataset
Open University Learning Analytics Dataset (OULAD)
- 32,593 students
- 7 courses
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/349/open+university+learning+analytics+dataset)

