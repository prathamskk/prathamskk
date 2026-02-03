# Pratham Kamble
**AI Product Engineer | Production Systems & Data Infrastructure**

I specialize in bridging the gap between **AI research and enterprise production**. My work focuses on building auditable, GDPR-compliant data pipelines and reliable RAG systems for regulated environments.

---

### 🎯 Engineering Focus

* 🛡️ **Governance & Compliance:** Designing architectures that prioritize PII protection, GDPR adherence, and audit trails.
* 🏗️ **Reliability over Hype:** Moving beyond "it works on my machine" to implementing robust error handling and logging.
* 📉 **Business Impact:** deploying systems that solve specific business problems (Latency, Cost, Accuracy) rather than chasing novel architectures.

---

### 🛠️ Technical Stack

| Domain | Toolkit |
| :--- | :--- |
| **Languages** | <img src="https://skillicons.dev/icons?i=python,ts,bash" height="20"/> Python, TypeScript, SQL |
| **Data Eng** | <img src="https://skillicons.dev/icons?i=gcp,kafka,postgres" height="20"/> BigQuery, PySpark, Postgres (pgvector) |
| **AI Ops** | <img src="https://skillicons.dev/icons?i=pytorch,docker,git" height="20"/> RAG, LangChain, Docker, CI/CD |
| **Web** | <img src="https://skillicons.dev/icons?i=react,flask,fastapi" height="20"/> React, Flask, Streamlit |

---

### 📂 Featured Projects

#### **1. Enterprise Market Sentiment Engine**
*High-Throughput Ingestion System | Sense Worldwide*

> **The Challenge:** Ingest public market data without violating strict vendor rate limits or GDPR privacy laws.

* **Solution:** Built an asynchronous webhook architecture to decouple ingestion from processing.
* **Scale:** Successfully handles **140,000+ events/hour** with zero data loss.
* **Compliance:** Implemented deterministic ID generation to ensure data consistency and full GDPR compliance.

#### **2. RAG Competitor Intelligence Tool**
*Hallucination-Resistant Search | Personal Project*

> **The Challenge:** Standard RAG pipelines often hallucinate when context windows are exceeded or fragmented.

* **Solution:** Engineered a document chunking strategy that preserves thread continuity and context.
* **Tech:** Processed **3M+ records** using PySpark; stored in PostgreSQL (pgvector) for retrieval.
* **Outcome:** Reduced model hallucination.

#### **3. Secure Voice Analysis Platform**
*Privacy-First Inference | Personal Project*

> **The Challenge:** Process sensitive user audio data without sending PII to external cloud APIs.

* **Solution:** Integrated **OpenAI Whisper locally** for on-device inference.
* **Metric:** Built **Cosine Similarity** based automated scoring engine.

---

[LinkedIn](https://linkedin.com/in/prathamskk) • [Email](mailto:prathamskk@gmail.com)
