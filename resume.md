---
layout: default
title: CV
permalink: /resume/
---

# Ali Kazemi
**Researcher in Biomedical AI, Computational Neuroscience & Data Science — seeking a funded PhD**
📍 Mashhad, Iran | Open to relocation | 📧 [alikazemi@ieee.org](mailto:alikazemi@ieee.org) | 📱 (+98) 915-239-0307
🔗 [LinkedIn](https://www.linkedin.com/in/ali-kazemi-199510/) | [GitHub](https://github.com/alikaz3mi) | [Research Statement](/research/)

---

## Profile

Researcher at the intersection of biomedical engineering, computational neuroscience, and data science. M.Sc. in biomedical engineering with a thesis on diffusion-tensor modeling of brain development, plus six years building production machine learning systems. I combine research training in neural-signal and medical-image modeling with hands-on depth in deep learning, LLMs, and the engineering needed to run experiments at scale. I am seeking a funded PhD in biomedical AI, neural-signal or medical-image analysis, or applied machine learning — bringing measurable, reproducible experimentation from industry into published research.

**Research interests:** computational neuroscience and neural-signal analysis (EEG, spike sorting, BCI); medical imaging and biomedical data science (diffusion MRI, deep learning for clinical data); machine learning and LLMs (efficient inference, RAG, agentic and trustworthy AI).

---

## Education

**Khajeh Nasir University of Technology (KNTU)** — Tehran, Iran
*M.Sc., Biomedical Engineering (Bioelectric)* | Oct 2019 – Feb 2023 | GPA: 18.04 / 20
**Thesis:** *Modeling of Human Brain Perisylvian Pathways Development with Diffusion Tensor Imaging* — diffusion-tensor analysis of white-matter language-pathway development in term neonates.

**Ferdowsi University of Mashhad (FUM)** — Mashhad, Iran
*B.Sc., Electrical Engineering (Communications)* | Oct 2014 – Feb 2019 | GPA: 15.8 / 20
**Thesis:** *Smoke Detection using Compressive Sensing and SVM.*

**English:** TOEFL iBT 105/120.

---

## Publications & Research

- **Kazemi, A.**, Abrishami Moghaddam, H., Namiranian, R. *Microstructural Analysis of Language Pathways' Development in Term Neonates.* (Manuscript in preparation.)
- **Mind2Text** — independent research project: EEG signal classification with large language models using symbolic tokenization and LoRA fine-tuning. Achieved **78.2% accuracy** and beat CNN and SVM baselines, which is evidence that transformer models transfer to cognitive-state decoding. [Code](https://github.com/alikaz3mi/mind2text).

---

## Research-Relevant Technical Skills

- **Deep learning & ML:** PyTorch, TensorFlow, Transformers (Hugging Face), LoRA / parameter-efficient fine-tuning, Scikit-learn, OpenCV; computer vision, NLP/NER, sequence and signal modeling.
- **LLMs & agents:** RAG and retrieval systems, agent orchestration (LangGraph, LlamaIndex), vector databases (ChromaDB, Milvus, Elasticsearch); structured evaluation of open-source and API models across accuracy, latency, and cost.
- **Experimental infrastructure (MLOps):** Docker, Kubernetes, CI/CD, Infrastructure as Code (Ansible), model serving (FastAPI, gRPC, vLLM, TensorRT), reproducible pipelines and evaluation harnesses.
- **Software engineering:** Python 3.x (asyncio, type hints, OOP, design patterns), test-driven development, modular architecture, code review.
- **Cloud & data:** AWS (EC2, SQS, IAM, CloudWatch), Prometheus/Grafana, PostgreSQL, MongoDB, edge AI (Jetson Nano/NX).

---

## Research & Engineering Experience

*Framed for research relevance: experimental design, model development and evaluation, and the infrastructure that makes studies reproducible.*

### ParsTech AI — Product Tech Lead
*Mashhad, Iran | Jul 2020 – Present*

**ParsChat — LLM agent platform** *(Nov 2022 – Present)*
- Built and evaluated a graph-based LLM agent system (LangGraph) with intent routing and state management, enabling reliable, **zero-hallucination** processing of knowledge bases up to **10 million characters**.
- Ran a structured model-selection study (QWEN vs. competing OSS/API models) across accuracy, latency, and cost; deployed via **vLLM on RTX 5090** at **60 messages/min**, and maintained an evaluation harness tracking quality regressions across model versions.
- Reduced per-user inference setup cost by **96%** ($2.50 → $0.10) — a measured efficiency result, not an estimate.

**Autonomous AI agent** *(ParsTech)*
- Designed a production agent processing multimodal inputs (voice, text, image) to route and assign Jira issues autonomously, cutting mean diagnosis time from 8 hours to 20 minutes.

**MLOps & experimental infrastructure**
- Architected Infrastructure-as-Code workflows (GitLab CI/CD, Ansible) to provision GPU clusters, cutting environment setup from days to hours.
- Migrated to containerized AWS EC2 microservices with SQS queuing (99.9% uptime) and Prometheus/Grafana/CloudWatch monitoring for model drift and latency.

**AshenasAI (eKYC & biometrics)** *(Feb 2023 – Jul 2023)*
- Developed and evaluated a 5-module biometric pipeline (liveness detection, 3D face verification, OCR, matching); **fine-tuned face-recognition models on 49M images** (NVIDIA A6000) to **99.97% accuracy**, then optimized for real-time CPU inference (20 s end-to-end).

**DastYar — AI Tech Lead** *(Aug 2021 – Oct 2022)* and **ML Engineer** *(Jul 2020 – Jul 2021)*
- Optimized video-analytics models (GPU latency 200 → 40 ms, ≈1,000 fps); trained a lightweight YOLO detector (84% mAP, ~1 ms TensorRT).
- Trained OCR and gesture-recognition systems, **reducing handwriting word-error rate to 3%** (from 20%); optimized detection models (TensorRT) for Jetson Nano/NX edge deployment.

### Sensifai BV — Freelance Research Engineer
*Remote (Belgium) | Feb 2022 – Jul 2022 | Sep 2025 – Mar 2026*

**DIPAL** *(SPADE Open Call #2, Sep 2025 – Mar 2026)*
- Engineered AWS backend services automating structure-from-motion (SfM) and multi-view-stereo (MVS) pipelines for an open-source photogrammetry toolkit, turning aerial drone captures into 3D reconstructions and geospatial outputs.

**SensiGesture** *(Automotive in-cabin AI, Feb 2022 – Jul 2022)*
- Curated a **350,000+ frame** annotated dataset across day/night/glare/overcast conditions; trained MobileNetV3 models recognizing **22 gestures and 20 driver-activity classes** for real-time edge inference, with a full data-versioning and evaluation pipeline.

---

## Service & Activities

**IEEE Student Branch — FUM** *(Feb 2014 – Feb 2018)*
Chairman (2017–18) and Treasurer (2016–17), leading branch operations and finances.
