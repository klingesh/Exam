# HR — Topic 13: AI in HR Functions

AI in Recruitment, Training, Performance and Engagement; Ethical Considerations; HRIS and AI Integration.

---

## 1. What is AI in HR? (Basic Idea)

**Artificial Intelligence (AI)** is the ability of machines to perform tasks that normally need human intelligence — learning, reasoning, recognising patterns and understanding language. **AI in HR** means applying those capabilities to people processes.

**Everyday analogy:** A recruiter reading 1,000 CVs is doing pattern-matching — slowly, and getting more tired and inconsistent with each one. AI does the same pattern-matching in seconds, identically every time. That is the promise. The catch is that it will also repeat any bias in the patterns it learned from — identically every time.

### Get the nesting right ⭐
```
ARTIFICIAL INTELLIGENCE (AI)          ← the broad field
   └── MACHINE LEARNING (ML)          ← systems that learn patterns from data
          └── DEEP LEARNING (DL)      ← ML using multi-layer neural networks
                 └── GENERATIVE AI / LLMs  ← generate text, code, images
```
Also know: **NLP** (Natural Language Processing) — how machines read and interpret human language, which is what powers CV parsing, chatbots and sentiment analysis.

### Why HR is a natural fit for AI
| HR characteristic | Why AI helps |
|-------------------|-------------|
| **High volume, repetitive** work | Screening, scheduling, answering the same queries |
| **Data-rich** | Applications, appraisals, attendance, surveys, payroll |
| **Pattern-based** decisions | Who will succeed, who is likely to leave |
| **Text-heavy** | CVs, feedback, survey comments, policies |
| Heavy **administrative** load | Frees HR time for the strategic layer *(see [Topic 3](03-hrm-planning-roles-and-responsibilities.md))* |

---

## 2. AI in Recruitment and Selection ⭐⭐

| Application | What it does |
|-------------|-------------|
| **AI-powered CV screening** | Parses and ranks CVs against the job description; shortlists in seconds |
| **Candidate sourcing / matching** | Scans databases and platforms to find passive candidates who fit |
| **Chatbots** | Answer candidate FAQs 24/7, collect basic details, pre-screen, schedule interviews |
| **Automated scheduling** | Coordinates calendars across panels without email chains |
| **Video interview analysis** | Assesses recorded answers (content, and sometimes tone/expression — **highly controversial**) |
| **Gamified & adaptive assessments** | Tests that adjust difficulty and score automatically |
| **Job-advert optimisation** | Flags biased or exclusionary wording ("young", "aggressive", "he") |
| **Predictive quality-of-hire** | Estimates likely performance and tenure from historical hiring data |
| **Fraud / duplicate detection** | Spots inconsistent or plagiarised applications |

### Benefits vs risks ⭐

| Benefits | Risks |
|----------|-------|
| **Speed** — days of screening in minutes | **Algorithmic bias** learned from historical data |
| **Scale** — thousands of applications handled | Good candidates rejected for **non-obvious reasons** |
| **Consistency** — same criteria applied every time | **"Black box"** decisions that cannot be explained |
| Lower **cost per hire** | Candidates **gaming keywords** to beat the parser |
| Better **candidate experience** (instant responses) | Loss of human judgement on potential and culture fit |
| Frees recruiters for relationship-building | Legal exposure under emerging AI regulation |

### ⚠️ The canonical case study — Amazon's scrapped recruiting tool
Amazon developed an experimental AI CV-screening tool and **abandoned it (reported in 2018)** after finding it **penalised women**. Trained on a decade of largely male CVs, the model learned that male-associated patterns predicted "success" — for example, downgrading CVs containing the word "women's" (as in "women's chess club captain").

> 🔑 **The lesson, and the single best point you can make on this topic:** AI does not remove bias — it **learns, scales and automates** the bias in its training data. A biased human affects the candidates they personally see; a biased algorithm affects **every** candidate, consistently and invisibly. **"Garbage in, garbage out" becomes "bias in, bias at scale out."**

---

## 3. AI in Training and Development ⭐

