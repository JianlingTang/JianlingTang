## 👋 Hi, I'm Janet (Jianling) Tang

I'm a **machine learning and software engineer** who takes **POCs and ideas to production** — from **data pipelines and statistical models** to **tested Python packages** and **LLM agents deployed on the cloud**.

During my **PhD in Astrophysics at ANU**, I delivered projects **from research idea to deployed apps and pipelines**, and published **three papers in top-tier peer-reviewed journals**. Along the way I worked with large, noisy datasets and built my toolkit in **Bayesian inference, forward modelling and uncertainty quantification**.

I worked as a **full-stack web developer** at ADACS, and I hold the **AWS Certified Cloud Practitioner** and **AWS Certified Machine Learning Engineer – Associate** certifications. I care about systems that are **reproducible, tested and honest about their limits**.

📍 Sydney · 💼 **Open to ML / Software Engineer roles**

---

### 💻 What I Do

- 🤖 Build **LLM agent systems** with tool calling, grounded answers, deterministic fallbacks and human-in-the-loop approval
- 🧠 Train and ship **ML models** — from simulation-generated training data to a pip-installable model API
- 🗃️ Design **data pipelines and warehouses** — Airflow ETL, star schemas, data-quality gates, BI dashboards
- 📊 Apply **statistical modelling** — Bayesian inference, MCMC, forecasting with uncertainty bounds
- ⚙️ Engineer for production — **Docker, CI/CD, pytest, cloud deployment (GCP, AWS), HPC**

### 🌱 Currently building

- 🧭 **Career Lighthouse** — an AI app that turns real job-market data (Seek + LinkedIn, deduplicated and cleaned) into personalised study plans for international students, with its own **LLM-as-judge eval and guardrail layer** to limit hallucination
- 📈 Adding **monitoring and retraining** to my ML projects to close the full model lifecycle

### 📌 Selected Projects

- 🔥 **[Wildfire Ops Copilot](https://github.com/JianlingTang/wildfire-ops-copilot)** · [Live demo](https://wildfireops-tang-0606.web.app/)

  An AI operations console for Australian bushfire hotspots. A Gemini/ADK agent combines live hotspots, weather, official warnings and Elastic MCP evidence into one risk score. It falls back to deterministic logic when it can't ground an answer, and every public advisory waits for **human approval** before anything is sent.

  🛠 Tech Stack: Python, FastAPI, Next.js, Gemini, Google ADK, Elastic MCP, Cloud Run, Firebase, Docker, pytest

- 🔭 **[C-4 · Cluster Completeness Calculator](https://github.com/JianlingTang/C-4-Cluster-Completeness-Correction-Calculator-)** · [PyPI](https://pypi.org/project/cluster-completeness-pipeline/)

  An end-to-end pipeline from synthetic data injection → detection → photometry → **neural-network emulator**. It replaces a slow simulation loop: **50× faster** over a **10× extended** range, and the trained model ships as a `pip install` API.

  🛠 Tech Stack: Python, PyTorch, scikit-learn, NumPy, Docker, HPC, pytest

- 🏛️ **[Research Reporting Data Platform](https://github.com/JianlingTang/research-reporting-platform)**

  A reporting platform (synthetic data) that merges five messy sources (staff, grants, investigators, outputs, candidatures) into a DuckDB star schema. It resolves identities across sources and uses **six blocking data-quality gates** that flagged 768 issues before publication, with UAT cases traced back to requirements.

  🛠 Tech Stack: Python, Apache Airflow, DuckDB, SQL, Power BI, pytest

- 🎓 **[University Service Intelligence](https://github.com/JianlingTang/university-service-intelligence)**

  Service analytics on synthetic data that turns operational bottlenecks into owned actions: SQL curation, a star schema, a **12-week seasonal demand forecast with uncertainty bounds** (holdout WAPE), and a four-page Power BI report.

  🛠 Tech Stack: Python, SQL, Power BI, DAX, time-series forecasting

- 📄 **[Research Reproducibility Package](https://github.com/JianlingTang/tgkr2026b)**

  The reproducible analysis behind my research paper: Bayesian forward modelling with MCMC and completeness-corrected inference. Every figure and table is mapped to the code and data that produced it.

  🛠 Tech Stack: Python, emcee (MCMC), NumPy, pytest, CITATION.cff

### 📫 Let's connect

- 💌 Email: [tangjianling1999@gmail.com](mailto:tangjianling1999@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/jianling-janet-tang](https://www.linkedin.com/in/jianling-janet-tang/)
- 📚 Selected publication: [Tang, Grasha & Krumholz (2024), MNRAS 532, 4583](https://doi.org/10.1093/mnras/stae1799)
