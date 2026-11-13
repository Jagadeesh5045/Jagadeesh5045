<img src="https://i.postimg.cc/2ywBFKPj/profile.jpg" align="right" width="220" alt="Jagadeeswara Rao Padala" />

# Hi there, I'm Jagadeeswara Rao Padala 👋

**Data Analyst | AI Engineer · MSc Artificial Intelligence @ Aston University**

I turn data into decisions: SQL, Python (pandas, NumPy) and Power BI for analysis, reporting and data quality, backed by an MSc in Artificial Intelligence (Merit, Aston University) and 2 years as a Python Developer building data pipelines and reporting workflows. My Pipeline Pulse ETL runs 17 data-quality checks in DuckDB and quarantined 503 bad rows; Churn-X, a Gradient Boosting churn model on ~5,000 synthetic telecom customers, scores test ROC-AUC 0.839 with SHAP explanations. On the AI side, my dissertation Code Sage AI is an agentic RAG code assistant, and RAG Eval Lab measures retrieval quality honestly (recall@k 0.9583, groundedness 0.9722 on a constructed adversarial set). I am seeking **Data Analyst** roles first, and AI Engineer roles, in the UK. Graduate visa from Dec 2026, no sponsorship required.

- 🔭 Currently building: **LLMON privilege guard** (12 Nov 2026), a guarded LLM pipeline demo of instruction and data separation, following the separation behind IBM's Granite LLMON previews (released 12 Nov 2026): trusted instructions are explicit referenced objects and untrusted data gets no instructional privilege, so injected imperatives in retrieved documents and tool outputs are quarantined in code (naive pipeline follows 4/4 injections, guarded pipeline 0/4, facts preserved 8/8, 17/17 tests passing) -> [daily/2026-11-12-llmon-privilege-guard](https://github.com/Jagadeesh5045/AI-builds/tree/main/daily/2026-11-12-llmon-privilege-guard)
- 🌱 Currently exploring: data analytics & BI reporting, agentic AI systems, LLM evaluation & groundedness
- 💬 Ask me about: SQL, data analysis, Python, Power BI, RAG, Machine Learning
- 📍 Birmingham, UK · open to relocating · Remote / Hybrid · Graduate visa from Dec 2026, no sponsorship required
- ⚡ Fun fact: my dissertation RAG system went head-to-head with ChatGPT on an unseen codebase — and held its ground with checkable citations

## 🛠️ Tech Stack

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-4A90E2?style=flat)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Data & BI:** SQL · Python (pandas, NumPy) · Power BI · Excel · DuckDB · ETL pipelines · data quality
**Machine learning:** scikit-learn · TensorFlow · PyTorch
**AI / LLM:** RAG systems · LangGraph · ChromaDB · Hugging Face
**Coursework / project level:** Tableau · dbt · Snowflake · Databricks · AWS · Azure · GCP · Airflow · Spark

## 🚀 Featured Projects