| Application | What it does |
|-------------|-------------|
| **Personalised learning paths** | Recommends content based on role, skill gaps, goals and past learning |
| **Adaptive learning** | Adjusts difficulty and pace in real time to the learner's responses |
| **Skill-gap analysis** | Maps the current skill inventory against future requirements — automating part of **TNA** *(see [Topic 5](05-recruitment-selection-and-training.md))* |
| **AI-driven coaching** | Conversational coaching, practice simulations, nudges and reminders |
| **Content generation** | Drafts modules, quizzes, summaries and translations |
| **Learning-experience platforms (LXP)** | "Netflix-style" recommendation of learning content |
| **Language & communication practice** | Real-time feedback on speaking, writing, pronunciation |
| **Effectiveness measurement** | Correlates learning completion with performance outcomes — helping reach **Kirkpatrick Levels 3 and 4** |

> 💡 **Where AI genuinely changes the game:** traditional training is one-size-fits-all because personalising it for 5,000 people was impossible. AI makes **mass personalisation** economically feasible for the first time — and it can push evaluation beyond "did they like it?" (Level 1) toward measured behaviour and results.

---

## 4. AI in Performance Management ⭐

| Application | What it does |
|-------------|-------------|
| **Continuous feedback analysis** | Analyses feedback text for themes, tone and recurring issues |
| **Goal tracking** | Monitors progress against KPIs/OKRs automatically from system data |
| **Predictive performance analytics** | Flags employees likely to over- or under-perform, so support arrives early |
| **AI-assisted review writing** | Drafts appraisal narratives from evidence and notes |
| **Bias detection in ratings** | Detects rating patterns by gender, location or manager — supporting **calibration** *(see [Topic 7](07-performance-management.md))* |
| **Real-time nudges** | Prompts managers to give feedback, hold 1-to-1s or recognise achievements |
| **Skills inference** | Infers actual skills from work output rather than self-declared profiles |

> ⚠️ **The key caution:** performance management is fundamentally a **conversation about a human being's contribution and future**. AI can supply better evidence, spot patterns a manager would miss, and draft the paperwork. It should not deliver the verdict. Using an algorithmic score to decide promotions or terminations without meaningful human review is both ethically indefensible and increasingly unlawful.

---

## 5. AI in Employee Engagement and Retention ⭐⭐

| Application | What it does |
|-------------|-------------|
| **Sentiment analysis** | NLP on survey comments, feedback and (with consent) internal communication to gauge mood |
| **AI-driven pulse surveys** | Short, frequent, adaptive surveys that ask smarter follow-up questions |
| **Attrition / flight-risk prediction** | Models who is likely to resign, and why, from tenure, pay position, promotion history, engagement and manager data |
| **HR helpdesk chatbots** | Answer leave, payroll and policy queries instantly, 24/7 |
| **Personalised retention actions** | Recommends the intervention most likely to work for that individual |
| **Internal mobility matching** | Matches employees to internal openings and projects — retention through opportunity |
| **Onboarding assistants** | Guide new joiners through their first 90 days |
| **Wellbeing / burnout signals** | Flags overwork patterns (meeting load, after-hours activity) |
| **Recognition prompts** | Suggests when and whom to recognise |

### How attrition prediction is actually used
```
1. Model flags a cohort at high flight risk
2. HR investigates the DRIVERS (pay below midpoint? no promotion in 4 years?
   new manager? high overtime?)
3. Targeted action: pay correction, career conversation, role change, workload fix
4. Measure whether the intervention reduced actual attrition
```
> ⚠️ **The ethical trap:** using flight-risk scores **against** employees — passing them over for projects or promotion because "they might leave anyway" — is a self-fulfilling prophecy and a serious misuse. Prediction should trigger **support**, never penalty.

---

## 6. AI Across the Employee Lifecycle — summary

| Stage | AI application |
|-------|---------------|
| **Workforce planning** | Demand forecasting, scenario modelling, skills supply projection |
| **Attract** | Job-advert optimisation, targeted sourcing, employer-brand analytics |
| **Hire** | CV screening, chatbots, assessments, scheduling, quality-of-hire prediction |
| **Onboard** | Onboarding assistants, document automation, buddy matching |
| **Develop** | Personalised learning, skill-gap mapping, AI coaching |
| **Perform** | Goal tracking, feedback analysis, bias detection, calibration support |
| **Reward** | Pay benchmarking, pay-equity gap detection, incentive modelling |
| **Engage** | Sentiment analysis, pulse surveys, recognition prompts |
| **Retain** | Attrition prediction, internal mobility matching |
| **Exit** | Exit-interview text analysis, trend detection, knowledge capture |

---

