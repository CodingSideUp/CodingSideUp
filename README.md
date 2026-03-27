# Gurudarshan BN

Data Science & ML Engineer based in Mannheim, Germany. M.Sc. Applied Data Science & Analytics, SRH Hochschule Heidelberg (graduated Oct 2025).

I work across the full ML lifecycle — data engineering and wrangling, feature pipelines, model training and evaluation, and building dashboards that make results usable for non-technical stakeholders. My background covers demand forecasting, inventory analytics, materials informatics, and data platform engineering.

---

## Currently

**VASPP GmbH, Walldorf** — ML Engineer *(Jan 2026 – present)*

Building a production demand forecasting system on the Kaggle Favorita dataset — 125M+ real grocery transactions across 54 Ecuadorian stores (2013–2017). The work covers the full pipeline: exploratory data analysis on raw sales and promotional data, feature engineering (lag windows, rolling statistics, calendar signals, interaction terms), demand segmentation using the Syntetos-Boylan-Croston framework, training and hyperparameter optimisation of LightGBM and CatBoost models, quantile regression for uncertainty estimation, and a Streamlit frontend with SHAP explainability and an inventory control view.

Also working on inventory optimisation — translating forecast uncertainty bands into safety stock and reorder policies, and collaborating cross-functionally with other teams to frame and validate those policies.

→ [github.com/CodingSideUp/demand-forecasting](https://github.com/CodingSideUp/demand-forecasting)

---

## Experience

**Allianz Commercial, Frankfurt** — Business Analyst *(Jan 2025 – Jul 2025)*
Designed and developed complex ETL pipelines using Python and PySpark on Palantir Foundry. Performed data modelling and transformation on insurance portfolio data using Palantir Contour. Built DAX-based Power BI dashboards for business reporting.

**SRH Hochschule Heidelberg** — M.Sc. Applied Data Science & Analytics *(Oct 2023 – Oct 2025)*
Coursework in data engineering, data management, cloud infrastructure, ML, deep learning, neural networks (LSTM, CNNs), reinforcement learning, and model deployment. Thesis: comparing XGBoost against Crystal Graph Convolutional Neural Networks for bandgap prediction in metal-organic frameworks.

**VMware Software India, Bengaluru** — Senior Fulfillment Analyst *(Jun 2022 – Oct 2023)*
Sales forecasting for the cloud product portfolio. Built and maintained ML models for revenue prediction pipelines.

**Genpact India (client: GE Healthcare)** — Demand Analyst *(Jul 2019 – Jun 2022)*
Demand forecasting for medical equipment. Data wrangling, feature engineering, and Tableau reporting across the supply chain planning function.

**Bangalore Institute of Technology** — B.E. Telecommunications Engineering *(2015–2019)*

---

## Skills

**Languages:** Python, SQL, R

**ML / Modelling:** LightGBM, CatBoost, XGBoost, scikit-learn, PyTorch, PyTorch Geometric, statsmodels, SHAP, LSTM, neural networks, reinforcement learning, quantile regression, time-series forecasting

**Data Engineering:** pandas, NumPy, PySpark, DuckDB, DBT, parquet, MongoDB

**BI & Visualisation:** Power BI (DAX), Tableau, Plotly, Streamlit, matplotlib, seaborn

**Cloud & Infrastructure:** GCP, AWS, Docker, Git, GitHub Actions

**Platforms:** Palantir Foundry, Palantir Contour, Anthropic Claude API

---

## Projects

**[Material Science — Bandgap Prediction](https://github.com/CodingSideUp/Material-Science)** *(M.Sc. thesis)*
Compared XGBoost against Crystal Graph Convolutional Neural Networks (CGCNN) for predicting electronic bandgap in metal-organic frameworks. Dataset: QMOF database, 20,374 MOF crystal structures. Feature pipeline uses CIF-extracted geometry (lattice parameters, atomic coordinates) plus DFT-computed properties. CGCNN (PyTorch + PyTorch Geometric, CUDA-accelerated with automatic mixed precision) achieved R² ≈ 0.71 on a 4,075-sample held-out test set. SHAP analysis identifies which structural features drive predictions.

**[HushHush](https://github.com/CodingSideUp/HushHush)** — Talent recruitment platform built for a course project. Scrapes developer profiles from GitHub and Stack Overflow APIs, runs K-Means clustering on 8 repository and activity metrics to identify high-value candidates (silhouette-scored), then trains supervised classifiers (Random Forest, AdaBoost, XGBoost) on the cluster labels. Flask + MySQL backend with an HR dashboard for recruiter workflows and automated email outreach.

---

## Contact

📍 Mannheim, Germany
✉️ gdforbizz@gmail.com
🔗 [linkedin.com/in/gurudarshan-bn](https://www.linkedin.com/in/gurudarshan-bn)

Languages: English (C1), German (B1)