| Project | What it is |
|---|---|
| [**Pipeline Pulse**](https://github.com/Jagadeesh5045/Pipeline-pulse) | Python ETL and data-quality pipeline: 17 automated data-quality checks run in DuckDB, with 503 rows quarantined before they could reach the warehouse. Python, SQL, DuckDB. |
| [**Churn-X**](https://github.com/Jagadeesh5045/Churn-x) | Customer churn prediction with Gradient Boosting on ~5,000 synthetic telecom customers: test ROC-AUC 0.839, with SHAP explanations for the drivers behind each prediction. Python, scikit-learn. |
| [**sql-session-lab**](https://github.com/Jagadeesh5045/AI-builds/tree/main/projects/sql-session-lab) | Advanced SQL analytics over a seeded clickstream (6,965 events, 800 users, 92 days): gaps-and-islands sessionisation (2,207 sessions), session funnel (18.4% conversion), 7-day moving-average revenue with window frames, purchase cohort retention, and a recursive-CTE calendar spine; revenue reconciles three ways to £30,755.34; 9 tests green, stdlib only. SQL, SQLite, Python. |
| [**saas-kpi-board**](https://github.com/Jagadeesh5045/AI-builds/tree/main/projects/saas-kpi-board) | SaaS subscription KPI analytics — billing-shaped SQLite warehouse (714 customers, 5,246 snapshots, 18 months), named SQL KPI suite (MRR, logo and revenue churn, cohort retention, GRR 76.8% / NRR 95.2% at 12 months, channel LTV:CAC and CAC payback), generated analyst report and CSV extracts; 14 tests green, stdlib only. Python, SQLite, SQL. |
| [**retail-warehouse**](https://github.com/Jagadeesh5045/AI-builds/tree/main/projects/retail-warehouse) | Incremental star-schema warehouse in pure Python and SQLite: SCD Type 2 customer and product history, deduplication with late corrections winning, quarantine for unresolvable orders. 580 fact orders, £50,029.15 revenue, 14 tests green. |
| [**experiment-lab**](https://github.com/Jagadeesh5045/AI-builds/tree/main/projects/experiment-lab) | A/B testing and experimentation statistics toolkit — two-proportion z-test, Bayesian A/B, CUPED variance reduction (34.9% on average order value), SPRT early stopping and a peeking audit on a realistic 4,000-user checkout experiment (lift +1.84pp, p=0.0212). pandas, SciPy, matplotlib, pytest. |
| [**Code Sage AI**](https://github.com/Jagadeesh5045/code-sage-ai) | Agentic RAG code assistant (MSc dissertation) — Tree-sitter AST parsing across 12 languages, 13-state LangGraph orchestration, hybrid retrieval (dense + BM25 + cross-encoder re-rank), citation engine tracing claims to exact file:line, hallucination guard. Evaluated on a 25-query benchmark and compared like-for-like vs ChatGPT. Flask + Docker. |
| [**RAG Eval Lab**](https://github.com/Jagadeesh5045/Rag-Eval-lab) | Local RAG evaluation harness: BM25 + TF-IDF retrieval with reciprocal rank fusion over 10 AI/ML guides (11 chunks), scored on 12 questions: recall@k 0.9583 and groundedness 0.9722 on a constructed adversarial set. Python. |
| [**rag-router**](https://github.com/Jagadeesh5045/AI-builds/tree/main/flagship/rag-router) | Hybrid query router for RAG — a scikit-learn classifier routes each query to vector search, BM25, or NL→SQL over a DuckDB warehouse; routing accuracy 0.926, keyword recall@5 1.000, SQL answers 30/30 exact; latency/quality trade-off evals plus a FastAPI `POST /ask` demo. |
| [**mlops-credit**](https://github.com/Jagadeesh5045/AI-builds/tree/main/flagship/mlops-credit) | End-to-end MLOps for credit default prediction — JSON model registry, 90/10 canary deploy (challenger promoted only on +0.02 ROC-AUC), PSI drift monitoring with drift-triggered retraining. 5,000 synthetic applicants, champion ROC-AUC 0.6886, canary kept the champion, drift on income (PSI 0.3773) and late payments (PSI 1.7022) triggered retraining to v3. 4 tests green. |
| [**care-wait-analytics**](https://github.com/Jagadeesh5045/AI-builds/tree/main/flagship/care-wait-analytics) | Health-sector flagship pairing data analytics with AI: synthetic elective referral pipeline (6,075 raw rows, 10 quality checks, 75 quarantined) into a SQLite warehouse, SQL analytics (median wait 97 days, 26.4% breaching 18 weeks, a 28-day deprivation gap), a Gradient Boosting breach-risk model (ROC-AUC 0.8516) and a grounded briefing generator whose numbers are verified against the warehouse. 5 tests green. |
| [**cascade-cost-router**](https://github.com/Jagadeesh5045/AI-builds/tree/main/daily/2026-11-10-cascade-cost-router) | LLM cascade cost router: a cheap model answers first and only uncertain cases escalate to a frontier model. On a 50-case fixture the cascade scored 100% accuracy vs 52% for the cheap model alone, at 50.7% lower cost than frontier-only; 14/14 tests passing. Python. |
| [**ai-builds**](https://github.com/Jagadeesh5045/AI-builds) | Weekly AI builds + daily trending experiments — new project every Monday, new experiment every day. |

## 📊 GitHub Stats

![Jagadeesh's GitHub stats](https://github-readme-stats.vercel.app/api?username=Jagadeesh5045&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Jagadeesh5045&layout=compact&theme=radical)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Jagadeesh5045&theme=radical)

## 🌐 Connect with me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jagadeesh5045/)
[![Medium](https://img.shields.io/badge/Medium-000000?style=flat&logo=medium&logoColor=white)](https://medium.com/@padalajagadeesh578)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=flat&logo=googlechrome&logoColor=white)](https://jagadeesh5045.github.io/portfolio/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=Loygz-EAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0006-5399-4805)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:Padalajagadeesh578@gmail.com)
