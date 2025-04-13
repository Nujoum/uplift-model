# 🎮 Creative Gaming: Uplift Modeling

This project explores **uplift modeling** to measure and optimize the impact of targeted advertising in a simulated mobile gaming environment. Unlike traditional machine learning models that predict conversion likelihood, uplift models estimate the **incremental effect** of showing an ad — helping marketers prioritize users who are most likely to respond *because* of the treatment.


## 📌 Overview

The analysis is driven by two balanced datasets:
- `cg_organic_control`: Customers who did **not** receive an ad (control group)
- `cg_ad_random`: Customers who were randomly shown an ad (treatment group)

The goal is to:
- Build and compare several uplift models
- Evaluate performance using uplift and incremental response metrics
- Recommend the optimal customer segment to target for maximum impact


## 🧠 Key Features

- ✅ Data preparation with randomized control and treatment groups  
- 📈 Uplift modeling using:
  - Logistic Regression
  - Neural Networks
  - Random Forest
  - XGBoost
- 🔍 Performance analysis using uplift tables and plots
- 💰 Incremental profit extrapolation for targeting strategies
- ⚖️ Comparison with propensity-to-buy models
- 🤖 Integration of GenAI tools (e.g., ChatGPT) for research, coding, and reflection



## 🛠️ Technologies Used

- **Python** (Jupyter Notebooks)
- **Pandas**, **NumPy** for data manipulation
- **Scikit-learn** for machine learning models
- **XGBoost**, **Random Forest**, and **Neural Networks** (manual tuning)
- **pyrsm** for uplift-specific visualizations and performance tables
- **Git & GitHub** for version control and collaboration
- **Docker-compatible environment** (no external installations required)


## 🔑 Takeaways
- 🚫 Propensity models waste ad budget on users who’d convert anyway.
- 📉 Some users show negative uplift — targeting them can hurt performance.
- 💸 XGBoost and Neural Nets can meaningfully boost profits when tuned and validated.
- 🎯 Targeting the optimal segment size (not blindly using 25%) leads to significantly better results.
- 🤖 Using Generative AI tools helped validate ideas, improve productivity, and surface nuanced patterns faster.
