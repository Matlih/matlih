# Montazar Matlih

**Applied AI Engineer — Edge Computer Vision & Multi-Agent Systems**

Founder, ChipSentinel · BSCS-ML Student

*"Building intelligent systems where time is currency."*

I build computer vision and agentic AI systems that run on constrained, real-world hardware — from a DOST-endorsed waste classifier to a satellite-based disaster-response pipeline.

<div align="left">
  <a href="https://linkedin.com/in/montazar-matlih">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://www.researchgate.net/profile/Montazar-Matlih">
    <img src="https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=ResearchGate&logoColor=white" alt="ResearchGate" />
  </a>
  <a href="https://lablab.ai/u/@matlih">
    <img src="https://img.shields.io/badge/Lablab.ai-000000?style=for-the-badge&logo=c&logoColor=white" alt="Lablab.ai" />
  </a>
</div>

---

## Validated Track Record

- 🥇 **1st Place, Project IMPACT (NU-D × REZBIN)** — endorsed by DOST Calabarzon & DSWD for regional edge-AI deployment
- 🏗️ **2× AMD Developer Hackathon Projects** — engineered a 24-hour hybrid edge-to-cloud C4ISR system and shipped a live multi-agent disaster-response pipeline on MI300X/ROCm 6.0
- 🗜️ **75% INT8 Model Compression (TSEK)** — reduced a 1.12 GB (FP32) mDeBERTa model to ~280 MB via 8-bit dynamic quantization for fast in-browser inference at 92.2% accuracy
- 📊 **94.2% mAP@50** — custom 9-class aerial POV vehicle detection, full methodology in technical report
- 🎤 **3× invited speaker** — NUD STEM Career Fair (A.Y. 2024–25, 2025–26), Campus Tour (A.Y. 2025-26)

---

## Currently Building

### ChipSentinel
Startup · `May 2026 → Present`

Edge-deployed anomaly detection for semiconductor and PCB manufacturing lines. Passive visual inspection designed to catch defects before they hit yield — built on PatchCore for edge inference and Qwen-VL for scene-level reasoning, served through FastAPI/React, running on AMD MI300X/ROCm 6.0.

**Stack:** AMD MI300X · ROCm 6.0 · PatchCore · Qwen-VL · FastAPI · React

