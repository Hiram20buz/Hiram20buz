<h1 align="center">👋 Hi, I'm Ricardo Santiago</h1>

<p align="center">
  <b>AI Engineer</b> · Agentic & Applied ML — from research to production
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ricardo-santiago-764718264/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:ricardosantiago1350@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://orcid.org/0009-0008-9493-3501"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white" alt="ORCID"/></a>
  <a href="https://scholar.google.com/citations?hl=es&user=rbWdn0MAAAAJ"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=flat&logo=googlescholar&logoColor=white" alt="Google Scholar"/></a>
  <a href="https://www.researchgate.net/profile/Ricardo-Santiago-10"><img src="https://img.shields.io/badge/ResearchGate-00CCBB?style=flat&logo=researchgate&logoColor=white" alt="ResearchGate"/></a>
  <a href="https://huggingface.co/ricardoSLabs"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-FFD21E?style=flat" alt="Hugging Face"/></a>
  <a href="https://www.kaggle.com/ricardorioda"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white" alt="Kaggle"/></a>
</p>

---

## 🧠 About Me

AI Engineer specializing in **applied and agentic machine learning systems, from research through deployment**. I build AI agents, chatbots, RAG pipelines, and REST APIs on **GCP Cloud Run** and **AWS Lambda**, plus enterprise document-search platforms, real-time voice agents, AI-driven test automation, and industrial computer vision for defect detection.

📍 Tijuana, Baja California, México
🎓 M.Sc. in Engineering – Artificial Intelligence (in progress) @ Instituto Tecnológico de Tijuana

**Open to:** AI Engineer · Data Engineer · Data Scientist · Research Scientist

---

## 💼 Experience

### Consulting — **AI Engineer**
📆 May 2026 – Oct 2026 · 📍 Tijuana, BC, México
*Building AI-powered voice and recipe-suggestion features for a chef-facing iOS app.*
- Built a **voice agent in SwiftUI (Xcode)** for chefs, connected via **LiveKit** to a Python agent using the **OpenAI Realtime API** for real-time speech interaction.
- Built a **recipe suggestion module** that filters recipes by constraints such as available time, taste preferences, and allergies.

### ITJ — **AI Engineer**
📆 Apr 2024 – Present · 📍 Tijuana, BC, México
*Designing and deploying applied AI solutions across agentic systems, chatbots, automation, and ML workflows.*
- Built a **Confluence document-search system (RAG)**: embeddings via **Vertex AI (Gemini)**, indexed in **Pinecone**, orchestrated with **LangChain**, deployed with **Docker on GCP Cloud Run**.
- Built an **AI voice agent for candidate pre-screening & behavioral interviews** using **Gemini native-audio (speech-to-speech)**, with **LiveKit Cloud** handling WebRTC/media and GCP Cloud Run hosting frontend, token server, and agent worker.
- Built a **serverless resume-processing pipeline on AWS Lambda** (containerized, async-triggered on S3 upload): uses Gemini/Vertex AI to extract structured candidate profiles, matches them against live Skills/Tags catalogs, and publishes to **GCP Pub/Sub**.
- Built an **AI-driven test automation pipeline** with **LangGraph + Gemini** that turns **Jira** stories into reviewed test cases and approved cases into runnable **Playwright** code, with a label-driven human-approval gate at each step. Automated end-to-end via a Jira rule that POSTs to a GCP Cloud Run `qa-gate` service writing results back to Jira/Xray.
- Implemented **predictive maintenance models** (LSTM, Prophet, XGBoost) for industrial sensor time-series forecasting.
- Implemented a **Vision Transformer defect detection system (98–99% accuracy)** for industrial TIG welding inspection — published as a research paper.

