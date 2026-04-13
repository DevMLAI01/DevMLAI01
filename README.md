  <h1 align="center">Hi, I'm Saurabh Kumar Dewangan 👋</h1>

<h3 align="center">Data & AI Leader | 19 Years Delivering at Enterprise Scale | Driving AI Adoption Across Data, Analytics & Engineering</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/saurabhkumardewangan" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/DevMLAI01" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <img src="https://img.shields.io/badge/Location-Calgary%2C%20Canada-red?style=for-the-badge&logo=google-maps&logoColor=white" alt="Calgary, Canada"/>
  <img src="https://komarev.com/ghpvc/?username=DevMLAI01&style=for-the-badge&color=blue" alt="Profile views"/>
</p>

---

## About Me

I'm a **Technology Lead with 19 years of enterprise experience** in Telecom and Data Engineering, transitioning into senior leadership roles at the intersection of **Data Analytics, Data Engineering, and AI adoption**.

I've spent nearly two decades owning complex, mission-critical systems — and I now apply that foundation to lead the design and delivery of **modern data platforms, AI-powered analytics pipelines, and intelligent agentic systems**. I bring both the strategic perspective to align data & AI investments with business outcomes, and the technical depth to architect and validate the solutions my teams build.

- Driving: **Enterprise AI adoption · Data platform modernisation · Agentic AI integration into business workflows**
- Architecture focus: **Azure Databricks Lakehouse · Medallion Architecture · Multi-agent LLM systems · RAG pipelines**
- Targeting: **Manager | Senior Manager | Architect** roles in **Data Analytics · Data Engineering · AI** in Canada & India
- Strength: Translating ambiguous business problems into scalable data and AI architectures — and shipping them
- Based in **Calgary, AB, Canada** | Open to remote and hybrid roles

---

## Featured Projects

### [Azure Telecom Data Lake + AI Triage Agent](https://github.com/DevMLAI01/Azure-Data-Lake-and-AI-Triage)
> **Medallion Architecture on Azure Databricks — anomaly detected to incident report in <60 seconds**

Production-style telecom data lake processing ~55K CDRs, 5K KPIs, and 70 unstructured NOC files through a full Bronze to Silver to Gold pipeline. Z-score SQL alert fires a webhook to an Azure Function, which runs a GPT-4o tool-calling loop that queries live Gold tables, searches NOC history, and writes structured Markdown incident reports directly to ADLS — fully automated, end-to-end.

`Azure Databricks` `Delta Lake` `AutoLoader` `Unity Catalog` `Azure OpenAI GPT-4o` `Azure Functions` `ADLS Gen2` `PySpark`

---

### [Telecom NOC AI Agent](https://github.com/DevMLAI01/telecom-noc-agent)
> **LangGraph + RAG + AWS Lambda — 45-90 min NOC workflow compressed to <60s**

4-node self-correcting state machine that autonomously investigates alarms,
retrieves vendor SOPs via semantic search, drafts resolution tickets, and
safety-audits its own output before returning — deployed on AWS Lambda with
a live REST endpoint. **35 tests · 70% coverage · 3-retry self-correction loop.**

`LangGraph` `GPT-4o` `AWS Lambda` `DynamoDB` `RAG` `LangSmith`

---

### [Autonomous SRE & Cloud FinOps Orchestrator](https://github.com/DevMLAI01/autonomous-sre-finops)
> **Multi-agent system targeting EC2 instances: CPU <5% over 7 days AND cost >$100/month**

5-node orchestrator that scans AWS, classifies resources via RAG (faithfulness >= 0.85),
generates Terraform PRs, and enforces mandatory human approval before any change —
zero autonomous `terraform apply`, full audit trail on every decision. **$0 infrastructure cost.**

`LangGraph` `Gemini` `Qdrant` `MCP` `Terraform` `Ragas` `HITL`

---

### [Production RAG Chatbot with RBAC & Guardrails](https://github.com/DevMLAI01/rag-rbac-chatbot)
> **Role-based document access · guardrails · cost monitoring · Ragas evaluation pipeline**

Production-grade RAG chatbot where retrieval is filtered by user roles — different personas see
different document subsets. Integrates guardrails to prevent hallucination and prompt injection,
tracks per-query token costs, and ships a Ragas evaluation harness for faithfulness and
answer relevancy scoring.

