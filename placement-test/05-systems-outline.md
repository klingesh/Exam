# 💻 SYSTEMS — OUTLINE

**6 topics.** The shortest section in the PDF, and mostly conceptual rather than technical.

> 📌 Outline only — the structure and the points worth noting. Expand the ⭐ items into proper notes.

---

## WHAT'S IN THIS SECTION

| # | Topic | Weight |
|---|---|---|
| 1 | Introduction to MIS, DSS/EIS, SDLC | ⭐⭐⭐ |
| 2 | ERP architecture, modules, implementation; BPR | ⭐⭐⭐ |
| 3 | Project life cycle, cost/time/scope, Agile | ⭐⭐ |
| 4 | DBMS, normalization, data warehousing, OLTP vs OLAP, data mining | ⭐⭐⭐ |
| 5 | The four analytics types, regression, decision trees | ⭐⭐ |
| 6 | Cloud (SaaS/IaaS/PaaS), chatbots, cybersecurity, LLM/AI, RPA | ⭐⭐ |

> 💡 **You are not expected to write code.** This section tests whether you know what each system/technology *is*, what it's *for*, and how the categories differ. Definitions and comparison tables are the whole game.

---

## TOPIC-BY-TOPIC OUTLINE

### 1. Introduction to MIS ⭐⭐⭐
- **MIS** — concepts and definition
- **Types of information systems** — TPS, MIS, DSS, EIS/ESS, ERP, KMS
- **Information systems in functional areas** — HR, finance, marketing, operations
- **DSS** (Decision Support System) — supports semi-structured decisions
- **EIS/ESS** (Executive Information System) — dashboards and summaries for top management
- **DSS vs MIS vs EIS** ⭐ — know which management level each serves
- **SDLC** (System Development Life Cycle) ⭐ — phases: **planning → analysis → design → development → testing → implementation → maintenance**
- **SDLC models** — Waterfall, Spiral, Prototype, Agile

### 2. ERP & BPR ⭐⭐⭐
**ERP**
- **Architecture** — typically three-tier (presentation / application / database); centralized common database
- **Modules** — finance, HR, manufacturing, SCM, CRM, sales & distribution, inventory
- **Implementation cycle** — pre-evaluation → planning → gap analysis → reengineering → configuration → testing → training → go-live → post-implementation support
- **Benefits** — single source of truth, integration, reduced redundancy, better reporting
- **Challenges** — high cost, long timelines, change resistance, customization difficulty, high failure rate
- Popular ERPs worth naming — SAP, Oracle, Microsoft Dynamics, Tally (SME)

**BPR**
- **BPR** (Business Process Reengineering) — fundamental rethinking and **radical redesign** of processes for **dramatic** improvement
- Coined by **Hammer & Champy**; four keywords: **fundamental, radical, dramatic, process**
- **Steps & methodologies** — identify process → map as-is → analyse → redesign to-be → implement → monitor
- **ERP vs BPR** ⭐ — technology-enabled integration vs process-level transformation; whether you redesign the process first or fit it to the software
- **BPR vs continuous improvement (TQM/Kaizen)** — radical leap vs incremental gains

> 📎 There are much fuller BPR notes in this repo already (with real bankruptcy case studies) at [pgpm-sem2/4_Business_Process_Reengineering.docx](../pgpm-sem2/4_Business_Process_Reengineering.docx) — useful if BPR carries weight in your paper.

### 3. Project Life Cycle ⭐⭐
- **Phases** — **initiation → planning → execution → monitoring & control → closure**
- **The triple constraint** ⭐ — **cost, time, scope** (quality in the middle); changing one affects the others
- **Scope management** — scope creep, WBS (Work Breakdown Structure)
- **Time management** — Gantt chart, CPM, PERT, critical path
- **Cost management** — budgeting, cost baseline
- **Methodologies** — Waterfall vs **Agile**
- **Agile** — iterative sprints, incremental delivery, adaptive to change; Scrum roles and ceremonies at a high level
- **Waterfall vs Agile** ⭐ — sequential and fixed vs iterative and flexible

### 4. Basic DBMS Concepts ⭐⭐⭐
- **DBMS** basics — **tables** (rows/records and columns/fields), **primary key**, **foreign key**
- **Queries** — the idea of SELECT/WHERE/JOIN at a conceptual level
- **Normalization** ⭐ — removing redundancy; **1NF, 2NF, 3NF** and what each removes
- **Data warehousing** — subject-oriented, integrated, time-variant, non-volatile; **ETL**; data warehouse vs data mart vs data lake
- **APIs** — how systems talk to each other
- **OLTP vs OLAP** ⭐⭐ — transaction processing vs analytical processing; this comparison is very likely to be asked
- **Data mining techniques** ⭐:
  - **Association** — finds items that occur together (market basket analysis)
  - **Classification** — assigns records to predefined categories
  - **Clustering** — groups similar records with no predefined labels
  - *(Classification vs clustering = supervised vs unsupervised — a common trick question)*

