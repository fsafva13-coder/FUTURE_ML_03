# 📄 Resume / Candidate Screening System
**Future Interns — Machine Learning Internship | Task 3**
`CIN: FIT/MAR26/ML6085` · `Repository: FUTURE_ML_03`

---

## 🔍 Overview

This project builds an **ML-powered resume screening system** that automatically reads candidate resumes, matches them against a job description, ranks them by overall fit, and highlights exactly which skills each candidate is missing.

Recruiters spend hours manually reading CVs. This system does it in seconds — scoring every candidate fairly using the same logic every time, with zero bias.

---

## 🎯 What This Project Does

- Screens 10 candidate resumes against an ML Engineer job description
- Extracts and matches 20 required skills per resume
- Calculates TF-IDF cosine similarity between each resume and the JD
- Generates a composite ranking score (skill + similarity + experience)
- Assigns candidates to tiers: Strong / Good / Partial / Weak Match
- Produces a skill gap heatmap showing exactly what each candidate is missing
- Outputs recruiter-ready shortlist and interview recommendations

---

## 📊 Results

### Final Candidate Rankings

| Rank | Candidate | Score | Tier |
|---|---|---|---|
| #1 | Sofia Martinez | 67.5 | 🟡 Good Match |
| #2 | Aisha Rahman | 66.0 | 🟡 Good Match |
| #3 | Yuna Kim | 53.6 | 🟠 Partial Match |
| #4 | Carlos Mendez | 53.5 | 🟠 Partial Match |
| #5 | Priya Nair | 49.4 | 🟠 Partial Match |
| #6 | Fatima Al-Hassan | 48.3 | 🟠 Partial Match |
| #7 | James Carter | 38.2 | 🟠 Partial Match |
| #8 | David Okafor | 30.1 | 🔴 Weak Match |
| #9 | Noah Williams | 27.1 | 🔴 Weak Match |
| #10 | Liam Thompson | 23.8 | 🔴 Weak Match |

### Scoring Formula
```
Final Score = Skill Match (40%) + JD Similarity (40%) + Experience (20%)
```

---

## 🗂️ Project Structure

```
FUTURE_ML_03/
│
├── FUTURE_ML_03.ipynb        # Main notebook (full pipeline)
├── screening_dashboard.png   # 4-chart screening dashboard
├── skill_gap.png             # Skill gap heatmap (all candidates)
└── README.md
```

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|---|---|
| Python 3.14 | Core language |
| Scikit-learn | TF-IDF, cosine similarity, scaling |
| Pandas & NumPy | Data handling & scoring |
| Matplotlib & Seaborn | Dashboard & heatmap visualizations |
| Regex (re) | Text cleaning |
| Jupyter Notebook | Development environment |

---

## ✨ Key Features Implemented

- ✅ Resume text cleaning & parsing
- ✅ Skill extraction & matching against 20 required skills
- ✅ TF-IDF cosine similarity between resumes and job description
- ✅ Composite scoring with weighted formula
- ✅ Candidate ranking with tier classification
- ✅ Skill gap heatmap (green = present, red = missing)
- ✅ 4-chart screening dashboard
- ✅ Recruiter shortlist & interview recommendations

---

## 💡 Business Value

This system helps recruiting teams by:

1. **Speed** — screens 100+ resumes in seconds instead of hours
2. **Consistency** — every candidate scored using the exact same criteria
3. **Transparency** — skill gap heatmap shows exactly why someone ranked where they did
4. **Actionability** — outputs a ready-to-use shortlist and priority interview list
5. **Scalability** — swap the job description and re-run for any role instantly

---

## 👩‍💻 About

**Intern:** Fathima Safva
**Program:** Future Interns Machine Learning Fellowship
**Duration:** 10/03/2026 – 10/04/2026
**LinkedIn:** [Future Interns](https://www.linkedin.com/company/future-interns/)
