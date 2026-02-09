
# 🧭 User Journey Health Dashboard

A product analytics case study simulating how a company's product data science team might analyze user behavior across a funnel. This project models a typical user journey—Signup → Follow → Content Creation → Retention —using simulated data to track engagement, identify drop-offs, and support data-driven product decisions.

---

## 🎯 Goals

- Track core product funnel conversion rates
- Analyze segment-level drop-offs (by platform, country, referral)
- Simulate retention trends and anomalies
- Provide PM-style recommendations based on metrics

---

## 🧪 Funnel Stages

| Stage           | Definition                                    |
|-----------------|-----------------------------------------------|
| `signup`        | User creates an account                       |
| `follow_user`   | User follows at least one person              |
| `post_created`  | User creates content                          |
| `retained_7d`   | User returns 7+ days after signup             |

---

## 📊 Metrics & Visualizations

- Funnel conversion chart (bar or sankey)
- Segment heatmaps (drop-off by country/platform)
- Retention curves
- Anomaly flags (sudden drops)

---

## 📁 Project Structure
meta-user-journey-dashboard/
├── data/
│ └── simulated_user_events.csv
├── notebooks/
│ └── 01_funnel_analysis.ipynb
│ └── 02_segment_dropoff.ipynb
├── dashboard/
│ └── streamlit_app.py ← optional
├── README.md
└── requirements.txt


---

## 🛠️ Tools

- Python (pandas, seaborn, plotly, numpy)
- Streamlit (for optional dashboard)
- GitHub + Jupyter

---

## 🔗 Preview / Use Case

This project showcases end-to-end product analytics capabilities and is designed to simulate real-world decision support at a product company. It can be used as part of a technical portfolio or job application.


