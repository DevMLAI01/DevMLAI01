  <h1 align="center">Hi, I'm Saurabh Kumar Dewangan 👋</h1>

<h3 align="center">Technology Lead → Data & AI Platform Leader | 19 Years in Telecom & Data Engineering | Building Intelligent Agentic Systems</h3>

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

I'm a **Technology Lead with 19 years of experience** in Telecom and Data Engineering, now fully immersed in building **production-grade AI/ML systems and agentic workflows**.

My career has given me a rare combination — deep domain expertise in complex, large-scale systems (Telecom NOC, legacy data migrations, cloud infrastructure) paired with hands-on skills in **LLMs, multi-agent architectures, RAG pipelines, Azure Databricks, and LLM fine-tuning**. I don't just prototype — I build AI systems that solve real operational problems at enterprise scale.

- Currently building: **Azure Databricks Data Lakes · Autonomous AI Agents for Telecom & FinOps**
- Deepening expertise in: **LangGraph · Agentic RAG · LLM Fine-tuning (LoRA/PEFT) · MLOps · Databricks Unity Catalog**
- Targeting: **Senior AI/ML Engineer | Data & AI Platform Lead | AI Architect** roles in Canada & India
- Superpower: Bridging the gap between messy real-world enterprise data systems and modern AI solutions
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

## What I Bring to a Senior Data & AI Role

| Area | Experience |
|------|-----------|
| **Azure Data Platform** | Databricks Medallion Architecture (Bronze/Silver/Gold), Delta Lake, Unity Catalog, ADLS Gen2, AutoLoader, Azure Functions |
| **Agentic AI Systems** | Production LangGraph agents with RAG, HITL, self-correction loops, and tool-calling GPT-4o workflows |
| **LLM Fine-tuning** | LoRA/PEFT fine-tuning of LLaMA models for domain-specific enterprise tasks |
| **Enterprise Domain** | 19 years in Telecom NOC, data engineering, and large-scale cloud infrastructure |
| **Production Mindset** | End-to-end pipelines: anomaly detection to webhook to AI triage to incident report in under 60 seconds |
| **System Design** | Multi-agent orchestration, MCP protocol, RBAC, autonomous remediation pipelines |

---

## Let's Connect

I'm actively looking for **Senior AI/ML Engineer · Data & AI Platform Lead · AI Architect** roles in **Canada and India**.

If you're working on interesting AI problems — especially in Telecom, FinOps, Data Engineering modernization, or Agentic AI — I'd love to connect.

Reach me via [LinkedIn](https://www.linkedin.com/in/saurabhkumardewangan)

---

<p align="center">
  <i>"19 years of building systems that work at scale. Now building systems that think."</i>
</p>