**→ [Landing Page](https://chipsentinel.cloud/)**

### Blacksite Node
Free & Source-Available Software · `May 2026 → Present`

Zero-knowledge password manager and secure notepad with memory-hard constraints and a cryptographic duress protocol. Uses an NLP-based password evaluator to move beyond traditional rule-based strength meters; steganographic export via LSB/EOF; BIP-39 passphrase generation across 12,288 words in 6 languages (EN/ES/FR/IT/PT/CZ).

**Stack:** Rust · Tauri v2 · Argon2id · ChaCha20-Poly1305

**→ [Repository](https://github.com/Matlih/Blacksite-Node) · [Releases](https://github.com/Matlih/Blacksite-Node/releases)**

### Prod
FOSS (Free and Open Source Software) · `July 2026 → Present`

A minimalist desktop timer built to enforce the 90/15 Ultradian rhythm and prevent developer burnout. Engineered for zero visual bloat and an extremely low resource footprint using a native Rust backend. Features persistent window state memory via Tauri IPC, hardware-accelerated responsive animations, and custom-synthesized Web Audio API alerts.

**Stack:** Rust · Tauri · React · TypeScript · Web Audio API

**→ [Repository](https://github.com/Matlih/Prod) · [Releases](https://github.com/Matlih/Prod/releases)**


---

## Flagship Projects

### ShellWise Smart Bin — Project IMPACT
🥇 **1st Place — NU-D × REZBIN** · Endorsed by DOST Calabarzon & DSWD · `April 2026`

Edge-deployed waste classification system running real-time inference on resource-constrained hardware. The DOST/DSWD endorsement specifically cites it for regional edge-AI integration.

**Stack:** YOLO11n · Edge Inference · Python

**→ [Repository](https://github.com/Matlih/ShellWise-Smart-Bin)**

### TSEK — Real-Time Fact-Checking System
UNESCO Youth Hackathon 2026 · `July 2026`

A cross-lingual Chrome Extension and web app that fact-checks claims in real-time while preserving privacy. It uses an in-browser local ML gatekeeper to filter out opinions and UI boilerplate, meaning only verifiable claims are sent to the backend. Achieved 92.2% peak accuracy, using 8-bit dynamic quantization to compress the mDeBERTa-v3-base model from 1.12 GB (FP32) to ~280 MB (INT8) for lightning-fast browser execution.

**Stack:** React · Transformers.js · mDeBERTa (INT8) · Vercel Serverless · Gemini API

**→ [Repository](https://github.com/Matlih/TSEK)**

### Ocular Sentinel — Autonomous C4ISR
AMD Developer Hackathon: ACT II · `July 2026`

An Autonomous C4ISR Security System that bridges ultra-fast edge detection with deep cloud-based multimodal reasoning. It runs a lightweight YOLO11n Edge Tripwire with a rolling frame buffer. Upon anomaly detection, downscaled timelapse frames are sampled and sent to a ROCm-accelerated Qwen2-VL model to generate rich, zero-shot tactical reports without relying on static bounding boxes.

**Stack:** React · FastAPI · WebSockets · YOLO11n · Qwen2-VL · vLLM · AMD ROCm

**→ [Repository](https://github.com/Matlih/OcularSentinel)**

### Project ARK — Autonomous Reconnaissance Kinematics
AMD Developer Hackathon · `May 2026`

Agentic pipeline that turns raw satellite telemetry (ESA Sentinel-2 L2A, NASA EONET) into disaster-response directives — engineered for under-60-second turnaround against a 72–96 hour manual-assessment baseline. Multi-agent orchestration (LangGraph) over a geospatial foundation model (Prithvi-100M) and Qwen-VL, running on AMD MI300X (192GB HBM3) / ROCm 6.0.

**Stack:** AMD MI300X · ROCm 6.0 · LangGraph · Prithvi-100M · Qwen-VL · XGBoost

**→ [Repository](https://github.com/Matlih/Project_ARK) · [Live Deployment](https://project-ark-mu.vercel.app/) · [Hackathon Certificate](https://lablab.ai/u/@matlih/ai-hackathons/amd-developer/certificate)**

### Aerial Vehicle Detection — 94.2% mAP@50
Academic Research Capstone · `June 2025`

Real-time, multi-class detection pipeline trained on a custom, manually annotated dataset spanning 9 vehicle types — PUJ, SUV, van, pickup, sedan, truck, bus, motorcycle, emergency — from an aerial perspective.

**Stack:** YOLO11 · CNNs · Python

**→ [Repository](https://github.com/Matlih/Aerial-View-Vehicle-Detection) · [Technical Report](https://doi.org/10.13140/RG.2.2.31747.46888)**

---

## Live Technical Demonstrations

### JARVIS Vision — Multimodal Edge Interface
Invited Speaker, NUD STEM Career Fair · `June 2026`

Real-time object detection and voice-controlled agent built for a live technical demo. Wake-word activation, fully local inference, dynamic scene narration via Edge TTS.

**Stack:** YOLO11n · Edge TTS · Speech Recognition · OpenCV

**→ [Repository](https://github.com/Matlih/JARVIS-Vision)**

### Cultural Garment Detection
Live Demonstration, NUD STEM Career Fair · `June 2025`

Rapid-inference CV pipeline for traditional garment identification — the first live technical demo.

**Stack:** YOLO11 · Python

**→ [Repository](https://github.com/Matlih/NU-Traditional-Uniform-Detection)**

---

### 🛠 Technical Skills

| Domain | Technologies & Methodologies |
| :--- | :--- |
| **AI & Machine Learning** | Multi-Agent LLM Orchestration (LangGraph), Vision-Language Models (Qwen-VL), Multimodal Fine-Tuning (LoRA), NLP (LSTM/RNN), CV (CNNs & YOLO Architectures), Geospatial Foundation Models (Prithvi), XGBoost, Edge TTS, OpenCV, Model Compression (INT8 Quantization). |
| **Systems & Edge Compute** | Bare-metal GPU provisioning (AMD MI300X, ROCm 6.x), Edge Inference (PatchCore), Full-Stack Integration (FastAPI, React), Systems Architecture Layout, In-Browser ML (Transformers.js), LLM Serving (vLLM). |
| **Security Architecture** | Rust Cryptographic Engineering (Argon2id, Tauri IPC), Steganography (LSB/EOF), Zero-Knowledge Infrastructure, Offline Threat Modeling. |
| **Leadership & Strategy** | Cross-functional team direction, predictive architecture, risk elimination, technical public speaking. |
