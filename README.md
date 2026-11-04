<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:05060F,50:1B0A3A,100:062B3A&height=190&text=SOURAV%20PATI&fontColor=00F5FF&fontSize=58&fontAlignY=42&animation=fadeIn&stroke=00F5FF&strokeWidth=2&desc=AI%20%2F%20ML%20ENGINEER&descSize=20&descAlignY=68" width="100%" alt="Sourav Pati, AI/ML Engineer"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3200&pause=1000&color=FF2E97&center=true&vCenter=true&width=700&height=40&lines=%3E+building+things+that+see%2C+listen+and+reason;Computer+Vision+%C2%B7+Speech+AI+%C2%B7+LLM+Agents;Open+to+AI%2FML+internships+and+full-time+roles" alt="Typing animation"/>

<br/>

![Open to work](https://img.shields.io/badge/STATUS-OPEN_TO_WORK-0D1117?style=for-the-badge&labelColor=0D1117&color=39FF14)
![Location](https://img.shields.io/badge/LOCATION-KOLKATA%2C_INDIA-0D1117?style=for-the-badge&labelColor=0D1117&color=00F5FF)
![Focus](https://img.shields.io/badge/FOCUS-AI_%2F_ML-0D1117?style=for-the-badge&labelColor=0D1117&color=FF2E97)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=00F5FF)](https://www.linkedin.com/in/patisourav/)
[![Portfolio](https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=vercel&logoColor=FF2E97)](https://sourav-portfolio45.onrender.com/)
[![Email](https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=FFE600)](mailto:patisourav2022@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=39FF14)](https://github.com/spati10)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F5FF,50:9D4EDD,100:FF2E97&height=3" width="100%" alt=""/>

## 👨‍💻 About Me

**Computer Science graduate (AI/ML)** building AI applications across **computer vision, speech processing, and NLP**. I like turning models into working products: inference pipelines, APIs, and real-time systems that run on real hardware.

- 🎙️ Building an **offline multilingual voice AI agent** (Bengali, Hindi, English)
- 🧬 Building **ThoughtField**, a multi-agent social simulation engine
- 🏭 Shipping **real-time CV systems** with YOLOv8 and OpenCV at my internship
- 🔬 Contributor to **open-source AI frameworks** (Aden Hive, 8.5k+ ⭐)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F5FF,50:9D4EDD,100:FF2E97&height=3" width="100%" alt=""/>

## ⚡ Impact at a Glance

<div align="center">

| 🎯 **99.3%** | 🔎 **99%** | 🧠 **4 GB → 1.2 GB** | ⚡ **~0.8 s** |
|:---:|:---:|:---:|:---:|
| Brain tumor MRI classification accuracy | Number plate OCR accuracy on test images | LLM memory after 4-bit ONNX quantization | Offline voice agent response time |

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F5FF,50:9D4EDD,100:FF2E97&height=3" width="100%" alt=""/>

## 🗺️ Journey

```mermaid
timeline
    title Sourav Pati
    2022 : Started B.Tech in CSE (AI/ML) at UEM
    2025 : Oracle Certified AI Foundations Associate
         : Oracle Certified Generative AI Professional
    2026 : Graduated, built Voice AI Agent, ThoughtField and Brain Tumor Detection
         : Joined Beas Consultancy as AI/ML Intern
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F5FF,50:9D4EDD,100:FF2E97&height=3" width="100%" alt=""/>

## 💼 Experience

### 🧪 AI/ML Intern · Beas Consultancy and Services Private Limited
*Aug 2026 – Present*

| | What I built |
|---|---|
| 🎙️ | **Offline multilingual voice AI agent**: speech recognition, language identification, local LLM inference, and text-to-speech |
| 🚚 | **Vehicle number plate recognition**: detects trucks, crops plate regions, extracts text with PaddleOCR at **99% accuracy** on all test images |
| 🏭 | **Real-time factory intrusion detection** on RTSP CCTV streams with YOLOv8 + OpenCV: multi-threaded stream reading, auto-reconnect, IoU-based person tracking, zone-overlap checks for angled cameras |
| 🚨 | **Live zone editor**, dwell-time alarm with siren, and automatic snapshot + event logging (entry time, exit time, duration) to JSON |
| 🏷️ | **Image annotation** and labeled data preparation for an object detection project |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F5FF,50:9D4EDD,100:FF2E97&height=3" width="100%" alt=""/>

## 🌟 Featured Projects

### 🎙️ Multilingual Voice AI Agent (Offline)
![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=00F5FF) ![ONNX](https://img.shields.io/badge/ONNX_Runtime-0D1117?style=flat-square&logo=onnx&logoColor=FF2E97) ![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=flat-square&logo=fastapi&logoColor=39FF14) ![ChromaDB](https://img.shields.io/badge/ChromaDB-0D1117?style=flat-square&logoColor=FFE600) ![RAG](https://img.shields.io/badge/RAG-0D1117?style=flat-square&logoColor=9D4EDD)

A locally running **speech-to-speech agent** supporting **Bengali, Hindi, and English**, combining multilingual speech recognition, language identification, and neural speech synthesis. Runs fully on CPU with ONNX Runtime and was tested offline.

```mermaid
flowchart LR
    A["🎤 Speech input"] --> B["Language identification"]
    B --> C["ASR<br/>Bengali · Hindi · English"]
    C --> D{"Tier 1<br/>Lexical match"}
    D -- hit --> H["🔊 Neural TTS reply"]
    D -- miss --> E{"Tier 2<br/>ChromaDB semantic search"}
    E -- hit --> H
    E -- miss --> F["Tier 3<br/>Local 4-bit LLM"]
    F --> H
    F -. unanswered .-> G["☎️ Customer-care escalation"]

    classDef neon fill:#0D1117,stroke:#00F5FF,color:#ffffff,stroke-width:2px
    classDef warn fill:#0D1117,stroke:#FF2E97,color:#ffffff,stroke-width:2px
    class A,B,C,D,E,F,H neon
    class G warn
```

- ⚡ ~**0.8 s** for dataset-matched queries, **2-3 s** for generated answers
- 🧠 Quantized the local LLM to 4-bit ONNX: memory down from ~4 GB to **1.2 GB**

---

### 🧠 ThoughtField
![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=00F5FF) ![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=flat-square&logo=fastapi&logoColor=39FF14) ![Next.js](https://img.shields.io/badge/Next.js-0D1117?style=flat-square&logo=nextdotjs&logoColor=ffffff) ![OpenAI](https://img.shields.io/badge/OpenAI_API-0D1117?style=flat-square&logo=openai&logoColor=FFE600) ![Redis](https://img.shields.io/badge/Redis-0D1117?style=flat-square&logo=redis&logoColor=FF2E97) ![ChromaDB](https://img.shields.io/badge/ChromaDB-0D1117?style=flat-square&logoColor=9D4EDD)

[![Code](https://img.shields.io/badge/View_Code-0D1117?style=for-the-badge&logo=github&logoColor=9D4EDD)](https://github.com/spati10/ThoughtField)

An AI-powered **multi-agent social simulation platform** based on the Stanford Generative Agents architecture, where autonomous agents interact and drive prediction-based simulations.

```mermaid
flowchart TB
    UI["🖥️ Next.js frontend<br/>live simulation canvas"] <-->|"HTTP + WebSocket"| API["⚡ FastAPI backend<br/>REST + WebSocket"]
    API --> R[("Redis<br/>pub/sub + state")]
    API --> C[("ChromaDB<br/>agent memory vectors")]
    API --> O["🧠 OpenAI API<br/>ticks · reflection · report"]

    classDef neon fill:#0D1117,stroke:#00F5FF,color:#ffffff,stroke-width:2px
    classDef data fill:#0D1117,stroke:#9D4EDD,color:#ffffff,stroke-width:2px
    classDef ai fill:#0D1117,stroke:#FF2E97,color:#ffffff,stroke-width:2px
    class UI,API neon
    class R,C data
    class O ai
```

- 🧠 Agent memory and semantic retrieval with **ChromaDB**, real-time workflows with **Redis**
- 📡 REST APIs plus **WebSocket** communication for live agent interactions

---

### 🩻 Brain Tumor Detection
![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=00F5FF) ![PyTorch](https://img.shields.io/badge/PyTorch-0D1117?style=flat-square&logo=pytorch&logoColor=FF2E97) ![Flask](https://img.shields.io/badge/Flask-0D1117?style=flat-square&logo=flask&logoColor=ffffff) ![ResNet50](https://img.shields.io/badge/ResNet50-0D1117?style=flat-square&logoColor=9D4EDD) ![OpenCV](https://img.shields.io/badge/OpenCV-0D1117?style=flat-square&logo=opencv&logoColor=39FF14)

An end-to-end deep learning web app that classifies brain MRI scans into **Glioma, Meningioma, and Pituitary** tumors using a fine-tuned **ResNet50** with transfer learning, reaching ~**99.3% accuracy** on the Figshare Brain Tumor MRI dataset.

```mermaid
flowchart LR
    A["🩻 MRI scan"] --> B["OpenCV preprocessing<br/>+ data augmentation"]
    B --> C["ResNet50<br/>transfer learning"]
    C --> D["Glioma"]
    C --> E["Meningioma"]
    C --> F["Pituitary"]
    C --> G["🌐 Flask web app"]

    classDef neon fill:#0D1117,stroke:#00F5FF,color:#ffffff,stroke-width:2px
    classDef out fill:#0D1117,stroke:#FF2E97,color:#ffffff,stroke-width:2px
    class A,B,C,G neon
    class D,E,F out
```

---

### 🤖 More AI Projects

| Project | What it does | Tech |
|---------|--------------|------|
| 🕸️ [AI Agents: Aden Hive](https://github.com/spati10/-Agents_AdenHive) | Web page summarizer and resume analyzer agents on a self-evolving agent framework | Python, Hive, GraphSpec, LLM |
| 🎯 [SHL Assessment Recommendation Engine](https://github.com/spati10/SHL_Assessment-Recommendation-Engine) | AI-powered system that recommends assessments based on user needs | Python, Streamlit |
| 👤 [Face Identification Model](https://github.com/spati10/face-identification-model) | Attendance tracker using face recognition | Python, Computer Vision, API |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F5FF,50:9D4EDD,100:FF2E97&height=3" width="100%" alt=""/>

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=py,pytorch,opencv,fastapi,flask,sklearn,redis,nextjs,git,github,linux&theme=dark&perline=11" alt="Core stack"/>

</div>

#### 🧠 Deep Learning & Computer Vision
![PyTorch](https://img.shields.io/badge/PyTorch-0D1117?style=for-the-badge&logo=pytorch&logoColor=FF2E97) ![OpenCV](https://img.shields.io/badge/OpenCV-0D1117?style=for-the-badge&logo=opencv&logoColor=39FF14) ![YOLOv8](https://img.shields.io/badge/YOLOv8-0D1117?style=for-the-badge&logoColor=00F5FF) ![ResNet50](https://img.shields.io/badge/ResNet50-0D1117?style=for-the-badge&logoColor=9D4EDD) ![PaddleOCR](https://img.shields.io/badge/PaddleOCR-0D1117?style=for-the-badge&logoColor=FFE600) ![Transfer Learning](https://img.shields.io/badge/Transfer_Learning-0D1117?style=for-the-badge&logoColor=FF2E97) ![VLM](https://img.shields.io/badge/VLM-0D1117?style=for-the-badge&logoColor=00F5FF)

#### 🎙️ Speech AI
![ASR](https://img.shields.io/badge/ASR-0D1117?style=for-the-badge&logoColor=00F5FF) ![TTS](https://img.shields.io/badge/TTS-0D1117?style=for-the-badge&logoColor=FF2E97) ![VAD](https://img.shields.io/badge/VAD-0D1117?style=for-the-badge&logoColor=39FF14) ![Language ID](https://img.shields.io/badge/Language_Identification-0D1117?style=for-the-badge&logoColor=FFE600)

#### 💬 LLMs, NLP & RAG
![OpenAI](https://img.shields.io/badge/OpenAI_API-0D1117?style=for-the-badge&logo=openai&logoColor=39FF14) ![Gemma](https://img.shields.io/badge/Gemma-0D1117?style=for-the-badge&logo=google&logoColor=00F5FF) ![RAG](https://img.shields.io/badge/RAG-0D1117?style=for-the-badge&logoColor=FF2E97) ![Semantic Search](https://img.shields.io/badge/Semantic_Search-0D1117?style=for-the-badge&logoColor=9D4EDD) ![Quantization](https://img.shields.io/badge/4--bit_Quantization-0D1117?style=for-the-badge&logoColor=FFE600) ![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-0D1117?style=for-the-badge&logo=onnx&logoColor=00F5FF)

#### 🗄️ Data & Vector Databases
![ChromaDB](https://img.shields.io/badge/ChromaDB-0D1117?style=for-the-badge&logoColor=FF2E97) ![Redis](https://img.shields.io/badge/Redis-0D1117?style=for-the-badge&logo=redis&logoColor=FF2E97) ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0D1117?style=for-the-badge&logo=scikitlearn&logoColor=FFE600) ![SQL](https://img.shields.io/badge/SQL-0D1117?style=for-the-badge&logoColor=00F5FF)

#### ⚙️ Backend & Integrations
![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=for-the-badge&logo=fastapi&logoColor=39FF14) ![Flask](https://img.shields.io/badge/Flask-0D1117?style=for-the-badge&logo=flask&logoColor=ffffff) ![REST APIs](https://img.shields.io/badge/REST_APIs-0D1117?style=for-the-badge&logoColor=00F5FF) ![WebSockets](https://img.shields.io/badge/WebSockets-0D1117?style=for-the-badge&logo=socketdotio&logoColor=9D4EDD)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F5FF,50:9D4EDD,100:FF2E97&height=3" width="100%" alt=""/>

## 🎓 Education & Certifications

**B.Tech in Computer Science and Engineering (AI/ML)** · University of Engineering and Management · *2022 – 2026* · CGPA 7.28/10

[![OCI AI Foundations](https://img.shields.io/badge/Oracle_Cloud-AI_Foundations_Associate_2025-0D1117?style=for-the-badge&logo=oracle&logoColor=FF2E97)](https://www.linkedin.com/in/patisourav/)
[![OCI Generative AI](https://img.shields.io/badge/Oracle_Cloud-Generative_AI_Professional_2025-0D1117?style=for-the-badge&logo=oracle&logoColor=00F5FF)](https://www.linkedin.com/in/patisourav/)

## 🔬 Open Source

Contributor to the **Aden Hive Framework** (YC-backed, 8.5k+ GitHub stars), working with GraphSpec / NodeSpec multi-agent architecture. Also into content writing.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F5FF,50:9D4EDD,100:FF2E97&height=3" width="100%" alt=""/>

## 📊 GitHub Activity

<div align="center">

<img src="https://streak-stats.demolab.com/?user=spati10&theme=radical&hide_border=true&background=0D1117&ring=FF2E97&fire=00F5FF&currStreakLabel=00F5FF" alt="GitHub streak"/>

<br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=spati10&theme=radical" width="49%" alt="GitHub stats"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=spati10&theme=radical" width="49%" alt="Most used languages"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=spati10&bg_color=0D1117&color=00F5FF&line=FF2E97&point=FFFFFF&area=true&area_color=9D4EDD&hide_border=true" width="100%" alt="Contribution activity graph"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=spati10&theme=radical&no-frame=true&no-bg=true&row=1&column=7&margin-w=10" alt="GitHub trophies"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:05060F,50:1B0A3A,100:062B3A&height=110&text=Let%27s%20build%20something%20intelligent%20together&fontColor=FF2E97&fontSize=26&fontAlignY=45&animation=fadeIn&stroke=FF2E97&strokeWidth=2&desc=patisourav2022%40gmail.com&descSize=16&descAlignY=72&descColor=00F5FF" width="100%" alt="Footer"/>

<div align="center">

![Profile views](https://komarev.com/ghpvc/?username=spati10&color=9D4EDD&style=for-the-badge&label=PROFILE+VIEWS)

</div>
