<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6e00ff,50:8a2be2,100:4b0082&height=220&section=header&text=Nandini%20Singh&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%2FML%20Engineer%20%7C%20Full%20Stack%20Developer&descAlignY=55&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=24&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=Building+Production-Grade+AI+Systems;RAG+%7C+Computer+Vision+%7C+Multi-Agent+Systems;Open+Source+Contributor+%40+aeon-toolkit;Pre-Final+Year+AI%2FML+Engineer" alt="Typing SVG" />

<br/>

![Academic](https://img.shields.io/badge/B.Tech-AI%20%26%20ML-6A0DAD?style=for-the-badge&logo=googlescholar&logoColor=white)
![Location](https://img.shields.io/badge/Indore%2C%20India-9370DB?style=for-the-badge&logo=googlemaps&logoColor=white)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-6e00ff?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/Nandinisingh07)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nandinisingh10)
[![Email](https://img.shields.io/badge/Email-8A2BE2?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nandinii.singh07@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-9333EA?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nandinisingh07)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Nandinisingh07&color=8a2be2&style=for-the-badge&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/Nandinisingh07?color=6e00ff&style=for-the-badge&label=FOLLOWERS)
![Stars](https://img.shields.io/github/stars/Nandinisingh07?color=9370DB&style=for-the-badge&label=STARS)

</div>

<br/>

## About Me

```yaml
engineer:
  name: "Nandini Singh"
  role: "AI/ML Engineer · Full Stack Developer"
  focus:
    - Designing and shipping production-grade ML pipelines (RAG, CV, NLP)
    - Building full-stack systems end-to-end with React, FastAPI & Node.js
    - Engineering with a product mindset — reliability, security & scale first
  open_source: "Recognized contributor @ aeon-toolkit, a peer-reviewed time series ML/DL library"
```

I'm a pre-final year AI/ML engineering undergrad who builds complete, deployable systems — not just notebooks. My work spans secure multimodal retrieval architectures, computer-vision-driven automation platforms, and multilingual AI assistants, all engineered with the same discipline: clean APIs, measured performance, and real-world constraints in mind. I contribute to peer-reviewed open-source infrastructure and enjoy the full lifecycle of a product — from architecture to deployment.

<table align="center">
<tr>
<td>

**🎯 Open To**
- AI/ML & Software Engineering Internships
- Open Source Collaboration
- Research-Driven Engineering Roles
- Hackathons & Applied ML Challenges

</td>
</tr>
</table>

---

## Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,js,ts,cpp&theme=dark" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,vite,html,css,tailwind&theme=dark" />

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=fastapi,nodejs,postgres,sqlite&theme=dark" />

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=docker,aws,git,github,vercel,postman&theme=dark" />

</div>

---

## AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|---|:---:|---|
| **Retrieval-Augmented Generation** | ●●●●● | Multi-stage hybrid retrieval — dense (Sentence-Transformers) + keyword (BM25) + visual (CLIP), reciprocal rank fusion, cross-encoder reranking, MMR deduplication |
| **Computer Vision** | ●●●●○ | Face recognition & liveness verification (InsightFace/ArcFace), OCR pipelines (Tesseract, PaddleOCR), lightweight on-device classification (TFLite) |
| **Generative AI & Agentic Systems** | ●●●●○ | LangChain, LangGraph, CrewAI, AutoGen, multi-agent orchestration, prompt engineering, Gemini & local LLMs via Ollama |
| **NLP & Semantic Search** | ●●●●○ | Sentence-BERT embeddings, FAISS vector search, intent classification, multilingual TTS/IVR pipelines |
| **MLOps & Deployment** | ●●●○○ | Dockerized microservices, CI/CD, model quantization for edge deployment, production monitoring with Prometheus |

</div>

---

## Featured Projects

<details open>
<summary><b>🧠 IntelliMesh — Secure Multimodal RAG System</b></summary>
<br/>

Fully air-gapped, offline-first multimodal RAG system ingesting PDFs, DOCX, images, and audio through local OCR, BLIP captioning, and Whisper transcription. Runs a six-stage hybrid retrieval pipeline — dense (MiniLM) + BM25 + CLIP visual search, fused via reciprocal rank fusion, cross-encoder reranked, and MMR-deduplicated — on top of a computed `networkx` knowledge graph with clearance-level access control. A dedicated hallucination guard achieved a **0% hallucination rate** across a 36-query, 9-configuration ablation evaluation.

| Aspect | Details |
|---|---|
| **Stack** | Python · FastAPI · React + Vite · ChromaDB · Ollama (phi3:mini) · Sentence-Transformers · BLIP · Whisper |
| **Scale** | 6-stage retrieval pipeline · networkx knowledge graph |
| **Performance** | 0% hallucination rate across 36-query / 9-config ablation testing |
| **Security** | Fully air-gapped, offline-first · clearance-based document access control |
| **Impact** | Production-grade RAG dashboard with architecture-diagrammed README |
| **Repository** | [github.com/Nandinisingh07/Intellimesh](https://github.com/Nandinisingh07/Intellimesh) · [Live Demo](https://intellimesh.vercel.app/) |

</details>

<details>
<summary><b>🏦 Complainlytics — Bank Complaint Intelligence Platform</b></summary>
<br/>

Full-stack complaint intelligence platform unifying six intake channels behind a 30-endpoint FastAPI backend, with NLP-based classification, generative-AI drafting, and dual autonomous agents (Auto-Triage + Resolution) for real-time escalation and SLA-based regulatory reporting.

| Aspect | Details |
|---|---|
| **Stack** | FastAPI · Sentence-BERT · FAISS · Gemini API · Scikit-learn · React · TypeScript |
| **Scale** | 30-endpoint backend unifying 6 complaint channels |
| **Performance** | Sub-100ms FAISS + SBERT duplicate detection across 1,200+ records |
| **Security** | Regulatory SLA-based reporting · audited & purged of exposed credentials |
| **Impact** | Dual AI agents automate triage and resolution end-to-end |
| **Repository** | [github.com/Nandinisingh07/Complainlytics](https://github.com/Nandinisingh07/Complainlytics) · [Live Demo](https://complainlytics.vercel.app/) |

</details>

<details>
<summary><b>🛡️ SEAS — Smart Exam Automation System</b></summary>
<br/>

End-to-end exam automation platform handling invigilator duty allocation, ArcFace-based three-stage biometric gate verification, and attendance/washroom tracking, secured with JWT role-based access control and deployed as Dockerized microservices with dynamic scheduling.

| Aspect | Details |
|---|---|
| **Stack** | FastAPI · InsightFace (ArcFace) · Tesseract OCR · React · Docker · Prometheus · JWT |
| **Scale** | 3-stage biometric verification gate · dynamic duty scheduling |
| **Performance** | 96.25% verification accuracy (77/80) in under 10s per student |
| **Security** | JWT-RBAC · Dockerized microservices · production monitoring |
| **Impact** | Automates exam integrity checks previously done manually |
| **Repository** | [github.com/Nandinisingh07/exam-system](https://github.com/Nandinisingh07/exam-system) · [Live Demo](https://exam-system-eta-nine.vercel.app/) |

</details>

<details>
<summary><b>🌾 Kisan Saathi — Multilingual Agricultural Assistant</b></summary>
<br/>

Flask-based agricultural assistant serving farmers across 13 Indian languages, combining a lightweight on-device crop disease classifier with Gemini 2.5 Flash for conversational guidance, Twilio IVR for phone-based access, and live market/weather data integration.

| Aspect | Details |
|---|---|
| **Stack** | Flask · Gemini 2.5 Flash · TensorFlow Lite · Twilio IVR · gTTS · Agmarknet API · OpenWeatherMap API |
| **Scale** | 13 Indian languages · 7.4MB on-device crop disease model, 18 classes |
| **Performance** | IVR-driven multilingual voice interface with automated language routing |
| **Security** | Dual-key API rotation for reliability under rate limits |
| **Impact** | Brings AI-driven crop diagnosis and market data to low-connectivity, voice-first users |
| **Repository** | [github.com/Nandinisingh07/Kisan-Saathi](https://github.com/Nandinisingh07/Kisan-Saathi) |

</details>

<br/>

<details>
<summary><b>📦 Additional Projects</b></summary>
<br/>

- **AlumniConnect** — RAG-powered alumni networking platform
- **LexiClarify** — Legal document analyzer built on Gemini
  

</details>

---

## Experience

**Open Source Contributor — Aeon (Time Series ML/DL Toolkit)**
`March 2026 – Present`

Contributing to [aeon-toolkit/aeon](https://github.com/aeon-toolkit/aeon), a peer-reviewed, BSD-licensed Python library for time series machine learning and deep learning.

- Authored and merged pull requests across the classification and forecasting modules, reviewed and approved by core maintainers
- Listed as a recognized contributor on the project's official contributor page

`Python` `Time Series ML` `Open Source` `Peer Review`

---

## Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🏆 HackWise, IIM Indore (IRIS 2026) | Advanced to Campus Round — national-level AI solution-building hackathon |
| 🌟 Aeon Recognized Contributor | Maintainer-reviewed PRs merged into a peer-reviewed OSS ML/DL toolkit |
| 🎖️ GitHub Achievements | YOLO · Pair Extraordinaire |
| 🎤 Anchored AI Horizon 2025 | Led a 6-day AI/ML/GenAI event at IIST Indore featuring speakers from Deloitte & Neuratantra AI |
| 👥 Core Member — AI/ML Club (DEV X) & DSA Club | Organized workshops and hackathons; mentored peers in AI/ML and DSA |

</div>

---

## Certifications

<div align="center">

**AWS**

![AWS Certified Cloud Practitioner](https://img.shields.io/badge/AWS-Certified%20Cloud%20Practitioner-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

**NPTEL**

![Deep Learning](https://img.shields.io/badge/NPTEL%20Silver%20Elite-Deep%20Learning-6A0DAD?style=flat-square&logo=googlescholar&logoColor=white)
![Data Analytics with Python](https://img.shields.io/badge/NPTEL%20Elite-Data%20Analytics%20with%20Python-8A2BE2?style=flat-square&logo=googlescholar&logoColor=white)
![C++](https://img.shields.io/badge/NPTEL%20Silver%20Elite-C%2B%2B-9370DB?style=flat-square&logo=googlescholar&logoColor=white)
![Joy of Computing](https://img.shields.io/badge/NPTEL-Joy%20of%20Computing-7C3AED?style=flat-square&logo=googlescholar&logoColor=white)

**Google**

![Kaggle 5-Day AI Agents Intensive](https://img.shields.io/badge/Kaggle%20%C3%97%20Google-5--Day%20AI%20Agents%20Intensive-4285F4?style=flat-square&logo=google&logoColor=white)

</div>

---

## Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-6A0DAD?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/Nandinisingh07)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-7C3AED?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/user/Nandinisingh07)
[![HackerRank](https://img.shields.io/badge/HackerRank-8A2BE2?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/Nandinisingh07)
[![CodeChef](https://img.shields.io/badge/CodeChef-9370DB?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com/users/Nandinisingh07)

<sub>⚠️ Update these links to your actual coding-profile usernames if they differ from your GitHub handle.</sub>

</div>

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Nandinisingh07&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=A78BFA&icon_color=8A2BE2&text_color=c9d1d9" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Nandinisingh07&theme=radical&hide_border=true&background=0d1117&stroke=A78BFA&ring=8A2BE2&fire=A78BFA&currStreakLabel=A78BFA" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nandinisingh07&layout=compact&theme=radical&hide_border=true&bg_color=0d1117&title_color=A78BFA&text_color=c9d1d9" width="49%"/>

</div>

---


## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Nandinisingh07&theme=react-dark&bg_color=0d1117&color=A78BFA&line=8A2BE2&point=ffffff&hide_border=true" width="100%"/>

</div>

---



## Current Focus

## 🚀 Current Focus

<div align="center">

|  LEARNING |  BUILDING |  EXPLORING |
|:---:|:---:|:---:|
| Advanced multi-agent orchestration | Production-grade retrieval & agentic AI systems | Applied research in time series ML/DL |
| LangGraph · CrewAI | Full-stack AI platforms | Edge deployment |
| Distributed systems | Security-first engineering | Model quantization |
| Scalable backend architecture | Measured, production-ready systems | Low-resource environments |

</div>

<break>
### 🎯 Open To

<div align="center">

**AI/ML Engineering Internships** · **Full Stack + AI Product Roles** · **Open Source Collaboration**

</div>

---

## Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-6e00ff?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nandinii.singh07@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nandinisingh10)
[![GitHub](https://img.shields.io/badge/GitHub-8A2BE2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nandinisingh07)
[![Portfolio](https://img.shields.io/badge/Portfolio-9333EA?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/Nandinisingh07)

</div>

<br/>

<div align="center">

*"Engineering isn't about writing code — it's about building systems people can trust."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4b0082,50:8a2be2,100:6e00ff&height=120&section=footer" width="100%"/>

</div>
