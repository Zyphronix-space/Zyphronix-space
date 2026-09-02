<div align="center">

![Status](https://img.shields.io/badge/Status-Open%20to%20Software%2FIT%20Internships-2E7D32?style=flat-square&labelColor=1a1a1a)

# Stephan

### Software / IT Developer — Full-Stack · AI &amp; Data · Systems Integration

3rd-year BIT undergraduate who ships complete systems, not exercises — a React/Node/MySQL platform with real-time features, a run of FastAPI + scikit-learn/transformer ML services, and a Ballerina integration service for a WSO2 internship application.

[Portfolio](https://zyphronix-space.github.io/) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/stephan-wasalathathrige) &nbsp;·&nbsp; [Email](mailto:stephanwasalathanthrige@gmail.com) &nbsp;·&nbsp; [GitHub](https://github.com/Zyphronix-space)

</div>

<br>

> **Building** — FastAPI + React ML services (house-price regression, resume↔job semantic matching) and small agentic AI tools (RAG document chat, tool-calling research agent)
>
> **Learning** — Spring Boot &amp; J2EE, to round out the Java side
>
> **Interested in** — applying ML inside full-stack products, and service integration in the style Ballerina/WSO2 are built for
>
> **Open to** — Software / IT internships

<br>

## Featured Projects

### Tier 1 — Flagship

<table>
<tr><td width="100%">

**VinuCare** — full-stack pet-care management platform

Appointment booking, an online pet-product shop, and role-based dashboards for doctors, nurses, and admins, with live staff notifications over WebSockets.

**Stack:** React (Vite) · Node.js/Express · MySQL · Socket.io · Google OAuth

**Highlights**
- Real-time staff messaging via Socket.io, not polling
- Role-based dashboards (Doctor / Nurse / Admin) with live analytics
- Email/password + Google auth, password-reset flow, transactional email via Resend

[Repository](https://github.com/Zyphronix-space/VinuCare)

</td></tr>
<tr><td width="100%">

**House Price Predictor** — end-to-end ML application

Predicts California house prices from housing-block statistics, from model training through to a live prediction UI.

**Stack:** Python · scikit-learn · FastAPI · React (Vite)

**Highlights**
- Benchmarks Linear Regression against Random Forest on MAE / R² before picking a model
- Trained model serialized with `joblib` and served behind a `POST /predict` FastAPI endpoint
- React frontend calls the live API — not a notebook demo

[Repository](https://github.com/Zyphronix-space/house-price-predictor)

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
| **[resume-job-matcher](https://github.com/Zyphronix-space/resume-job-matcher)** | Upload a CV + job description, get a semantic match score and a concrete skills gap, via sentence embeddings — not keyword matching | Python · sentence-transformers · FastAPI · React |
| **[ai-research-agent](https://github.com/Zyphronix-space/ai-research-agent)** | An agent that decides on its own whether to search the web, run a calculation, or just answer, streaming each tool call live | Python · Gemini function calling · FastAPI · React |
| **[doc-chat-rag](https://github.com/Zyphronix-space/doc-chat-rag)** | Upload a document, ask questions grounded only in retrieved chunks — a real RAG pipeline, not a plain LLM wrapper | Python · sentence-transformers · Chroma · Gemini · FastAPI · React |
| **[sms-spam-classifier](https://github.com/Zyphronix-space/sms-spam-classifier)** | Classifies SMS text as spam/ham, comparing Naive Bayes against Logistic Regression on TF-IDF features | Python · scikit-learn · FastAPI · React |

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
**AI, Data &amp; Integration** — ML services, RAG and agentic tooling, Ballerina-based service integration
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
