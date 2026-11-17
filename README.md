<div align="center">

# 👋 Hi, I'm Haotian (Tony) Liu

### Data Scientist · Machine Learning Engineer · Data Engineer

**M.S. in Analytics, University of Southern California**  
I build practical AI and data systems—from reliable pipelines and model evaluation to search APIs and interactive applications.

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=19&duration=3200&pause=1100&color=36BCF7&center=true&vCenter=true&width=700&lines=Search+%26+Learning-to-Rank+Systems;Python+%7C+SQL+%7C+Machine+Learning;LLM+Applications+%26+Data+Engineering;Building+End-to-End+AI+Products" alt="Typing animation" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haotianliutony/)
[![GitHub](https://img.shields.io/badge/GitHub-sprAyyyyy-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sprAyyyyy)
[![Featured Project](https://img.shields.io/badge/Featured_Project-Search_%26_Ranking-2563EB?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sprAyyyyy/ecommerce-search-ranking-system)

</div>

---

## 🔍 Featured Project: E-Commerce Search & Learning-to-Rank System

### [🚀 Explore the project, source code & benchmarks](https://github.com/sprAyyyyy/ecommerce-search-ranking-system)

An **eight-week, end-to-end e-commerce product search system** covering lexical, semantic and multimodal retrieval, learning-to-rank, cold-start evaluation, API serving and an interactive search interface.

The repository contains **28 Google Colab notebooks**, the **FastAPI + Streamlit application source**, a final technical report, experiment visualizations and real local execution evidence.

<div align="center">

[![Search system architecture](https://raw.githubusercontent.com/sprAyyyyy/ecommerce-search-ranking-system/main/assets/system_architecture.svg)](https://github.com/sprAyyyyy/ecommerce-search-ranking-system)

</div>

| **0.9297** NDCG@10 | **+15.75%** vs BM25 | **40.65 ms** mean | **49.27 ms** P95 |
|:---:|:---:|:---:|:---:|
| Fixed 200-query reranking evaluation | Relative lift on the **same** benchmark | Local 100-query API benchmark | Local 100-query API benchmark |

**What I implemented**

- **Data & retrieval:** product preprocessing and relevance labeling; **TF-IDF, BM25, SBERT + FAISS, CLIP**, and hybrid retrieval experiments.
- **Learning-to-rank:** a **29-feature LambdaMART** reranker, compared with XGBoost pointwise and ListNet; feature ablation and error analysis.
- **Cold-start strategies:** zero-shot and LLM-assisted relevance experiments, evaluated on a separate 45-query holdout.
- **System integration:** a **10,000-product FAISS index**, FastAPI `/health` and `/search` endpoints, a Streamlit demo, and Docker configuration.
- **Runtime validation:** launched the original application locally on **Windows / CPU** and completed **100/100 successful sequential API requests**, all under the 200 ms server-pipeline target.

**Tech stack:** `Python` · `Pandas` · `BM25` · `SBERT` · `FAISS` · `CLIP` · `LightGBM / LambdaMART` · `FastAPI` · `Streamlit` · `Docker`

<div align="center">

[![100-query measured latency](https://raw.githubusercontent.com/sprAyyyyy/ecommerce-search-ranking-system/main/benchmark_100_query_latency.png)](https://github.com/sprAyyyyy/ecommerce-search-ranking-system/blob/main/local_runtime_validation.md)

</div>

**[Code & notebooks](https://github.com/sprAyyyyy/ecommerce-search-ranking-system/tree/main/notebooks)** · **[FastAPI / Streamlit app](https://github.com/sprAyyyyy/ecommerce-search-ranking-system/tree/main/app)** · **[Runtime benchmark evidence](https://github.com/sprAyyyyy/ecommerce-search-ranking-system/blob/main/local_runtime_validation.md)** · **[Final technical report](https://github.com/sprAyyyyy/ecommerce-search-ranking-system/blob/main/docs/Amazon_Week8_Final_Technical_Report_Revised.pdf)**

<sub>**Evaluation note:** The 0.9297 NDCG@10 result is from an offline fixed-candidate reranking experiment; the 40.65 ms mean and 49.27 ms P95 are from a separate **warm-model, single-client (concurrency=1) local API benchmark**. These are not production SLAs or online relevance metrics. This is an independent portfolio project using public Amazon-related research data, not an official Amazon source-code release.</sub>

---

## 👨‍💻 About Me

- 🎓 **University of Southern California** — M.S. in Analytics (**4.0 / 4.0 GPA**).
- 🎓 **University of California, Davis** — background in **Economics & Statistics**.
- 🤖 Interested in **applied ML, information retrieval, LLM-powered applications, recommendation systems and data engineering**.
- ⚙️ Comfortable working across the full lifecycle: **ETL → feature engineering → modeling → evaluation → APIs → visualization**.
- 🐱 Outside of code: cat enthusiast, table tennis fan, and competitive **USPSA** shooter.

## 🛠️ Tech Arsenal

<details open>
<summary><b>💻 Languages, Data & Analytics</b></summary>
<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

</details>

<details open>
<summary><b>🧠 Machine Learning, Search & LLMs</b></summary>
<br>

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5C1B?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-29884A?style=flat-square)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![FAISS](https://img.shields.io/badge/FAISS-Vector_Search-4169E1?style=flat-square)
![LLMs](https://img.shields.io/badge/LLM-Applications-8B5CF6?style=flat-square)

</details>

<details open>
<summary><b>☁️ Cloud, Data Engineering & Deployment</b></summary>
<br>

![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</details>

---

## 🚀 Other Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧬 [Enhanced Clinical Trials AI Agent](https://github.com/sprAyyyyy/Enhanced-Clinical-Trials-AI-Analysis)

**LLMs · ClinicalTrials.gov · Gradio · Competitive Intelligence**

Developed an AI-assisted workflow for clinical trial data extraction, competitive analysis, and executive-ready research summaries.

[View repository](https://github.com/sprAyyyyy/Enhanced-Clinical-Trials-AI-Analysis)

</td>
<td width="50%" valign="top">

### 🏥 [Hospital Readmission Prediction](https://github.com/sprAyyyyy/Predicting-30-Day-Hospital-Readmissions-with-Vertex-AI)

**Vertex AI · Python · SMOTE · XGBoost**

Built a Google Cloud ML workflow for data preprocessing, class-imbalance handling, predictive modeling, and evaluation of hospital readmission risk.

[View repository](https://github.com/sprAyyyyy/Predicting-30-Day-Hospital-Readmissions-with-Vertex-AI)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🗺️ [Yelp Review & Network Analysis](https://github.com/sprAyyyyy/NLP-Review-Analysis)

**NLP · TextBlob · NetworkX · Geospatial Analysis**

Explored sentiment, review helpfulness, community structure, and geographic patterns in large-scale Yelp data.

[View repository](https://github.com/sprAyyyyy/NLP-Review-Analysis)

</td>
<td width="50%" valign="top">

### 👥 [Customer Segmentation](https://github.com/sprAyyyyy/Customer-Segmentation-Clustering-)

**K-Means · Scikit-learn · Statistics · Visualization**

Applied clustering and exploratory analysis to identify customer groups and support personalized marketing strategies.

[View repository](https://github.com/sprAyyyyy/Customer-Segmentation-Clustering-)

</td>
</tr>
</table>

## 💼 Experience Highlights

| Experience | Focus |
|:--|:--|
| **CABS — Data Science Intern** | Clinical-trial competitive intelligence, data integration, LLM-powered research tools and analytics. |
| **TechEquity AI — Data & Automation Intern** | Python/SQL data workflows, lead research automation, LLM-assisted outreach, and analytics dashboards. |
| **Orient Securities — Market Analysis Intern** | ABS/REIT analysis, financial research, and quantitative reporting. |

---

## 📊 GitHub Analytics

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=sprAyyyyy&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sprAyyyyy&layout=compact&theme=tokyonight&hide_border=true" alt="Most-used GitHub languages" />

</div>

<details>
<summary><b>🏆 GitHub achievements</b></summary>
<br>
<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=sprAyyyyy&theme=tokyonight&no-frame=true&margin-w=8&row=1" alt="GitHub achievements" />

</div>
</details>

---

<div align="center">

## 🤝 Let's Connect

*I enjoy turning complex data and research problems into measurable, useful software.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haotianliutony/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow_Me-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sprAyyyyy)

</div>
