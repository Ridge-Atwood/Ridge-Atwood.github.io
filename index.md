---
title: "Ridge Atwood | Data Science Portfolio"
css: styles.css
---

::: {.columns}

::: {.column width="65%"}
## I turn data into insights, models, and solutions for real-world problems.

I'm a Statistics student at **Brigham Young University** specializing in Data Science. I'm particularly interested in the intersection of data science, machine learning, AI, and business.

I enjoy working on problems where data and technology can improve decisions, predict outcomes, identify inefficiencies, or automate useful processes.

I've completed my Bachelor's and have started my **Master's in Statistics at BYU in Fall 2026**.

### What I'm Interested In

::: {.interest-box}
**Business & Data Science**  
Using data to improve decisions and identify opportunities.

**Machine Learning**  
Building models that predict outcomes and uncover patterns.

**AI & Automation**  
Developing systems that automate useful real-world tasks.

**Deep Learning**  
Building and understanding neural networks and improving how they learn.

**Applied Research**  
Turning statistical and machine learning research into practical improvements.
:::
:::

::: {.column width="35%"}
![Ridge Atwood](images/suit_profile_photo.jpeg){fig-align="center" width="80%"}
:::

:::

---

## Experience

### Graduate Research Assistant — Brigham Young University

**Jan 2026 – Present · Advised by Dr. Tom Kerby**

- Built a targeted-dropout method from scratch in PyTorch that uses information theory and PCA to choose which parts of a neural network to perturb, instead of dropping neurons at random.
- Compared no dropout, 10–50% dropout, Gaussian noise, and CoreX targeted perturbations on CIFAR-10 and SVHN across 5 random seeds; CoreX improved target-class accuracy by 1–3% with overall accuracy unchanged.
- Presented results at the Red Rock Data Science Conference 2026, and bring my own hypotheses and research questions to weekly meetings with my supervisor.

