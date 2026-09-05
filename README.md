<div align="center">

![Status](https://img.shields.io/badge/Status-Open%20to%20Software%2FIT%20Internships-2E7D32?style=flat-square&labelColor=1a1a1a)

# Stephan

### Software / IT Developer — Full-Stack · AI &amp; Data · Systems Integration

3rd-year BIT undergraduate who ships complete systems, not exercises — multi-agent and RAG platforms on FastAPI + Gemini, full-stack ML products with real auth and analytics, and a Ballerina integration service for a WSO2 internship application.

[Portfolio](https://zyphronix-space.github.io/) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/stephan-wasalathathrige) &nbsp;·&nbsp; [Email](mailto:stephanwasalathanthrige@gmail.com) &nbsp;·&nbsp; [GitHub](https://github.com/Zyphronix-space)

</div>

<br>

> **Building** — Full-stack AI platforms (ResearchOS: multi-agent research workspace with projects/sources/full auth; DocMind: multi-user RAG document intelligence) and end-to-end ML products (real-estate analytics, recruiter/candidate matching)
>
> **Learning** — Spring Boot &amp; J2EE, to round out the Java side
>
> **Interested in** — applying ML and LLM agents inside full-stack products, and service integration in the style Ballerina/WSO2 are built for
>
> **Open to** — Software / IT internships

<br>

## Featured Projects

### Tier 1 — Flagship

<table>
<tr><td width="100%">

**ResearchOS** — multi-agent AI research workspace

Ask a research question and watch it turn into a cited report, live: a Planner breaks it into sub-questions, concurrent Researchers investigate them with real tools (web search, page fetch, calculator), a Reviewer checks the pooled findings for gaps and contradictions, and a Writer produces the final report — wrapped in a full workspace (projects, saved sources, research history, an agent-status page), not a single-shot Q&A demo.

**Stack:** Python · FastAPI · Gemini structured output · SQLite · React (Vite) · React Router

**Highlights**
- Real concurrent researchers with real fan-in — live progress merged into one ordered event stream via an `asyncio.Queue`, plus a bounded Reviewer reflection loop
- Structured sources (title + URL exactly as seen in a tool result, never a bare link) with relevance derived from the researcher's own confidence — no source metadata is ever invented
- A real per-user data model (projects, sessions, sources) behind email/password + Google auth, with every lookup ownership-checked (cross-user access 404s, not 403s)

[Repository](https://github.com/Zyphronix-space/ai-research-agent) &nbsp;·&nbsp; [Live Demo](https://delightful-desert-0af6ccc00.7.azurestaticapps.net) <sub>(hosted on Azure — may take ~10s to wake up)</sub>

</td></tr>
<tr><td width="100%">

**DocMind** — AI document intelligence platform

Upload documents and get answers grounded in real per-page citations — a full multi-user platform, not a single-shot RAG demo: JWT auth, per-user collections, persisted conversations, and an honest retrieval + faithfulness evaluation framework.

**Stack:** Python · FastAPI · SQLAlchemy · Chroma · Gemini · React (Vite) · Tailwind CSS

**Highlights**
- Per-page PDF chunking so every citation points at an exact page, not just "the document"
- JWT auth, per-user collections, and conversations scoped to one document or a whole collection
- Retrieval hit-rate + labeled Gemini-judge faithfulness scoring — disclosed as an approximation, not oversold as a rigorous eval

[Repository](https://github.com/Zyphronix-space/doc-chat-rag) &nbsp;·&nbsp; [Live Demo](https://polite-coast-06d46f000.6.azurestaticapps.net) <sub>(hosted on Azure — may take ~10s to wake up)</sub>

</td></tr>
<tr><td width="100%">

**House Price Predictor** — AI real-estate analytics platform

Predicts California housing prices and explains every prediction with a tree-path contribution breakdown, backed by comparable-property search, a what-if simulator, and an investment calculator — not just a form-and-answer demo.

**Stack:** Python · scikit-learn · FastAPI · SQLAlchemy · React (Vite)

**Highlights**
- Hand-rolled Saabas-method tree-path explainability (mathematically exact) after `shap`'s heavy dependencies broke the Azure build
- k-NN comparable-property search over the full 20,640-row reference dataset
- JWT auth with per-user prediction history, not local-only demo state

[Repository](https://github.com/Zyphronix-space/house-price-predictor) &nbsp;·&nbsp; [Live Demo](https://house-price-predictor-three-nu.vercel.app)

</td></tr>
<tr><td width="100%">

**City Snapshot Service** — WSO2 internship contribution project

A Ballerina integration service: give it a city, it geocodes it, then fetches live weather and currency exchange rates concurrently and merges them into one response.

**Stack:** Ballerina · Concurrent HTTP calls (`start`/`wait`) · HTML/CSS/JS frontend

**Highlights**
- Three public APIs (geocoding, weather, forex) orchestrated in one service
- Weather and forex calls run concurrently via Ballerina's `start`/`wait`, not sequentially
- Built specifically for WSO2's "real-world project implementation" contribution track

[Repository](https://github.com/Zyphronix-space/city-snapshot-service) &nbsp;·&nbsp; [Live Demo](https://delightful-mud-0758db600.7.azurestaticapps.net) <sub>(hosted on Azure — may take ~10s to wake up)</sub>

</td></tr>
</table>

### Tier 2 — Strong Projects

| Project | What it does | Stack |
|---|---|---|
| **[VinuCare](https://github.com/Zyphronix-space/VinuCare)** ([demo](https://witty-stone-0dc7a5c00.7.azurestaticapps.net/)) | Full-stack pet-care platform — appointment booking, an online pet-product shop, and role-based Doctor/Nurse/Admin dashboards with live staff notifications over WebSockets | React · Node.js/Express · MySQL · Socket.io · Google OAuth |
| **[RecruitAI](https://github.com/Zyphronix-space/resume-job-matcher)** ([earlier demo](https://salmon-ground-0609b6e00.7.azurestaticapps.net)) | Recruiter/candidate workspace built around one explainable matching pipeline — job postings, applicant ranking, shortlisting, and live analytics, not just a single CV-vs-JD score. *(Demo still runs the project's earlier single-score version — the rebuild isn't deployed yet.)* | Python · sentence-transformers · FastAPI · React |
| **[SpamShield](https://github.com/Zyphronix-space/sms-spam-classifier)** | Full-stack AI message-security platform — auth, persisted history, a feedback loop, CSV batch scanning, and model-performance analytics around a TF-IDF + Naive Bayes classifier, behind a Ballerina API gateway | Python · scikit-learn · Ballerina · FastAPI · React |

### Tier 3 — Foundations

<details>
<summary>Earlier coursework and desktop projects (click to expand)</summary>
<br>

| Project | What it is |
|---|---|
| **[furniture-management-system](https://github.com/Zyphronix-space/furniture-management-system)** | Role-based desktop inventory/order system — Java, Swing, MySQL |
| **[library-management-system](https://github.com/Zyphronix-space/library-management-system)** | Desktop library system with borrow/return tracking — Python, Tkinter, MySQL |
| **[Film-vault-](https://github.com/Zyphronix-space/Film-vault-)** | Static movie/TV showcase site with genre browsing and a watchlist — HTML/CSS/JS |
| **[DSA](https://github.com/Zyphronix-space/DSA)** | Data structures &amp; algorithms exercises — Java |
| **[java-stack-array](https://github.com/Zyphronix-space/java-stack-array)** | Stack implementation on a raw array — Java |

</details>

<br>

## Developer Journey

**Foundation** — OOP, data structures, SQL fundamentals
&nbsp;&nbsp;↓
**Full-Stack Development** — React/Node/MySQL apps with real auth and real-time features (VinuCare)
&nbsp;&nbsp;↓
**Applied Systems** — role-based desktop management systems (Java Swing, Tkinter)
&nbsp;&nbsp;↓
**AI, Data &amp; Integration** — full-stack ML platforms, multi-agent and RAG systems, Ballerina-based service integration
&nbsp;&nbsp;↓
**Next** — Spring Boot / J2EE, deeper backend architecture

<br>

## Tech Stack

**Languages** &nbsp; ![Java](https://img.shields.io/badge/-Java-black?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript&logoColor=white) ![Ballerina](https://img.shields.io/badge/-Ballerina-black?style=flat-square&logo=ballerina&logoColor=white) ![PHP](https://img.shields.io/badge/-PHP-black?style=flat-square&logo=php&logoColor=white)

**Frontend** &nbsp; ![React](https://img.shields.io/badge/-React-black?style=flat-square&logo=react&logoColor=white) ![HTML5](https://img.shields.io/badge/-HTML5-black?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-black?style=flat-square&logo=css3&logoColor=white)

**Backend** &nbsp; ![Node.js](https://img.shields.io/badge/-Node.js-black?style=flat-square&logo=nodedotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-black?style=flat-square&logo=fastapi&logoColor=white) ![Laravel](https://img.shields.io/badge/-Laravel-black?style=flat-square&logo=laravel&logoColor=white)

**AI / ML** &nbsp; ![scikit-learn](https://img.shields.io/badge/-scikit--learn-black?style=flat-square&logo=scikitlearn&logoColor=white) ![Gemini](https://img.shields.io/badge/-Gemini%20API-black?style=flat-square&logo=googlegemini&logoColor=white)

**Data** &nbsp; ![MySQL](https://img.shields.io/badge/-MySQL-black?style=flat-square&logo=mysql&logoColor=white)

**Tools** &nbsp; ![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git&logoColor=white) ![VS Code](https://img.shields.io/badge/-VS%20Code-black?style=flat-square&logo=visualstudiocode&logoColor=white) ![IntelliJ IDEA](https://img.shields.io/badge/-IntelliJ%20IDEA-black?style=flat-square&logo=intellijidea&logoColor=white) ![NetBeans](https://img.shields.io/badge/-NetBeans-black?style=flat-square&logo=apache-netbeans-ide&logoColor=white)

<br>

<div align="center">

![Profile views](https://komarev.com/ghpvc/?username=Zyphronix-space&style=flat-square&color=1a1a1a&label=Profile+views)

</div>
