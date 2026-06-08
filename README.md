<!-- Header -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:388bfd&height=120&section=header&text=Lakshay%20Dalal&fontSize=42&fontColor=e6edf3&fontAlignY=65&animation=fadeIn" width="100%"/>

</div>

<div align="center">

```bash
$ whoami
> Full-Stack Developer · Deep RL & Machine Learning · Agentic AI Builder
> B.Tech Computer Engineering @ JC Bose University (YMCA) · CGPA: 7.91 · Faridabad, India
> Ex-Intern @ DRDO (DESIDOC) · Open to SDE & AI/ML Internships
```

</div>

---

<!-- Badges -->
<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lakshay-dalal-4024091b8/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lakshaydalal27@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lakshaydalal27)
![Open to Work](https://img.shields.io/badge/Open%20to%20Work-SDE%20%7C%20AI%2FML%20Intern-3fb950?style=for-the-badge)

</div>

<br/>

---

## 🧑‍💻 About Me

- 🎓 **3rd year B.Tech Computer Engineering** @ JC Bose University of Science & Technology, YMCA
- 🏛️ **Former Full-Stack Dev Intern @ DRDO (DESIDOC)** — built a production portal handling 500+ govt. applicants
- 🤖 I build **deep reinforcement learning agents from scratch** (PyTorch), plus **agentic AI / LLM tool-use** and **RAG** pipelines
- 🔬 Also exploring **Computer Vision** — gesture recognition and real-time tracking
- 🥇 **Best Junior Team** @ Bennett University Hackathon (250+ teams) · **Top 5** @ E-Cell DTU Hackathon
- 📬 Reach me at **lakshaydalal27@gmail.com**
- ⚡ Fun fact: I like making computers understand humans — through traffic that learns, voice agents, and hand gestures

---

## 🚀 Projects

### 🚦 Intelligent Traffic Signal Control — Deep Reinforcement Learning &nbsp;`⭐ Flagship`
**`Python` · `PyTorch` · `Double DQN` · `SUMO` · `TraCI` · `FastAPI`**

A **Double DQN agent built from scratch in PyTorch** that learns to control a 4-way intersection, dynamically choosing which lane gets the green to minimise total vehicle waiting time. Trained by interacting with the **SUMO** traffic simulator via **TraCI**.
- 🧠 Double DQN implemented **from scratch — no RL libraries** (no stable-baselines / RLlib)
- 📉 Cut total vehicle waiting time by **12%** vs a 20s and **45%** vs a 30s fixed-timer baseline
- 🔬 **Three documented experiments** (baseline DQN → Double DQN → adaptive-duration), including what didn't work
- 📊 Live **FastAPI** dashboard streaming per-lane Q-values and agent decisions in real time

[![GitHub](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/lakshaydalal27/Traffic-Light-Management-System-using-RL-and-SUMO)

---

### 🛡️ Pipeline Sentinel — Real-Time Leak Detection & Intelligent Rerouting
**`Python` · `TensorFlow/Keras` · `LSTM Autoencoder` · `Isolation Forest` · `FastAPI` · `Dijkstra`**

A hybrid anomaly-detection system (24-hour DTU hackathon, team project) that flags pipeline leaks in real time and automatically reroutes flow around the failed node.
- 🧠 **Hybrid engine** — LSTM Autoencoder (temporal reconstruction error) + Isolation Forest (statistical outliers) fused into a single anomaly score
- ⚡ **FastAPI ML microservice** behind a Node.js/Express backend streaming sensor data over **WebSockets**
- 🛣️ On detection, isolates the faulty node and runs **Dijkstra's algorithm** to compute an optimal bypass route
- 📊 Live **React (Vite)** dashboard with SVG pipeline-topology visualisation and manual override

[![GitHub](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/lakshaydalal27/Pipeline-Sentinal)

---

### 🎙️ Voice Support & Quotation Agent &nbsp;`No-code / Automation`
**`Voiceflow` · `Relevance AI` · `Twilio` · `Make.com` · `WebHooks` · `RAG`**

An agentic AI customer-support system with ReAct-style tool-use and multi-step reasoning, real-time quote generation, automated lead capture, and a RAG-style knowledge base built via website scraping.
- ⚡ **75% reduction** in average response time over manual handling
- 📈 **45% boost** in qualified lead intake via automated WebHook capture
- 🧠 **60% improvement** in query accuracy across voice + chat channels

[![Live Demo](https://img.shields.io/badge/Live%20Demo-388bfd?style=flat-square&logo=vercel&logoColor=white)](https://creator.voiceflow.com/share/6904544d9a34d4e2b6a20aa0/development)

---

### ✋ Air Marker — Mid-Air Drawing with Hand Gestures
**`Python` · `OpenCV` · `MediaPipe` · `Computer Vision`**

A computer vision project that enables real-time mid-air drawing using hand gesture recognition — no touch, no stylus. Tracks finger positions via MediaPipe and renders strokes live with OpenCV.
- 🖐️ Real-time hand landmark tracking at high FPS
- 🎨 Multi-colour drawing, erase, and canvas clear via gestures

![Source](https://img.shields.io/badge/Source-Coming%20Soon-bc8cff?style=flat-square&logo=github)

---

### 🏛️ JRF Job Application Portal — DRDO (DESIDOC) &nbsp;`Production`
**`MongoDB` · `Express.js` · `React.js` · `Node.js` · `JWT` · `RBAC`**

Production-grade recruitment portal built during my internship at a Govt. research organisation. Fully replaced manual workflows across admin, reviewer, and applicant tiers.
- 🔐 15+ secured REST APIs with JWT auth + 3-tier RBAC
- 🚀 Lighthouse score **91/100** (vs ~48 on the existing site)
- ⚙️ MongoDB indexing + aggregation cut query time by **~30%**

> ⚠️ *Proprietary — source not publicly available (government project)*

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

[![My Skills](https://skillicons.dev/icons?i=python,js,cpp,java&theme=dark)](https://skillicons.dev)

**Frontend & Backend**

[![My Skills](https://skillicons.dev/icons?i=react,nextjs,nodejs,express,fastapi,flask&theme=dark)](https://skillicons.dev)

**Databases & Cloud**

[![My Skills](https://skillicons.dev/icons?i=mongodb,postgres,docker,gcp,git&theme=dark)](https://skillicons.dev)

**AI / ML**

[![My Skills](https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,sklearn&theme=dark)](https://skillicons.dev)
&nbsp;`Double DQN` &nbsp;`Reinforcement Learning` &nbsp;`LSTM` &nbsp;`Isolation Forest` &nbsp;`Anomaly Detection` &nbsp;`RAG` &nbsp;`LLM Tool-Use` &nbsp;`ReAct`

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=lakshaydalal27&show_icons=true&theme=github_dark_dimmed&hide_border=true&include_all_commits=true&count_private=true&hide=contribs" height="160"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lakshaydalal27&layout=compact&theme=github_dark_dimmed&hide_border=true&langs_count=6" height="160"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=lakshaydalal27&theme=github-dark-blue&hide_border=true" height="160"/>

</div>

---

## 🏆 Achievements & Certifications

| 🏅 Achievement | Details |
|---|---|
| 🥇 **Best Junior Team (1st Year)** | Bennett University Hackathon, Apr 2024 — out of 250+ teams |
| 🎖️ **5th Place** | Hackathon by E-Cell DTU |
| 📜 **AI Agency & Automation** | Liam Ottley's course — LLM integration, agentic workflows, autonomous agents |

---

## 📌 Positions of Responsibility

- 🎪 **Event Coordinator** — Student Council, JC Bose University (YMCA)
- 🌿 **Joint Secretary** — Vasundhra Eco Club, JC Bose University (YMCA)

---

## 🤝 Let's Connect

<div align="center">

I'm actively looking for **SDE Internships** and **AI/ML Internships**. If you're hiring or just want to talk tech — reach out!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lakshay-dalal-4024091b8/)
[![Gmail](https://img.shields.io/badge/Gmail-Drop%20a%20Mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lakshaydalal27@gmail.com)

</div>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:388bfd,50:1f6feb,100:0d1117&height=100&section=footer" width="100%"/>

</div>