### ITJ — **Automation Tester** *(Dexcom Project)*
📆 May 2023 – Apr 2024 · 📍 Tijuana, BC, México
*Automated testing frameworks for medical device software.*
- Built and maintained automated test suites with **Appium + TestNG** for a mobile Continuous Glucose Monitoring (CGM) app, covering critical patient-monitoring flows.
- Led test automation from scratch for the **G6→G7 app migration**, achieving regression coverage across both versions.
- Developed a **Python + TestRail API** script to pull failed runs, classify failure types, and generate summary metrics — reducing manual triage time.

---

## 🛠️ Tech & Tools

**Programming & AI/ML**
Python · Java · Swift/SwiftUI · SQL · PyTorch · Transformers (Hugging Face) · scikit-learn · OpenCV · LangChain · FastAPI · Unsloth

**Agentic & LLM Systems**
OpenAI Realtime API · Gemini Native Audio (speech-to-speech) · Vertex AI · RAG Pipelines · Pinecone / Vector DBs · Embeddings · AI Agents · Voice AI Agents (LiveKit/WebRTC) · Tool Calling · MCP (Model Context Protocol) · LangGraph

**Cloud & Deployment**
GCP (Cloud Run, Vertex AI, Artifact Registry, Cloud Build, Pub/Sub) · AWS (Lambda, ECR, S3, Secrets Manager) · Docker · Git · REST APIs · CI/CD & MLOps (Makefile-based deploy automation)

**Computer Vision & Data Science**
Vision Transformers (ViT, BEiT) · Image & Document Classification · Welding Defect Detection · Facial Emotion Recognition · Time Series Forecasting (LSTM, Prophet, XGBoost) · Neural Architecture Search · Model Benchmarking & Evaluation · Pandas · NumPy · spaCy

**Test Automation & QA**
Appium · TestNG · TestRail API · Playwright · Jira / Xray · AI-Assisted Test Case Generation · Regression & Mobile App Testing

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Hiram20buz&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hiram20buz&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages"/>
</p>

---

## 🚀 Projects

- 🤖 **RAG Pipeline with GCP Deployment** — Retrieval-Augmented Generation with vector search, metadata extraction, and agent demos, fully deployed on Google Cloud.
- 🔧 **TIG Welding Defect Detection** — Vision Transformer–based classification of industrial welding defects (98–99% accuracy).
- 😊 **NAS for Facial Emotion Recognition** — Neural Architecture Search (CMA-ES) for optimized FER systems.
- 📑 **Document Classification** — Benchmarking ML, DL, and transformer models for multi-class text/image classification.
- ⏳ **Time Series Prediction** — Forecasting with LSTM, Prophet, and XGBoost.
- 🎙️ **Voice Gender Detection** — ML/DL approach to gender recognition from audio.
- 📝 **OCR + NER Tool** — Custom pipeline for extracting structured information from documents.
- 📊 **Synthetic Tabular Data Generation** — Data augmentation and benchmarking (GANs), with Optuna tuning and class-balancing experiments.

---

## 📚 Publications

