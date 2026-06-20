---
layout: default
title: Research & Projects
permalink: /projects/
---

## Research & Projects

My work spans research in neural decoding and medical imaging and a body of applied machine learning systems built in industry. The research comes first; the applied work follows, and shows the experimental and engineering depth I would bring to a PhD — whether in a biomedical/neuroscience group or an AI lab.

---

## Research

### [Mind2Text — EEG decoding with LLMs](https://github.com/alikaz3mi/mind2text)

**Question**: Can large language models, with symbolic tokenization of neural signals, decode cognitive states from EEG better than conventional models?
**Methods**: Python, PyTorch, Transformers (Hugging Face), LoRA fine-tuning, Pydantic, FastAPI, Docker.
**Result**: **78.2% accuracy with an LLM (LoRA)**, outperforming CNN and SVM baselines — evidence that transformer models transfer to brain-signal classification. An active line of work I want to extend in a PhD.

---

### M.Sc. Thesis — Diffusion-tensor modeling of brain development

**Question**: How do perisylvian white-matter language pathways develop in term neonates, as seen through diffusion tensor imaging (DTI)?
**Methods**: Diffusion-tensor analysis, microstructural metrics, medical-image processing.
**Result**: Characterized microstructural development of language pathways; basis of a manuscript in preparation (*Microstructural Analysis of Language Pathways' Development in Term Neonates*). GPA 18.04/20.

---

## Applied AI Systems

These production projects are where I built the experimental and infrastructure skills — model development, evaluation, and reproducible pipelines — that research depends on.

### [ParsChat — LLM agent platform](https://chat.parstechai.com)

**Objective**: Full lifecycle of a Python AI agent platform handling 20,000+ daily messages across enterprise clients, integrated with existing CRM and e-commerce backends.
**Technologies**: Python, LangGraph, QWEN/vLLM (RTX 5090), RAG, LlamaIndex, ChromaDB, Milvus, Elasticsearch, FastAPI, Docker.
**Outcome**: Graph-based orchestration with intent routing enabling zero-hallucination processing of knowledge bases up to 10 million characters; 60 messages/min throughput; per-user setup cost cut 96% ($2.50 → $0.10).

---

### DastYar — Video analytics

**Objective**: Versatile video-analytics product for GPU and CPU servers, integrating face recognition, people counting, and license-plate recognition.
**Technologies**: Python, GStreamer, PostgreSQL, Django, Vue.js, TensorRT, YOLO, Docker.
**Outcome**: GPU latency 200 → 40 ms, ≈1,000 fps; face-recognition model fine-tuned on 49M+ images to 99.97% accuracy.

---

### DIPAL — Drone photogrammetry backend

**Role**: Backend Engineer (Sensifai BV — SPADE Open Call #2, Sep 2025 – Mar 2026).
**Objective**: Scalable AWS backend automating SfM and MVS pipelines for an open-source photogrammetry toolkit.
**Technologies**: Python, AWS (EC2, SQS, IAM), REST API, GIS, SfM/MVS.
**Outcome**: Aerial drone capture processed into accurate 3D reconstructions and geospatial outputs with REST integration for GIS workflows.

<figure class="shot" markdown="0">
  <a href="https://photogear.sensifai.com" target="_blank" rel="noopener">
    <picture>
      <source srcset="{{ '/assets/img/photogear.webp' | relative_url }}" type="image/webp">
      <img src="{{ '/assets/img/photogear.png' | relative_url }}" width="1200" height="591" loading="lazy" decoding="async" alt="PhotoGear — AWS photogrammetry platform turning drone flights into NDVI maps and 3D models">
    </picture>
  </a>
  <figcaption><b>PhotoGear</b> — the productized photogrammetry platform this backend powers · <span>photogear.sensifai.com</span></figcaption>
</figure>

---

### SensiGesture — Automotive in-cabin AI

**Role**: ML/MLOps Engineer (Sensifai BV, Feb 2022 – Jul 2022).
**Objective**: Real-time in-cabin driver monitoring recognizing gestures and driver activity for automotive-grade edge hardware.
**Technologies**: Python, MobileNetV3, PyTorch, TensorRT, Edge MLOps, Docker.
**Outcome**: Curated 350,000+ annotated RGB frames across day/night/glare/overcast; trained models recognizing 22 gestures and 20 driver-activity classes; end-to-end MLOps pipeline for versioning, evaluation, and on-device deployment.

<figure class="shot" markdown="0">
  <a href="https://sensifai.com/en/portfolio/sensigesture" target="_blank" rel="noopener">
    <picture>
      <source srcset="{{ '/assets/img/sensigesture.webp' | relative_url }}" type="image/webp">
      <img src="{{ '/assets/img/sensigesture.png' | relative_url }}" width="1200" height="591" loading="lazy" decoding="async" alt="SensiGesture — automotive in-cabin driver-monitoring and gesture-recognition system">
    </picture>
  </a>
  <figcaption><b>SensiGesture</b> — in-cabin driver-monitoring product (Sensifai) · <span>sensifai.com</span></figcaption>
</figure>

---

### AshenasAI — eKYC service

**Objective**: AI-driven electronic Know-Your-Customer service: 3D video face verification, signature verification, liveness detection.
**Technologies**: Python, gRPC, FastAPI, Docker, Redis, Celery.
**Outcome**: Five verification modules in 20 seconds end-to-end; face-recognition models fine-tuned on 49M images to 99.97% accuracy.

---

### [Jira Telegram Bot](https://github.com/alikaz3mi/jira-telegram-bot)

**Objective**: Telegram bot to manage Jira tasks directly, without the Jira interface.
**Technologies**: Python, Jira API, Python Telegram Bot.
**Outcome**: Streamlined task management and automated issue tracking.

---

### License Plate Recognition (Edge AI)

**Objective**: Efficient license-plate recognition for real-time processing on edge devices.
**Technologies**: TensorRT, Python, Docker, Jetson Nano, Jetson NX.
**Outcome**: Latency 300 → 25 ms at 95% accuracy; deployed on Jetson Nano (3–5 FPS) and NX (8–12 FPS).

---

### People Counting System

**Objective**: Scalable people-counting for multi-camera surveillance with zone-specific accuracy.
**Technologies**: YOLOx, TensorRT, Celery, Redis, Docker, Python.
**Outcome**: +25% counting accuracy, latency to 1.5 ms; deployed across multiple cameras via Nvidia Docker.

---

### Document Layout & QA (NLP)

**Objective**: NLP system extracting key information from professional websites, with question-answering and document layout analysis.
**Technologies**: LayoutLMv3, SerpAPI, Python.
**Outcome**: 83% accuracy at 200 ms latency; produced 30 distinct output fields, cutting client query response time by 30%.

---

### SensoChat — RAG chatbot

**Objective**: AI chatbot answering customer queries via information extraction and LLMs.
**Technologies**: Retrieval-Augmented Generation (RAG), Python, NLP, Docker, CI/CD.
**Outcome**: +45% query-resolution rate; up to 2,000 requests/min on a 4-core CPU / 8 GB RAM; delivery time 1 week → 5 minutes; setup cost cut 96%.