`RAG` `RBAC` `LangChain` `Guardrails` `Ragas` `ChromaDB` `Python`

---

### [Legacy-to-Cloud LLM Fine-Tuner](https://github.com/DevMLAI01/Legacy-to-Cloud-tuner)
> **LLaMA 3.1-8B fine-tuned with LoRA — 16GB model to ~5GB, only 0.8% of weights trained**

Domain-adapted fine-tuning pipeline for Netezza SQL to PySpark translation using
4-bit NF4 quantization and LoRA (rank-16). Runs on a free Colab T4 GPU and exports
to GGUF format for production deployment via Ollama or llama.cpp.

`LLaMA 3.1` `LoRA/PEFT` `Unsloth` `bitsandbytes` `GGUF` `TRL`

---

### [Text-to-SQL Multi-Agent BI Orchestrator](https://github.com/DevMLAI01/text-to-sql_Mult_Agent-bi-orchestrator)
> **3 Claude models · 5 security guards · live on AWS EC2 · self-correcting SQL pipeline**

4-node pipeline routing natural language through Claude Haiku (retrieval),
Opus (SQL generation with Pydantic guards), SQLAlchemy executor, and Sonnet
(business narrative) — with AST-based table allow-listing and automatic
self-correction for failed queries.

`LangGraph` `Claude` `Streamlit` `SQLAlchemy` `Pydantic` `AWS EC2`

---

## Tech Stack

### AI / ML
![LangGraph](https://img.shields.io/badge/LangGraph-FF6B35?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![Claude](https://img.shields.io/badge/Anthropic_Claude-D4A76A?style=flat-square&logo=anthropic&logoColor=black)

### Data Engineering & Lakehouse
![Azure Databricks](https://img.shields.io/badge/Azure_Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-0073FF?style=flat-square&logo=databricks&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache_Iceberg-336791?style=flat-square&logo=apache&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

### Cloud & Infrastructure
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Azure Functions](https://img.shields.io/badge/Azure_Functions-0062AD?style=flat-square&logo=azurefunctions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

### MLOps & Evaluation
![LangSmith](https://img.shields.io/badge/LangSmith-FF6B35?style=flat-square&logo=python&logoColor=white)
![Ragas](https://img.shields.io/badge/Ragas-Evaluation-blue?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DevMLAI01&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="160" alt="GitHub Stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DevMLAI01&layout=compact&theme=tokyonight&hide_border=true" height="160" alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=DevMLAI01&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</p>

---

## What I Bring to a Data & AI Leadership Role

| Area | What I Deliver |
|------|---------------|
| **Strategic Leadership** | Define data & AI roadmaps aligned to business goals; translate C-suite priorities into architecture decisions and delivery plans |
| **AI Adoption & Diffusion** | Drive enterprise-wide AI adoption — from use-case identification and build-vs-buy decisions to team enablement and governance frameworks |
| **Data Platform Architecture** | Design and deliver cloud-native lakehouses (Azure Databricks, Medallion Architecture, Delta Lake, Unity Catalog) that scale to enterprise data volumes |
| **AI & Analytics Systems** | Architect production LangGraph agents, RAG pipelines, agentic triage systems, and LLM fine-tuning workflows that solve real operational problems |
| **Cross-functional Delivery** | 19 years leading engineers, aligning stakeholders, and shipping complex data systems in high-stakes Telecom and cloud environments |
| **Engineering Excellence** | HITL guardrails, Ragas evaluation, observability (LangSmith/MLflow), PII masking, RBAC — building AI systems that are safe and auditable, not just functional |

---

## Let's Connect

I'm actively targeting **Manager · Senior Manager · Architect** roles in **Data Analytics · Data Engineering · AI** in **Canada and India**.

If your organisation is modernising its data platform, scaling analytics capabilities, or figuring out how to responsibly adopt AI at enterprise scale — that is exactly the kind of challenge I want to help solve.

Reach me via [LinkedIn](https://www.linkedin.com/in/saurabhkumardewangan)

---

<p align="center">
  <i>"19 years of building systems that work at scale. Now building systems that think."</i>
</p>