[Full write-up in Projects →](#neural-network-research-targeted-dropout)

### Teaching Assistant, Stat 469: Analysis of Correlated Data — Brigham Young University

**Jul 2026 – Present · Instructor: Dr. Matt Heaton**

- Support about 35 students in regression methods for spatial, temporal, and seasonal correlated data.
- Complete every assignment myself before grading, then grade roughly 105 submissions each week (about 1,260 per semester).

### Teaching Assistant, Stat 121: Introductory Statistics — Brigham Young University

**Jan 2025 – Apr 2026**

- Taught statistical concepts to 70+ students per session from non-technical, non-statistics majors.
- Reviewed about 72 homework sets and 6 exams, correcting errors and wording so the section lined up with another professor's.

---

## Projects

### 📦 Medline — Predicting Competitor Backorders

**Predictive Analytics · Business Strategy**

Built a predictive analytics approach to identify when competitor products were likely to go on backorder.

Built an ETL pipeline for more than 10 million rows of one year of inventory, sales, fulfillment, and backorder data, then used EDA, event studies, time series forecasting, feature engineering, and machine learning to model backorders.

A Lasso logistic regression model achieved an <span class="result">AUC of ~0.82</span>, identifying customer-level fulfillment problems as important early-warning signals.

The analysis was translated into strategies Medline could use to proactively position inventory and capture market share.

**Tools:** Python · pandas · NumPy · scikit-learn · XGBoost

[View Project →](https://github.com/Ridge42/Medline_Case_study)

---

### 🤖 Employee Scheduling Automation

**In Progress · Constraint Optimization · Business Automation**

Started from a real problem: a fast-food manager described building each schedule by hand, which takes 4–6 hours with constant changes.

Built a scheduler with OR-Tools CP-SAT that balances employee availability, preferences, and staffing requirements. It is designed to handle any number of employees and is currently tested on test data.

Next up is an AI agent layer to handle schedule changes, planned for February 2027.

**Tools:** Python · OR-Tools (CP-SAT) · Optimization

---

### 🎬 Movie Recommendation System

**Machine Learning · Neural Networks**

Built a movie recommendation system with a team of three to predict whether users would like movies, using 100,000+ MovieLens ratings from 610 users across 9,742 movies.

My role: I built the PyTorch neural network (user and movie embeddings) used for the final predictions, and the pandas pipeline that selected and augmented the data into the shapes our models needed.

The neural network achieved an <span class="result">F1 score of 0.897</span>, compared with 0.684 for logistic regression and 0.679 for KNN. The team also built an interactive Streamlit app to explore the recommendations.

**Tools:** Python · pandas · scikit-learn · PyTorch · Streamlit

[View Project →](https://github.com/chamiltonb8/STAT_486_final_proj/tree/main) · [Try the App →](https://stat486finalproj.streamlit.app/UMAP_view)

---

### 🔬 Neural Network Research — Targeted Dropout

**Research Assistant · BYU · Neural Networks**

Developing a new approach to neural network regularization that uses information theory to identify which parts of a neural network should be perturbed, rather than randomly dropping neurons like standard dropout.

I build and train neural networks in PyTorch and use information-theoretic methods to identify important factors in learned representations. I then selectively perturb those factors and evaluate how the changes affect model performance.

I compared a model with no dropout, standard dropout at 10–50%, Gaussian noise perturbations, and CoreX targeted perturbations on CIFAR-10 and SVHN across 5 random seeds. The results are consistent: CoreX outperforms the baselines on target-class accuracy by 1–3% while overall accuracy stays about the same, suggesting that targeted perturbation can be more effective than randomly removing information from the network. I presented this work at the Red Rock Data Science Conference 2026.

This research has given me hands-on experience with deep learning, neural network architectures, PyTorch, representation learning, information theory, experimental design, and large-scale model evaluation.

**Tools:** Python · PyTorch · CIFAR-10 · SVHN · PCA · Information Theory · TensorBoard

[View Research →](https://github.com/TomKerbyLab/LocalCorex_Target_Dropout)

---

### 🐀 New York Rat Case Competition

<span class="result">**2nd Place — Case Competition**</span>

Analyzed 31,312 NYC 311 rodent complaints from 2025 and joined them with housing and economic data for all 51 council districts (25 variables) to identify where rat activity was concentrated, what factors were associated with it, and how the city could respond.

Found that complaint volume did not always track confirmed rat activity: the districts with the most complaints were not always those with the highest confirmed-rat rates.

Used DBSCAN clustering (50 m / 1 hour) to flag nearby complaints with conflicting inspection outcomes, LASSO and linear regression to find housing-related predictors, and random forest modeling and leaflet maps to turn the data into actionable recommendations.

Recommended that the city send trap supplies to residents and communities who report rats so they can act right away, instead of dispatching one visit to check and another to exterminate. The city would set traps itself on public property.

**Tools:** R · tidyverse · sf · leaflet · dbscan · glmnet · ggplot2

[View Project →](https://github.com/Ridge42/rats_case_competition2026)

---

## Skills

Click a category to see the tools and examples of where I've applied them.

<details>
<summary><strong>Programming & Data Science</strong></summary>

| Skill | Example |
|---|---|
| **Python** | [Medline](https://github.com/Ridge42/Medline_Case_study) · [Neural Network Research](https://github.com/TomKerbyLab/LocalCorex_Target_Dropout) |
| **R** | [NYC Rat Case Competition](https://github.com/Ridge42/rats_case_competition2026) |
| **SQL** | Data querying and analysis |
| **pandas** | [Medline](https://github.com/Ridge42/Medline_Case_study) |
| **NumPy** | [Medline](https://github.com/Ridge42/Medline_Case_study) |
| **Excel** | Data analysis and business analysis |

</details>

<details>
<summary><strong>Machine Learning & Statistics</strong></summary>

| Skill | Example |
|---|---|
| **Regression** | [Medline](https://github.com/Ridge42/Medline_Case_study) · [NYC Rat Case Competition](https://github.com/Ridge42/rats_case_competition2026) |
| **Classification** | [Medline](https://github.com/Ridge42/Medline_Case_study) |
| **Random Forests** | [NYC Rat Case Competition](https://github.com/Ridge42/rats_case_competition2026) |
| **Neural Networks** | [Movie Recommendation System](https://github.com/chamiltonb8/STAT_486_final_proj/tree/main) · [Research](https://github.com/TomKerbyLab/LocalCorex_Target_Dropout) |
| **PyTorch** | [Movie Recommendation System](https://github.com/chamiltonb8/STAT_486_final_proj/tree/main) · [Research](https://github.com/TomKerbyLab/LocalCorex_Target_Dropout) |
| **PCA** | [Neural Network Research](https://github.com/TomKerbyLab/LocalCorex_Target_Dropout) |
| **Feature Engineering** | [Medline](https://github.com/Ridge42/Medline_Case_study) |
| **Information Theory** | [Neural Network Research](https://github.com/TomKerbyLab/LocalCorex_Target_Dropout) |
| **Statistical Analysis** | [Medline](https://github.com/Ridge42/Medline_Case_study) · [NYC Rat Case Competition](https://github.com/Ridge42/rats_case_competition2026) |
| **Time Series Forecasting** | [Medline](https://github.com/Ridge42/Medline_Case_study) |
| **Event Studies** | [Medline](https://github.com/Ridge42/Medline_Case_study) |
| **A/B Testing & Experimentation** | [Neural Network Research](https://github.com/TomKerbyLab/LocalCorex_Target_Dropout) |
| **Clustering (DBSCAN)** | [NYC Rat Case Competition](https://github.com/Ridge42/rats_case_competition2026) |
| **Constraint Optimization (OR-Tools CP-SAT)** | Employee Scheduling Automation (in progress) |

</details>

<details>
<summary><strong>Data Visualization & Analysis</strong></summary>

| Skill | Example |
|---|---|
| **Matplotlib** | [Medline](https://github.com/Ridge42/Medline_Case_study) |
| **Seaborn** | [Medline](https://github.com/Ridge42/Medline_Case_study) |
| **ggplot2** | [NYC Rat Case Competition](https://github.com/Ridge42/rats_case_competition2026) |
| **Leaflet** | [NYC Rat Case Competition](https://github.com/Ridge42/rats_case_competition2026) |
| **Data Visualization** | [NYC Rat Case Competition](https://github.com/Ridge42/rats_case_competition2026) · [Medline](https://github.com/Ridge42/Medline_Case_study) |
| **Tableau** | Coursework |

</details>

<details>
<summary><strong>Tools & Workflow</strong></summary>

| Skill | Example |
|---|---|
| **Git / GitHub** | [GitHub Profile](https://github.com/Ridge42) |
| **Jupyter Notebooks** | [Medline](https://github.com/Ridge42/Medline_Case_study) |
| **ETL** | [Medline](https://github.com/Ridge42/Medline_Case_study) · [NYC Rat Case Competition](https://github.com/Ridge42/rats_case_competition2026) |
| **VS Code** | Development environment |
| **APIs** | Data extraction and analysis |
| **Quarto** | This portfolio |

</details>

---

## Let's Connect

::: {.connect-box}
I'm interested in opportunities in data science, analytics, machine learning, and business-focused problem solving.

**Email:** [atwoodridge@gmail.com](mailto:atwoodridge@gmail.com)  
**Location:** Provo, Utah  

[GitHub](https://github.com/Ridge42) · [LinkedIn](https://www.linkedin.com/in/ridge-atwood)
:::