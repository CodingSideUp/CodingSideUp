# Gurudarshan BN

Data Science & ML Engineer based in Mannheim, Germany. M.Sc. Applied Data Science & Analytics from SRH Hochschule Heidelberg (2023–2025). Currently building demand forecasting and AI products at VASPP GmbH in Walldorf.

My background spans retail demand forecasting, supply chain analytics, and ML pipeline engineering — starting at Genpact on GE Healthcare equipment forecasting, through VMware's cloud revenue prediction work, a stint at Allianz Commercial on insurance data, and now building end-to-end ML systems for enterprise clients.

---

## What I'm working on

**[Demand Forecasting — Favorita](https://github.com/CodingSideUp/demand-forecasting)**

Built a demand forecasting system on the Kaggle Favorita dataset — 125M transactions from Ecuadorian grocery stores (2013–2017). The interesting part wasn't the models themselves but the segmentation: I ran SBC classification on 1,920 store-item pairs and routed each to a specialist model based on its demand pattern (smooth, erratic, intermittent, lumpy). Intermittent series — the ones that sell on maybe 30% of days — get a two-stage model: a binary classifier to predict whether demand occurs at all, then a magnitude regressor for when it does.

Final numbers on a 78,304-row held-out set: LightGBM Segmented at 23.52% WAPE, CatBoost M2 Full at 23.22% WAPE. Naive lag-7 baseline was 40.8%. The gap narrows on the intermittent segment specifically — the two-stage model gets 18.44% WAPE there vs ~27% from the smooth model used as a fallback on lumpy series.

The dashboard is a three-tab Streamlit app: model comparison with SHAP waterfall explainability, an inventory replenishment view with P10/P90 quantile bands, and a forward forecast through Christmas 2017 with four years of historical actuals overlaid.

---

## Experience

**VASPP GmbH, Walldorf** — ML Engineer / AI Products *(Oct 2025 – present)*
Building enterprise ML demo systems for retail demand forecasting. Full pipeline from feature engineering and segmentation through LightGBM/CatBoost training to Streamlit dashboard.

**Allianz Commercial, Frankfurt** — Business Analyst *(Jan 2025 – Jul 2025)*
Data analysis and reporting on insurance portfolio data. Power BI dashboards, SQL-based data extraction, stakeholder reporting.

**SRH Hochschule Heidelberg** — M.Sc. Applied Data Science & Analytics *(Oct 2023 – Oct 2025)*
Time-series forecasting, deep learning, statistical modelling. Thesis project on weather impact forecasting at Paretos GmbH.

**VMware Software India, Bengaluru** — Senior Fulfillment Analyst *(Jun 2022 – Oct 2023)*
Sales forecasting for the cloud product portfolio. Built and maintained ML models feeding revenue prediction pipelines.

**Genpact India (client: GE Healthcare)** — Demand Analyst *(Jul 2019 – Jun 2022)*
Demand forecasting for medical equipment. Data cleaning, feature engineering, Excel/Python modelling, dashboard reporting in Tableau.

**Bangalore Institute of Technology** — B.E. Telecommunications Engineering *(2015–2019)*

---

## Skills

**Languages:** Python, SQL, R (basic)

**ML / Modelling:** LightGBM, CatBoost, XGBoost, scikit-learn, PyTorch, statsmodels, SHAP, quantile regression, time-series forecasting

**Data Engineering:** pandas, NumPy, PySpark, DuckDB, DBT, parquet, MongoDB

**BI & Visualisation:** Power BI, Tableau, Plotly, Streamlit

**Cloud & Infrastructure:** GCP, AWS, Docker, Git, GitHub Actions

**Other:** Palantir Contour, Anthropic Claude API

---

## Other projects

**Weather Impact on Demand Forecasting** — Paretos GmbH (M.Sc. thesis project). Investigated how weather signals improve short-term retail demand forecasts. Built on real retail transaction data.

**Hush Hush Recruiter** — Matching algorithm for an anonymous job-matching platform. Candidate-job ranking with skill-based similarity scoring.

---

## Contact

📍 Mannheim, Germany
✉️ gdforbizz@gmail.com
🔗 [linkedin.com/in/gurudarshan-bn](https://www.linkedin.com/in/gurudarshan-bn)

Languages: English (C1), German (B1)
