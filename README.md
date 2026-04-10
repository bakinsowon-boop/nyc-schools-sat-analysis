# 🏫 Exploring NYC Public School SAT Test Result Scores

## Overview

SAT scores are a critical factor in the US college admissions process, with each of the three sections — reading, math, and writing — scored out of 800 points. This project analyses SAT performance data across New York City public schools to answer key questions about where top academic performance is concentrated and what patterns exist across schools.

This is the kind of analysis useful to education policymakers, school administrators, researchers, and parents navigating the admissions landscape.

---

## Business Questions Answered

1. **Which NYC schools have the best math performance?**
   Identified schools where the average math score exceeds 640 (80% of the maximum), ranked in descending order.

2. **Which are the top 10 schools overall?**
   Ranked schools by combined total SAT score (math + reading + writing) to surface the highest overall performers.

3. **Which NYC borough has the strongest SAT performance?**
   Aggregated school-level data by borough to identify geographic concentration of academic achievement.

---

## Dataset

**Source:** `schools.csv` — provided as part of the DataCamp DataLab project environment.

**Key fields include:**
- `school_name` — name of the NYC public school
- `average_math` — average SAT math score
- `average_reading` — average SAT reading score
- `average_writing` — average SAT writing score
- `borough` — NYC borough the school belongs to

---

## Methodology

- Data loaded and explored using **pandas**
- Filtering applied to isolate high math performers (average math > 640)
- Total SAT score derived by summing the three section averages
- Borough-level aggregation used to identify geographic performance trends
- Results sorted and sliced to surface meaningful rankings

---

## Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| pandas | Data manipulation and analysis |
| DataCamp DataLab | Development environment |

---

## Key Findings

> _Update this section with your actual outputs once the notebook has been run in full._

- **Best math schools:** Schools with average math scores above 640 — filtered and ranked
- **Top 10 overall:** Identified by total SAT score across all three sections
- **Borough insights:** [Add finding here — e.g. which borough dominated and by what margin]

---

## How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/BabsAkinsowon/nyc-schools-sat-analysis.git
   cd nyc-schools-sat-analysis
   ```

2. Install dependencies
   ```bash
   pip install pandas
   ```

3. Place `schools.csv` in the root directory and run the notebook
   ```bash
   jupyter notebook notebook.ipynb
   ```

---

## Project Structure

```
nyc-schools-sat-analysis/
│
├── notebook.ipynb        # Main analysis notebook
├── schools.csv           # Source dataset
└── README.md             # Project documentation
```

---

## Author

**Babs Akinsowon** — Data Analyst | [LinkedIn](www.linkedin.com/in/babatunde-a-607969139) | [GitHub](https://github.com/bakinsowon-boop)
