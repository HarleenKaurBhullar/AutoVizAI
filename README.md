# AutoVizAI — Automated Data Analysis with Multi-Agent Intelligence

**AutoVizAI** is an **intelligent multi-agent system** designed to automate the process of exploratory data analysis (EDA). By leveraging multiple specialized agents, this project allows users to **load any dataset, clean it, engineer features, and generate meaningful visualizations** automatically — no manual coding required.

---

## 🧠 Core Concept & Value

Traditional data analysis is **time-consuming and requires technical expertise**. **AutoVizAI** addresses this by using **AI-powered agents** to perform key steps of data analysis:

* **Load Agent** → Loads datasets and manages session data
* **Clean Agent** → Automatically removes duplicates, fills missing values, caps outliers, and converts data types
* **Feature Engineering Agent** → Suggests and applies transformations or new features based on dataset and visualization goals
* **Visualization Agent** → Automatically generates charts (histograms, boxplots, correlation matrices, categorical comparisons)
* **Inference Agent** → Recommends the most meaningful visualizations and highlights patterns for insights

**Central Idea:** Automatically produce critical visualizations for any dataset uploaded by the user.

**Value:** Makes data analysis accessible, fast, and reproducible for beginners, researchers, and professionals alike.

---

## 🔍 Problem Being Solved

Manual EDA can be:

* Repetitive and error-prone
* Dependent on programming and statistical knowledge
* Slow for large or unfamiliar datasets

This system **reduces human effort** and produces **actionable insights and visualizations** with minimal intervention.

---

## 🏗️ Multi-Agent Architecture

| Agent | Role |
| :--- | :--- |
| Load Agent | Loads CSV/Excel files into a session-managed DataFrame |
| Clean Agent | Generates Python code to clean the dataset automatically |
| Feature Engineering Agent | Generates Python code to transform or create features |
| Inference Agent | Suggests the most relevant visualizations |
| Visualization Agent | Generates visualizations using Matplotlib & Seaborn |

**Workflow:**

1.  Load dataset → **Load Agent**
2.  Clean dataset → **Clean Agent**
3.  Feature transformations → **Feature Engineering Agent**
4.  Suggest visualizations → **Inference Agent**
5.  Generate plots → **Visualization Agent** 

[Image of multi-agent data analysis workflow diagram]


---

## 🛠️ Tech Stack

* **Python**
* **Pandas, NumPy** (data manipulation)
* **Matplotlib, Seaborn** (visualization)
* **Google ADK** (agent orchestration and LLM interaction)
* **Dotenv** (for API key management)

---