### 5. Digital Transformation & Analytics ⭐⭐
- **The four types of analytics** ⭐ — this is the single most reusable framework in the section:

| Type | Question it answers |
|---|---|
| **Descriptive** | What happened? |
| **Diagnostic** | Why did it happen? |
| **Predictive** | What will happen? |
| **Prescriptive** | What should we do about it? |

- **Predictive modelling tools** — **regression** (predicts a numeric value) and **decision trees** (rule-based splits, easy to interpret)
- **Digital transformation** — using digital technology to fundamentally change how a business operates and delivers value

### 6. Cloud, AI, Cybersecurity & RPA ⭐⭐
- **Cloud service models** ⭐:

| Model | You get | Example |
|---|---|---|
| **IaaS** | Infrastructure — servers, storage | AWS EC2 |
| **PaaS** | Platform to build/deploy on | Google App Engine |
| **SaaS** | Ready-to-use software | Gmail, Salesforce |

- **Cloud deployment models** — public, private, hybrid
- **Cybersecurity basics** — **CIA triad** (Confidentiality, Integrity, Availability); threats: phishing, malware, ransomware, social engineering; controls: firewall, encryption, MFA
- **AI basics** — **AI ⊃ ML ⊃ DL** (know the nesting)
- **LLM** (Large Language Model) — trained on large text corpora to generate and understand language; generative AI
- **RPA** (Robotic Process Automation) ⭐ — software bots automating repetitive rule-based tasks
- **RPA vs AI** ⭐ — RPA follows fixed rules (does not learn); AI learns from data
- **Chatbots in enterprise systems** — rule-based vs AI/NLP-driven

---

## ⭐ IMPORTANT TO NOTE

### Abbreviations — expand every one of these

| Abbr | Expansion |
|---|---|
| **MIS** | Management Information System |
| **TPS** | Transaction Processing System |
| **DSS** | Decision Support System |
| **EIS / ESS** | Executive Information System / Executive Support System |
| **SDLC** | System Development Life Cycle |
| **ERP** | Enterprise Resource Planning |
| **BPR** | Business Process Reengineering |
| **DBMS** | Database Management System |
| **OLTP** | Online Transaction Processing |
| **OLAP** | Online Analytical Processing |
| **ETL** | Extract, Transform, Load |
| **API** | Application Programming Interface |
| **NF** | Normal Form (1NF, 2NF, 3NF) |
| **WBS** | Work Breakdown Structure |
| **CPM / PERT** | Critical Path Method / Program Evaluation and Review Technique |
| **SaaS / PaaS / IaaS** | Software / Platform / Infrastructure as a Service |
| **AI / ML / DL** | Artificial Intelligence / Machine Learning / Deep Learning |
| **LLM** | Large Language Model |
| **RPA** | Robotic Process Automation |
| **CIA** | Confidentiality, Integrity, Availability |

### Frameworks & sequences to know
| Item | Content |
|---|---|
| **SDLC phases** | Planning → Analysis → Design → Development → Testing → Implementation → Maintenance |
| **Project life cycle** | Initiation → Planning → Execution → Monitoring & Control → Closure |
| **Triple constraint** | Cost, Time, Scope |
| **Four analytics types** | Descriptive → Diagnostic → Predictive → Prescriptive |
| **Cloud models** | IaaS, PaaS, SaaS |
| **Data mining techniques** | Association, Classification, Clustering |
| **Normalization** | 1NF → 2NF → 3NF |
| **BPR keywords** | Fundamental, Radical, Dramatic, Process |
| **AI nesting** | AI ⊃ ML ⊃ DL |
| **CIA triad** | Confidentiality, Integrity, Availability |
| **ERP implementation** | Planning → gap analysis → configuration → testing → training → go-live → support |

### "Difference between" pairs — prepare as tables
- **OLTP vs OLAP** ⭐ (most likely question in the section)
- **ERP vs BPR** ⭐
- **Waterfall vs Agile** ⭐
- **Classification vs Clustering** ⭐ (supervised vs unsupervised)
- **RPA vs AI** ⭐
- MIS vs DSS vs EIS
- Data warehouse vs Data mart vs Data lake
- SaaS vs PaaS vs IaaS
- AI vs ML vs DL
- BPR vs TQM/continuous improvement
- Primary key vs Foreign key

**Where marks concentrate:** the abbreviation list, SDLC, ERP modules and implementation, OLTP vs OLAP, the three data mining techniques, the four analytics types, and the cloud service models. Nearly all of it is definition-and-comparison recall — which makes this the fastest section to prepare of the five.

---

⬅️ [Back to index](README.md) &nbsp;|&nbsp; 📄 [Syllabus](00-syllabus-verbatim.md)