## 7. Ethical Considerations of AI in HR ⭐⭐⭐

This is where the marks are. HR decisions affect livelihoods, so the ethical bar is higher than in most AI applications.

| Issue | The problem | What HR must do |
|-------|------------|-----------------|
| **Algorithmic bias** | Models trained on biased history reproduce and scale discrimination | Regular **bias audits**; test outcomes by gender, age, region, disability; diverse and representative training data |
| **Transparency / explainability** | "Black box" models cannot explain why a candidate was rejected | Prefer explainable models for high-stakes decisions; be able to state the reasons |
| **Privacy and consent** | Monitoring, sentiment analysis and biometric data are highly intrusive | Clear notice; lawful basis; **data minimisation**; no covert monitoring *(see [Topic 11](11-labour-law-and-legal-requirements.md))* |
| **Human oversight** | Fully automated hiring or firing removes accountability | Keep a **human in the loop** for every consequential decision |
| **Accountability** | "The algorithm decided" is not a defence | Named human owner accountable for every AI-assisted decision |
| **Data quality** | Poor or thin data produces confident nonsense | Validate, clean and audit inputs; know the model's limits |
| **Over-reliance / deskilling** | Managers stop exercising judgement | Train managers to challenge AI output, not defer to it |
| **Proxy discrimination** | Neutral variables (postcode, college, name, career gaps) act as stand-ins for protected traits | Test for proxies explicitly; remove or control for them |
| **Consent and candidate rights** | Candidates often don't know AI is assessing them | Disclose AI use; offer a route to human review |
| **Job displacement** | Automation of HR administrative roles | Reskill and redeploy the people whose work is automated |
| **Surveillance culture** | Productivity monitoring erodes trust | Apply the **proportionality** test: is it necessary, transparent and minimal? |
| **Vendor risk** | Third-party tools may be biased or insecure | Due diligence, contractual audit rights, security review |

### The regulatory landscape (know these exist)
| Regulation | Relevance |
|-----------|-----------|
| **EU AI Act** | Classifies AI used in **employment and worker management as "high-risk"**, triggering obligations on risk management, data governance, transparency and human oversight |
| **GDPR Article 22** | Right not to be subject to a decision based **solely** on automated processing where it has legal or similarly significant effects |
| **NYC Local Law 144** (in force 2023) | Requires an annual **independent bias audit** of Automated Employment Decision Tools, plus candidate notice |
| **Illinois AI Video Interview Act** | Requires notice, explanation and consent for AI analysis of video interviews |
| **DPDP Act, 2023** (India) | Consent, purpose limitation and security obligations for employee personal data |

> ⚠️ AI regulation is moving quickly and phased differently by jurisdiction. Cite these as examples of the **direction of regulation** and verify the current status rather than asserting fixed rules.

### The principles that should govern AI in HR
```
1. FAIRNESS          — test for and correct discriminatory outcomes
2. TRANSPARENCY      — disclose that AI is used, and be able to explain decisions
3. HUMAN OVERSIGHT   — a person decides, informed by AI; AI never decides alone
4. PRIVACY           — collect the minimum, with notice and lawful basis
5. ACCOUNTABILITY    — a named human owns every outcome
6. PURPOSE           — use AI to support employees, not merely to police them
7. AUDITABILITY      — log inputs, outputs and overrides so decisions can be reviewed
```

> 🎯 **The strongest single line for an exam answer:** *"AI should support the HR decision, not make it. Efficiency gained at the cost of fairness is not a gain — because in HR, the cost of an unfair decision is a person's career."*

---

## 8. HRIS and AI Integration ⭐⭐

### What an HRIS is
An **HRIS (Human Resource Information System)** is the central software system that stores and processes all employee data and automates HR transactions. **HRMS/HCM** are broader terms for the same category.

### Typical modules
```
CORE HR         Employee master data, org structure, documents
PAYROLL         Salary processing, statutory deductions, payslips
TIME            Attendance, leave, shifts, overtime
RECRUITMENT     ATS — requisitions, applications, pipeline
ONBOARDING      Document collection, task workflows
PERFORMANCE     Goals, appraisals, feedback, calibration
LEARNING        LMS — courses, completion, certification
COMPENSATION    Salary structures, increment cycles, benefits
ANALYTICS       Dashboards, reports, metrics
SELF-SERVICE    ESS/MSS — employee and manager portals
```