- **"Multiclass Evaluation of Vision Transformers for Industrial Welding Defect Detection"**
  *Mathematical and Computational Applications*, Vol. 30, Issue 2, Article 24 (2025) — [Read →](https://www.mdpi.com/2297-8747/30/2/24)

- **"Embedded Vision Transformers for Industrial Welding Defect Detection"**
  R. R. Santiago, A. Contreras Ortiz, M. Lopez-Montiel, V. H. Diaz-Ramirez
  *Proc. SPIE 13604, Optics and Photonics for Information Processing XIX*, 136040P (2025) — [Read →](https://doi.org/10.1117/12.3063965)

- **"Benchmarking ML, DL, and Transformer Models for Document Classification"**
  R. R. Santiago, A. Contreras Ortiz, C. Tona, M. Lopez-Montiel
  *Artificial Intelligence and Quantum Computing: Early Innovations*, Vol. 1, pp. 347–373, Springer Nature (2025) — [Read →](https://doi.org/10.1007/978-3-031-85614-3_18)

---

## 🏆 Highlights

- 🧮 **National Physics Olympiad (ONF)** — Honorable mention, ranked 38th nationally (2019) · [[Results]](https://smf.mx/programas/olimpiada-nacional-de-fisica/resultados-onf-2019/) · [[Certificate]](https://drive.google.com/file/d/1OgZ0fkUbRoeafk9XuO3NhryNl4aSGUbb/view)
- 👩‍💻 **[Womanium Quantum Workshop](https://youtu.be/UOsoAQIjyio?si=O5_4V_058RLKfMV-&t=7649)** — ViT-with-quantum-layer project (2024)
- 🤖 **NEO 2024** — Presented & published *"Multiclass Evaluation of Vision Transformers..."* · [[Paper]](https://www.mdpi.com/2297-8747/30/2/24)
- 🔬 **[Seminar on AI and Quantum Computing](https://www.youtube.com/live/3Y85HQK902E?si=EbwPZj6qiJDMHEom&t=12142)** (2024) · [[Paper]](https://doi.org/10.1007/978-3-031-85614-3_18)
- 🇺🇸 **[Summer School on Numerical Methods in Quantum Information Science](https://www.linkedin.com/posts/ricardo-santiago-764718264_im-excited-to-share-that-ive-just-completed-activity-7353951483723145216-4WZa)** — UMass Amherst (2025)
- 🌎 **[SPIE Optics + Photonics](https://www.linkedin.com/posts/ricardo-santiago-764718264_spie-optics-photonics-2025-excited-to-activity-7359634819422605313-WS1z)** — San Diego, CA (2025) · [[Paper]](https://doi.org/10.1117/12.3063965)
- 🤖 **NEO 2025** — Presented *"Neural Architecture Search with CMA-ES for Facial Emotion Recognition"* · [[Handbook]](https://neo-workshop.com/Documents/NEO_book_of_abs_2025.pdf)
- 👩‍💻 **[{Tech: Europe} Paris AI Hackathon](https://www.linkedin.com/posts/ricardo-santiago-764718264_techeurope-openai-beyond-activity-7378339279367933953-KGXa/)** (2025) · [[Repo]](https://github.com/emilecohen/techeurope-hack-paris)
- 🎙️ **[TAI Explorations: Real-Time Voice Agents with Agora](https://www.linkedin.com/posts/ricardo-santiago-764718264_agora-voiceagents-aiagents-activity-7419765355704692737-LZgq)** — Tokyo (2026)
- 🤖 **[Physical AI Hack 2026](https://www.linkedin.com/posts/ricardo-santiago-764718264_physicalai-lerobot-solotech-activity-7424119198395641856-sjo6)** — San Francisco, CA (2026)

---

## 🎓 Education

- **M.Sc. in Engineering – Artificial Intelligence** *(in progress)* — Instituto Tecnológico de Tijuana · 2025 – Present
- **B.Eng. in Computer Systems Engineering** — Instituto Tecnológico de Tijuana · 2020 – 2024

---

## 📜 Certifications

- 🅰️ [**Claude Certified Architect – Foundations**](https://www.credly.com/badges/044d708d-5b13-4dfc-9b65-59827ff9a611/linked_in_profile) — Anthropic (2026)
- 🧱 [**Databricks Certified Data Engineer Associate**](https://credentials.databricks.com/fa93e950-7197-476c-b9a0-fc7eff646012) — Databricks (2026)
- 🔌 [**Introduction to Embedded Machine Learning**](https://coursera.org/share/157d76d0c790026ac2a6ae43a9ea6301) — Coursera (2025)
- 👁️ [**Computer Vision with Embedded Machine Learning**](https://coursera.org/share/ab7b2f0caddbdd802105de6b620d33cd) — Coursera (2025)
- 📊 [**IBM Data Science**](https://coursera.org/share/b25b267903636d0b27e30b6c40818fec) — Coursera (2025)

---

<p align="center">
  <i>✨ Thanks for visiting! Open to collaboration in AI agents, applied ML, and research — feel free to connect.</i>
</p>
