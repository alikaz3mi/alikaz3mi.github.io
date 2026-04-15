---
layout: default
title: Resume
permalink: /resume/
---

# Ali Kazemi
**Expert Machine Learning Engineer**  
📍 Mashhad, Iran | Ready to Relocate | 📧 [alikazemi@ieee.org](mailto:alikazemi@ieee.org) | 📱 (+98) 915-239-0307  
🔗 [LinkedIn](https://www.linkedin.com/in/ali-kazemi-199510/) | [GitHub](https://github.com/alikaz3mi)

---

## Professional Summary

- 5+ years of experience in ML & AI Engineering, including 2 years as Tech Lead managing cross-functional teams of up to 15.
- **Architected production RAG & LLM pipelines** handling **2,000 requests/min**, achieving a **96% reduction in per-user setup costs** ($2.50 to $0.10).
- **Deployed high-performance NLP & OCR pipelines** with **<50ms latency** on 2GHz CPUs, reducing Italian handwriting Word Error Rate (WER) from 20% to 3%.
- **Engineered Large-Scale CV systems**, fine-tuning facial recognition models on **49M+ images** to achieve 99.97% accuracy.
- **TOEFL iBT: 105/120**.

---

## Technical Skills

- **Python & Software Engineering:** Python 3.x (asyncio, type hints, context managers, OOP, design patterns), TDD, modular architecture, unit testing, code review practices.
- **AI Agent Development:** Agent design and orchestration (LangGraph, LlamaIndex), LLMs (open-source & APIs), Advanced RAG, vector databases (ChromaDB, Milvus, Elasticsearch), Transformers, NER.
- **3rd-Party Model Evaluation:** Production experience with OpenAI, QWEN, and OSS LLMs; hands-on trade-off analysis across latency, cost, accuracy, and context-window limits for production selection.
- **CI/CD & MLOps:** Docker, Kubernetes, GitLab/GitHub Actions CI/CD, Infrastructure as Code (Ansible), Model Serving (FastAPI, gRPC, vLLM, TensorRT), GitOps.
- **Observability & Cloud:** AWS (EC2, SQS, IAM, CloudWatch), Prometheus, Grafana, Graylog, SQL (PostgreSQL), NoSQL (MongoDB), scalable data pipelines, PyTorch, TensorFlow.

---

## Professional Experience

### ParsTech AI — Product Tech Lead
*Mashhad, Iran | Jul 2020 – Present*

**Tech Lead**
- **MLOps & Infrastructure Automation:** Architected **Infrastructure as Code (IaC)** workflows using **GitLab CI/CD** and **Ansible** to automate the provisioning of high-performance GPU clusters, reducing environment setup time from days to hours.
- **Scalable Model Serving & Observability:** Migrated monolith to containerized **AWS EC2** microservices with **SQS** task queuing, ensuring 99.9% uptime; established **Prometheus/Grafana/CloudWatch** monitoring for model drift and latency tracking.
- **Autonomous AI Agent:** Designed and deployed a production Python agent that processes multimodal inputs (voice, text, image) to autonomously route and assign Jira issues — built with asyncio task handling and enterprise system integration, cutting mean diagnosis time from 8 hours to 20 minutes.

**ParsChat — Product Tech Lead** *(Nov 2022 – Present)*
- **Enterprise AI Agent Platform:** Owned the full lifecycle — prototype through production — of a Python-based AI agent platform handling **20,000+ daily messages** across diverse enterprise clients, integrating agents with existing CRM and e-commerce backend systems.
- **3rd-Party Model Evaluation & Deployment:** Selected **QWEN** over competing OSS and API alternatives through structured evaluation of latency, accuracy, and cost; deployed via **vLLM on RTX 5090**, achieving **60 messages/min** throughput; maintained an agent evaluation harness tracking quality regressions across model versions.
- **Agent Orchestration (LangGraph):** Re-architected the agent pipeline into a **graph-based design (LangGraph)** with intent-based routing and state management, enabling zero-hallucination processing of knowledge bases up to **10 million characters**.
- **Business Impact:** Reduced agent delivery time from 1 week to 5 minutes and cut per-user setup costs by **96%** ($2.50 → $0.10) — every technical decision tied to a measurable dollar outcome.

**AshenasAI (eKYC & Biometrics)** *(Feb 2023 – Jul 2023)*
- **Multi-Module AI System Integration:** Designed and integrated a 5-module pipeline (Liveness Detection, 3D Face Verification, OCR, biometric matching) against an existing enterprise identity system using strongly-typed Python interfaces, FastAPI, gRPC, and Celery/Redis.
- **Model Evaluation & Optimization:** Evaluated and fine-tuned face recognition models on **49M images** (NVIDIA A6000) to achieve 99.97% accuracy; profiled and optimized the same models for CPU-based deployment, achieving real-time performance across all 5 modules (20 seconds end-to-end).

**DastYar — AI Tech Lead** *(Aug 2021 – Oct 2022)*
- Optimized video analytics: GPU latency 200 → 40 ms, throughput ≈ 1,000 fps.
- Fine-tuned a large-scale face recognition model on 49M+ images, reaching 99.97%.
- Head detector: lightweight trained YOLO model (84% mAP, ~1 ms TRT Deployment).

**ML Engineer** *(Jul 2020 – Jul 2021)*
- Trained OCR and gesture recognition systems (WER ↓ to 3%, top-5 = 84%).
- **Resource-Efficient Edge AI:** Optimized detection models (TensorRT) for Jetson Nano/NX, enabling real-time video analytics (license plate recognition, people counting) on constrained hardware.

---

### Sensifai BV — Freelance Engineer
*Remote (Belgium) | Feb 2022 – Jul 2022 | Sep 2025 – Mar 2026*

**DIPAL** *(Backend Engineer — SPADE Open Call #2, Sep 2025 – Mar 2026)*
- **Drone Pipeline Backend:** Engineered scalable **AWS** backend services automating structure-from-motion (SfM) and multi-view-stereo (MVS) pipelines for an open-source photogrammetry toolkit, converting aerial drone captures into accurate 3D reconstructions and geospatial outputs with REST API integration for downstream GIS workflows.

**SensiGesture** *(ML/MLOps Engineer — Automotive In-Cabin AI, Feb 2022 – Jul 2022)*
- **Dataset & Model Development:** Curated a proprietary in-cabin dataset of **350,000+ annotated RGB frames** across day, night, glare, and overcast conditions; trained **MobileNetV3** models achieving recognition of **22 gestures** and **20 driver activity classes** (drowsiness, phone use, seatbelt violations) for real-time inference.
- **Edge MLOps:** Built end-to-end pipeline for data versioning, automated evaluation, and on-device deployment on automotive-grade edge hardware.

---

## Education

**Khajeh Nasir University of Technology (KNTU)** — Tehran, Iran  
*M.Sc., Biomedical Engineering (Bioelectric)*  
Oct 2019 – Feb 2023 | GPA: 18.04 / 20  
**Thesis:** Modeling of Human Brain Perisylvian Pathways Development with Diffusion Tensor Imaging

**Ferdowsi University of Mashhad (FUM)** — Mashhad, Iran  
*B.Sc., Electrical Engineering (Communications)*  
Oct 2014 – Feb 2019 | GPA: 15.8 / 20  
**Thesis:** Smoke Detection using Compressive Sensing and SVM

---

## Publication

**Kazemi, A.**, Abrishami Moghaddam, H., Namiranian, R.  
*Microstructural Analysis of Language Pathways' Development in Term Neonates.* (Manuscript in preparation)

---

## Extra Curricular Activities

**IEEE Student Branch — FUM**  
Feb 2014 – Feb 2018  
- Chairman (2017–18) and Treasurer (2016–17), managing finances and leading branch operations.