### Why integration matters
AI is only as good as the data it can reach. Its value depends on the HRIS being the **single source of truth**.

| Requirement | Why |
|-------------|-----|
| **Single source of truth** | Contradictory headcount figures make every model unreliable |
| **Data quality and completeness** | Missing or stale fields silently distort predictions |
| **System integration** | Payroll, ATS, LMS and performance data must connect via **APIs** — otherwise analysis stops at departmental boundaries |
| **Consistent definitions** | If "attrition" is calculated three different ways, nothing is comparable |
| **Historical depth** | ML needs years of data to learn genuine patterns |
| **Access control** | Sensitive data must be role-restricted even as it is analysed |
| **Audit trail** | Needed to review and defend AI-assisted decisions |

### Common integration challenges
Legacy systems with no APIs · data scattered across spreadsheets · duplicate and conflicting records · inconsistent metric definitions across locations · poor adoption (managers don't update the system, so data decays) · privacy constraints on combining datasets · vendor lock-in · **HR teams lacking analytics skills to interpret output**

### The build sequence — why order matters
```
1. CLEAN DATA          ← foundation. Without it, everything above is unreliable
2. INTEGRATED SYSTEMS  ← connect ATS, HRIS, payroll, LMS, performance
3. RELIABLE REPORTING  ← consistent, agreed definitions and dashboards
4. ANALYTICS           ← diagnostic: why is this happening?
5. AI / PREDICTION     ← only now does prediction become trustworthy
```
> 🔑 **The most common organisational mistake:** buying an AI tool at step 5 while still at step 1. AI layered on messy, disconnected data produces confident, precise, wrong answers — and because they look sophisticated, they get believed.

---

## 9. What AI Cannot Do

| AI is good at | AI is poor at |
|---------------|--------------|
| Processing volume at speed | **Judgement in novel situations** |
| Finding patterns in large datasets | Understanding **context** and individual circumstances |
| Consistency and tirelessness | **Empathy** in a grievance, a bereavement, a termination |
| Prediction from history | Predicting genuine **change** (history is not always prologue) |
| Drafting and summarising | **Accountability** for a decision |
| Flagging anomalies | Negotiating, persuading, building trust |

> 💡 **The realistic conclusion:** AI **augments** HR rather than replacing it. It absorbs the administrative layer — which is exactly what frees HR to move up to the strategic layer, the theme of [Topic 14](14-traditional-vs-modern-hr.md). The parts of HR that are irreducibly human — judgement, empathy, negotiation, accountability — are the parts that become **more** valuable, not less.

---

## ✅ Quick Recap (Topic 13)

- **Nesting: AI ⊃ ML ⊃ DL ⊃ Generative AI/LLMs.** **NLP** powers CV parsing, chatbots and sentiment analysis.
- **Recruitment:** CV screening, sourcing, chatbots, scheduling, video analysis, job-advert de-biasing, quality-of-hire prediction.
- **Training:** personalised and adaptive learning, skill-gap mapping (automating TNA), AI coaching, content generation — enables **mass personalisation**.
- **Performance:** goal tracking, feedback analysis, predictive analytics, **rating-bias detection**, calibration support. AI informs; the human decides.
- **Engagement/retention:** sentiment analysis, pulse surveys, **attrition prediction**, HR chatbots, internal mobility matching. Prediction must trigger **support, not penalty**.
- ⭐ **AI does not remove bias — it scales it.** **Amazon's scrapped CV tool (2018)** penalised women because it learned from male-skewed historical data. *"Bias in, bias at scale out."*
- **Ethics:** bias · transparency/explainability · privacy and consent · **human in the loop** · accountability · data quality · proxy discrimination · over-reliance · surveillance · vendor risk.
- **Regulation:** **EU AI Act** treats HR AI as **high-risk**; **GDPR Art. 22** limits solely automated decisions; **NYC Local Law 144** mandates bias audits; **DPDP Act 2023** in India.
- **HRIS** = the central people-data system; AI depends on it being the **single source of truth**, connected by **APIs**.
- **Build order: clean data → integration → reporting → analytics → AI.** Skipping to AI on bad data is the classic failure.
- **AI augments, it doesn't replace.** Judgement, empathy, negotiation and accountability stay human — and grow more valuable.

➡️ **Next:** [Topic 14 — Traditional vs Modern HR Models](14-traditional-vs-modern-hr.md)
