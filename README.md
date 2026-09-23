<!-- ============ HEADER ============ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=190&section=header&text=Sreeram%20Avasarala&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Data%20Scientist%20%E2%80%A2%20M.S.%20Data%20Science%20%40%20UT%20Arlington&descAlignY=58&descSize=16" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3200&pause=900&color=2C9FC9&center=true&vCenter=true&width=640&lines=I+don%27t+ship+a+single+accuracy+number.;Cross-validation.+Significance+tests.+SHAP.;Currently%3A+testing+whether+RAG+actually+reduces+hallucination.;Python+%E2%80%A2+PySpark+%E2%80%A2+Snowflake+%E2%80%A2+Scikit-learn" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://sreeramavasarala0-tech.github.io/portfolio-site/"><img src="https://img.shields.io/badge/Portfolio-0f2027?style=for-the-badge&logo=githubpages&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/venkata-nagasai-sreeram-avasarala-368560222"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:sreeramavasarala0@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=sreeramavasarala0-tech&style=for-the-badge&color=2c5364&label=PROFILE+VIEWS" />
</p>

---

### `>>> sreeram.describe()`

```python
class DataScientist:
    name       = "Venkata Nagasai Sreeram Avasarala"
    based_in   = "Apex, North Carolina, USA"
    education  = ["M.S. Data Science, UT Arlington (GPA 3.66)",
                  "B.E. Electronics & Communication, GRIET"]
    role_now   = "Graduate Research Assistant, UTA CSE (RAG vs. LLM hallucination)"

    workflow   = ["clean", "engineer features", "validate statistically",
                  "explain (SHAP)", "ship something a non-DS team can use"]

    beliefs    = {
        "an AUC without a CI": "is a rumor",
        "p-values":            "are a starting point, not a verdict",
        "a dashboard":         "is only done when the business can read it alone",
    }

    open_to    = ["Data Scientist", "ML Engineer", "AI Engineer",
                  "Data Analyst", "Data Engineer"]
```

---

### 🧪 Current Experiment: **CortexIQ**

> **Does retrieval-augmented generation make an LLM more accurate, or does it just make it sound more confident?**

| | |
|---|---|
| **H₀** | RAG and a no-retrieval baseline (same underlying model) produce equal accuracy and hallucination rates |
| **Design** | 5-stage RAG pipeline (embeddings → FAISS/ChromaDB vector search → prompt engineering) vs. baseline, head to head |
| **Test set** | 60 reference questions (40 answerable, 20 deliberately unanswerable) across 3 knowledge-base completeness levels |
| **Metrics** | Accuracy, hallucination rate, correct abstention |
| **Stats** | McNemar's paired significance test |
| **Status** | 🟡 Proposal finalized (v3), experimental phase up next |
| **Mentor** | Prof. Marika Apostolova, Dept. of CSE, UT Arlington |

---

### 📊 Selected Work

<table>
<tr>
<td width="50%" valign="top">

#### 🫀 Chronic Disease Prediction from Environmental Factors
Predicting diabetes and CVD risk by fusing **4 public datasets** (BRFSS, EPA AQS, Census ACS, USDA Food Access) across **14,245 respondents** and **25 Texas regions**.

`AUC-ROC 0.821 (diabetes)` `AUC-ROC 0.833 (CVD)`
`+0.025 PR-AUC, p < 0.0001` `31 → 11–18 features`

Nested RF / LogReg / XGBoost, stratified 5-fold CV, MICE-PMM imputation of 3,900+ missing values, SHAP with paired bootstrap validation. Separated environmentally driven CVD risk from lifestyle-driven diabetes risk for geo-targeted screening.

[**→ Repository**](https://github.com/sreeramavasarala0-tech/REPO-NAME)

</td>
<td width="50%" valign="top">

#### 📉 Customer Churn Prediction
A telecom churn classifier built to give retention teams **3 clear levers instead of 20+ ambiguous variables**.

`80% accuracy` `~0.85 AUC` `top-3 drivers isolated`

Correlation analysis and multicollinearity reduction surfaced contract type, tenure, and monthly charges. Streamlit + Plotly dashboards (confusion matrix, ROC, lift/gain) let non-technical teams evaluate the model and target at-risk customers on their own.

[**→ Repository**](https://github.com/sreeramavasarala0-tech/REPO-NAME)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🎓 PeerTut: AI-Powered Peer Tutoring Platform
A full-stack platform unifying tutor matching, session booking, ratings, and study planning.

`React 18` `Node/Express` `MySQL + Sequelize` `Gemini API` `WCAG 2.1 AA`

3-tier REST architecture with JWT + bcrypt auth. Turned manual scheduling into self-service, with Gemini-powered tutoring recommendations and full accessibility across desktop, tablet, and mobile.

[**→ Repository**](https://github.com/sreeramavasarala0-tech/REPO-NAME)

</td>
<td width="50%" valign="top">

#### 🧠 CortexIQ: RAG Hallucination Study
The controlled research study described above. Code, knowledge base, and evaluation harness will land here as the experiment runs.

`FAISS` `ChromaDB` `Embeddings` `McNemar's test`

[**→ Repository**](https://github.com/sreeramavasarala0-tech/REPO-NAME)

</td>
</tr>
</table>

---

### 🛠️ Toolkit

**Languages**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
</p>

**Machine Learning & AI**
<p>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-189AB4?style=flat-square" />
  <img src="https://img.shields.io/badge/SHAP-8A2BE2?style=flat-square" />
  <img src="https://img.shields.io/badge/Optuna-2C5364?style=flat-square" />
  <img src="https://img.shields.io/badge/RAG-FAISS%20%7C%20ChromaDB-0f2027?style=flat-square" />
</p>

**Data Engineering**
<p>
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
</p>

**Visualization & BI**
<p>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" />
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square" />
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square" />
</p>

**Web & Tools**
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
</p>

---

### 📈 GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=sreeramavasarala0-tech&show_icons=true&hide_border=true&theme=tokyonight&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sreeramavasarala0-tech&layout=compact&hide_border=true&theme=tokyonight" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=sreeramavasarala0-tech&hide_border=true&theme=tokyonight" />
</p>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=sreeramavasarala0-tech&hide_border=true&theme=tokyo-night" width="95%" />
</p>

---

### 📜 Certifications
`Google Analytics Individual Qualification (2025)` · `Java Programming, IIT Bombay (2025)` · `Programming Essentials in C, Cisco (2024)` · `Data Science for Engineering, NPTEL (2024)`

---

<p align="center">
  <i>"Show me the confidence interval."</i><br/>
  <b>Open to Data Science, ML, and AI roles. Let's talk.</b>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" />
</p>
