# Hi there, I'm Saif

### Founding Engineer · Cloud Architect · AI Engineer

I build scalable, real-time backend systems and autonomous AI agents — the kind that have to survive concurrency, retries, and production traffic without falling over.

Currently building **[Plavio.ai](https://www.plavio.ai)** — architecting an agentic system that turns training content into game-based learning, on **AWS**, **LangGraph**, and **FastAPI**.

Previously delivered AI and cloud solutions for **Schneider Electric** and the **London School of Hygiene & Tropical Medicine**, and led UI/API test automation at **Deloitte**, lifting automated coverage from **15% → 75%**.

- Ask me about durable workflow engines, serverless architecture, LangGraph, or event-driven systems
- Reach me at **[[LinkedIn]](https://www.linkedin.com/in/saifrahmansyed/)** · **[plavio.ai](https://www.plavio.ai)**

---

### Tech Stack

- **Languages:** Python · Go (Golang) · Java · TypeScript / JavaScript · SQL
- **AI & Agents:** LangGraph · LangChain · RAG · OpenAI / LLMs · Agentic & Human-in-the-Loop Workflows
- **Backend & Data:** FastAPI · Next.js · Django · PostgreSQL · TimescaleDB · Prisma · Kafka
- **Cloud & DevOps:** AWS (Lambda, Step Functions, DynamoDB, ECS, SQS, Firehose) · Docker · CI/CD (Azure DevOps, Jenkins)
- **Architecture:** Serverless · Event-Driven · Microservices · WebSockets · RESTful APIs

---

### Featured Projects & Case Studies

#### 1. [Email Outreach Tool](https://github.com/saifs1315/email-outreach-tool)
**Campaign-Centric AI Sales Automation Platform**
*A production-ready outreach platform that generates and sends personalised sales emails with AI, while guaranteeing deliverability, rate-limit safety, and correct multi-day workflow execution.*
* **Tech Stack:** Next.js 16 (App Router, Server Actions), Inngest, Prisma 7, PostgreSQL (Neon), Resend, OpenAI, Supabase Auth, Shadcn UI.
* **Key Features:**
    * **Durable Workflow Engine:** Built on Inngest to handle multi-day waits, retries, and snoozing reliably across follow-up sequences.
    * **Race-Condition Safety:** Atomic status locks on the `Lead` entity ensure no lead is ever emailed twice — or chased after they've already replied.
    * **Smart Rate Limiting:** Respects per-campaign daily send limits, auto-queuing and snoozing excess emails to the next window.
    * **Inbound Reply Handling:** Integrated Resend webhooks detect replies and automatically halt follow-up sequences.
    * **Async at Scale:** CSV imports trigger background draft generation, so bulk imports never freeze the UI.

#### 2. [AgentFlow](https://github.com/saifs1315/AgentFlow)
**No-Code AI Agent Orchestration Platform**
*A full-stack application for building, visualising, and managing complex AI agent workflows via a drag-and-drop interface.*
* **Tech Stack:** Django (DRF & Channels), LangGraph, LangChain, React Flow, PostgreSQL.
* **Key Features:**
    * **Dynamic Graph Construction:** Drag-and-drop frontend (React Flow) that compiles into executable LangGraph workflows.
    * **Real-time Streaming:** WebSocket connections that visualise agent execution states and token streaming live.
    * **Human-in-the-Loop:** Interruptibility features letting users pause, review, and approve agent actions mid-execution.
    * **Extensible Architecture:** Modular backend allowing easy addition of new nodes and capabilities.

#### 3. [Data-Science-Portfolio](https://github.com/saifs1315/Data-Science-Portfolio)
**Predictive Modeling & NLP Analysis**
*A collection of data science projects exploring regression, classification, and advanced natural language processing.*
* **Tech Stack:** Python, Jupyter Notebooks, XGBoost, Transformers (Hugging Face), Beautiful Soup.
* **Key Projects:**
    * **Education Outcomes:** Predictive model flagging schools where Key Stage 5 students are at risk of poor post-education outcomes, to support data-driven interventions.
    * **Energy Forecasting:** Time-series forecasting and EDA on hourly energy consumption data using XGBoost.
    * **NLP & Sentiment Analysis:** Comparative analysis of NLTK's VADER vs. Transformers on Amazon Food Reviews, plus classification of vaccine tweets.
    * **Web Scraping:** Automated extraction of product data from Amazon using Beautiful Soup.

#### 4. [Resume-Job-Matcher](https://github.com/saifs1315/Resume-job-matcher)
**NLP-Powered Career Tool**
*An intelligent tool that bridges the gap between candidate profiles and job requirements using Natural Language Processing.*
* **Tech Stack:** Python, NLP Libraries, Vector Embeddings.
* **Key Features:**
    * Parses and structures unstructured resume data into analyzable formats.
    * Uses keyword extraction and similarity algorithms to score relevance between resumes and job descriptions.
    * Provides actionable feedback to optimise application success rates.

#### 5. [React Native Jobs](https://github.com/saifs1315/react_native_jobs)
**Cross-Platform Job Aggregator**
*A modern mobile application that streamlines the job search with a responsive UI and real-time data integration.*
* **Tech Stack:** React Native, JavaScript/TypeScript, RESTful APIs.
* **Key Features:**
    * Cross-platform mobile architecture (iOS/Android) for browsing and filtering job listings.
    * Integration with external Job APIs to fetch real-time employment data.
    * Optimised UI/UX components for seamless navigation and detailed job views.

---

### GitHub Stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=saifs1315&show_icons=true&theme=tokyonight" alt="Saif's GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=saifs1315&layout=compact&theme=tokyonight" alt="Top languages" />
</p>

---

### Education
* **MSc Management of Information Systems & Digital Innovation**, Warwick Business School *(Distinction)*
* **BTech Electronics & Instrumentation**, SRM Institute of Science and Technology *(Distinction)*
