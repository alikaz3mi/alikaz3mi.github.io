---
layout: default
title: Projects
permalink: /projects/
---

## Featured Projects

Here is a collection of some of the key projects I have worked on, showcasing my skills in AI, NLP, technical leadership, and scalable system design.

### [Mind2Text](https://github.com/alikaz3mi/mind2text)

**Objective**: A comprehensive framework for EEG signal classification using Large Language Models (LLMs) with symbolic tokenization and efficient fine-tuning.
**Technologies**: Python, PyTorch, Transformers (Hugging Face), LoRA, Pydantic, FastAPI, Docker
**Outcome**: Achieved 78.2% accuracy with LLM (LoRA), outperforming CNN and SVM baselines. Demonstrated the superiority of transformer models for cognitive state classification.

---

### [ParsChat](https://chat.parstechai.com)

**Objective**: Owned the full lifecycle of a Python-based AI agent platform handling 20,000+ daily messages across diverse enterprise clients, integrating agents with existing CRM and e-commerce backend systems.
**Technologies**: Python, LangGraph, QWEN/vLLM (RTX 5090), RAG, LlamaIndex, ChromaDB, Milvus, Elasticsearch, FastAPI, Docker
**Outcome**: Reduced agent delivery time from 1 week to 5 minutes and cut per-user setup costs by 96% ($2.50 → $0.10). Achieved 60 messages/min throughput via graph-based LangGraph orchestration with intent-based routing, enabling zero-hallucination processing of knowledge bases up to 10 million characters.

---

### DastYar

**Objective**: Develop a versatile video analytics product capable of deployment on both GPU and CPU-based servers. Integrated AI pipelines for face recognition, people counting, and license plate recognition.
**Technologies**: Python, Gstreamer, PostgreSQL, Django, Vue.js, TensorRT, YOLO, Docker
**Outcome**: Optimized video analytics (GPU latency 200 → 40 ms, throughput ≈ 1,000 fps). Fine-tuned a large-scale face recognition model on 49M+ images, reaching 99.97% accuracy.

---
### DIPAL — Drone Pipeline Backend

**Role**: Backend Engineer (Sensifai BV — SPADE Open Call #2, Sep 2025 – Mar 2026)
**Objective**: Engineer scalable AWS backend services automating structure-from-motion (SfM) and multi-view-stereo (MVS) pipelines for an open-source photogrammetry toolkit.
**Technologies**: Python, AWS (EC2, SQS, IAM), REST API, GIS, SfM/MVS
**Outcome**: Automated aerial drone capture processing into accurate 3D reconstructions and geospatial outputs with REST API integration for downstream GIS workflows.

---

### SensiGesture — Automotive In-Cabin AI

**Role**: ML/MLOps Engineer (Sensifai BV, Feb 2022 – Jul 2022)
**Objective**: Build a real-time in-cabin driver monitoring system recognizing gestures and driver activity for automotive-grade edge hardware.
**Technologies**: Python, MobileNetV3, PyTorch, TensorRT, Edge MLOps, Docker
**Outcome**: Curated 350,000+ annotated RGB frames across day/night/glare/overcast conditions. Trained models achieving recognition of 22 gestures and 20 driver activity classes (drowsiness, phone use, seatbelt violations). Built end-to-end MLOps pipeline for data versioning, automated evaluation, and on-device deployment.

---
### [Jira Telegram Bot](https://github.com/alikaz3mi/jira-telegram-bot)

**Objective**: Develop a Telegram bot to automate interactions with Jira, allowing users to manage tasks directly from Telegram without the need for Jira’s interface.  
**Technologies**: Python, Jira API, Python Telegram Bot  
**Outcome**: Provided a streamlined experience for Jira users, improving task management efficiency and automating issue tracking.

---

### License Plate Recognition

**Objective**: Develop and deploy a highly efficient license plate recognition system, improving both accuracy and speed to meet real-time processing needs on edge devices.  
**Technologies**: TensorRT, Python, Docker, Jetson Nano, Jetson NX  
**Outcome**: Reduced latency from 300ms to 25ms, achieving 95% accuracy. The model was deployed on Jetson Nano and NX, with 3-5 FPS on Jetson Nano and 8-12 FPS on Jetson NX.

---

### People Counting System

**Objective**: Develop a scalable people-counting system for multi-camera surveillance applications, with zone-specific accuracy and real-time performance.  
**Technologies**: YOLOx, TensorRT, Celery, Redis, Docker, Python  
**Outcome**: Increased counting accuracy by 25% and reduced system latency to 1.5ms. The system was successfully deployed across multiple cameras using Nvidia Docker, improving real-time zone-specific counting.

---

### Doctorate Resume Analysis (NLP)

**Objective**: Build an NLP-based system to extract key information from doctors' websites, including question-answering and document layout analysis.  
**Technologies**: LayoutLMv3, SerpAPI, Python  
**Outcome**: Achieved an 83% accuracy rate with a latency of 200ms. The system processed inputs like doctor names and countries to generate outputs with 30 distinct fields, reducing client query response time by 30%.

---

### Vanguard AI Surveillance System

**Objective**: Develop an AI-based surveillance system capable of handling multiple streams and integrating face recognition, people counting, and license plate recognition in a unified platform.  
**Technologies**: Python, GStreamer, PostgreSQL, Django, Vue.js, TensorRT  
**Outcome**: The system can handle 1000 frames per second (equivalent to streaming from 12 cameras) and record/log 10,000 events per second. This solution improved resource efficiency by 35% and cut hardware costs by 30%.

---

### AshenasAI (eKYC Service)

**Objective**: Build an AI-driven electronic Know Your Customer (eKYC) service, including modules for 3D video face verification, signature verification, and liveness detection.  
**Technologies**: Python, gRPC, FastAPI, Docker, Redis, Celery  
**Outcome**: Optimized for real-time performance, processing five verification modules within 20 seconds. The system resulted in a 50% improvement in scalability and reduced development time from three months to two weeks.

---

### SensoChat

**Objective**: Develop an AI-powered chatbot capable of answering customer queries using information extraction and large language models (LLMs).  
**Technologies**: Retrieval-Augmented Generation (RAG), Python, NLP, Docker, CI/CD  
**Outcome**: Increased customer query resolution rate by 45%, handling up to 2000 requests per minute on a 4-core CPU with 8GB of RAM. The delivery time of the chatbot was reduced from 1 week to 5 minutes, with setup costs lowered by 96%.

