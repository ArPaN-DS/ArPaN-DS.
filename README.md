<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,45:161b22,100:0f4c81&height=230&section=header&text=Arpan%20Majumdar&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=Data%20Scientist%20%7C%20ML%20Engineer%20%7C%20NLP%20%2F%20LLM%20Engineer%20%7C%20Speech%20%26%20Multimodal%20AI&descSize=18&descColor=d0d7de&descAlignY=56&animation=fadeIn" alt="header" width="100%" />
</p>

<p align="center">
  Building production-grade AI systems across speech forensics, multimodal deepfake detection, NLP, RAG, and real-world ML backends.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/arpan-majumdar-"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/ArPaN-DS"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="mailto:arpanmajumdar952@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Speech%20AI-0f4c81?style=flat-square" alt="Speech AI"/>
  <img src="https://img.shields.io/badge/Multimodal%20AI-1f6feb?style=flat-square" alt="Multimodal AI"/>
  <img src="https://img.shields.io/badge/NLP%20%26%20LLMs-238636?style=flat-square" alt="NLP and LLMs"/>
  <img src="https://img.shields.io/badge/RAG%20%26%20Agents-7c3aed?style=flat-square" alt="RAG and Agents"/>
  <img src="https://img.shields.io/badge/Production%20ML-b45309?style=flat-square" alt="Production ML"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ArPaN-DS&style=for-the-badge&color=0f4c81&label=PROFILE+VIEWS" alt="Profile Views"/>
  <img src="https://img.shields.io/github/followers/ArPaN-DS?style=for-the-badge&color=0f4c81&labelColor=161b22&logo=github" alt="Followers"/>
</p>

---

## About

I am a Data Science graduate from the University of Kalyani focused on building AI systems that move beyond notebooks into production workflows. My work sits at the intersection of speech AI, multimodal deepfake detection, NLP, LLM applications, and scalable backend engineering.

I have worked on research and applied systems spanning SemEval and CLEF competition pipelines, multilingual claim verification, real-time audio and video analysis, forensic speaker recognition, and LLM-assisted decision support. My current strongest work comes from the RKMV R&D team in industry collaboration with FaceOff Technology, where I have been building public-safe speech and multimodal AI systems for real-world use cases.

> I do not just train models. I build end-to-end systems that listen, reason, detect, summarize, and deliver usable intelligence.

---

## What I Build

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Speech AI and Audio Forensics</h3>
      <p>Speaker recognition, diarization, deepfake audio detection, emotion analysis, telephony-aware preprocessing, and evidence-oriented speech pipelines.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Multimodal Deepfake Detection</h3>
      <p>Audio plus video analysis systems that combine WavLM, ViT, MediaPipe, temporal smoothing, and live meeting-stream inference.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>NLP, RAG, and LLM Applications</h3>
      <p>Transcript intelligence, multilingual sentiment workflows, research retrieval, Gemini-powered assistants, and analysis-aware chat systems.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Production ML Backends</h3>
      <p>Django, FastAPI, Celery, Redis, WebSockets, async processing, PDF reporting, and operational pipelines designed for real users and long-running workloads.</p>
    </td>
  </tr>
</table>

---

## Selected AI Systems

<p>
  Public-safe highlights from the <strong>RKMV R&amp;D team in industry collaboration with FaceOff Technology</strong>. Descriptions below are intentionally written to protect NDA boundaries while still showing technical depth.
</p>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>SWAR CHIHNAYAN</h3>
      <p><strong>Forensic speaker recognition for degraded audio evidence.</strong></p>
      <p>
        Built an offline-first pipeline for extracting target voices from noisy wiretap-style recordings using ECAPA-TDNN, Silero VAD, quality-gated preprocessing, adaptive similarity scoring, and temporal clustering.<br/>
        Designed the backend for scalable batch processing, evidence packaging, and timestamped reporting suitable for high-traceability forensic workflows.
      </p>
      <p><strong>Stack:</strong> PyTorch, SpeechBrain, Silero VAD, Librosa, SciPy, Django, Celery, Redis, ReportLab</p>
    </td>
    <td width="50%" valign="top">
      <h3>FACE_MEET</h3>
      <p><strong>Real-time meeting intelligence with multimodal risk analysis.</strong></p>
      <p>
        Architected a live meeting-analysis system that captures audio and video streams, performs emotion analysis, audio deepfake detection, and visual spoof checks, then pushes results over WebSockets to an interactive frontend.<br/>
        Added session logging and risk-oriented report generation for auditable post-meeting review.
      </p>
      <p><strong>Stack:</strong> Django Channels, LiveKit, WebSockets, WavLM, MediaPipe, ViT, OpenCV, ReportLab</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Call Screener</h3>
      <p><strong>Telephony-focused fraud screening and live speech intelligence.</strong></p>
      <p>
        Developed a real-time call analysis workflow that ingests telephony audio, performs speech detection, transcription, translation, deepfake-risk scoring, and emotion inference, then converts segment-level outputs into explainable forensic signals.<br/>
        Focused on robust streaming behavior, multilingual handling, and production-style API delivery.
      </p>
      <p><strong>Stack:</strong> FastAPI, Twilio Media Streams, Whisper, Gemini, WavLM, asyncpg, PostgreSQL, Docker</p>
    </td>
    <td width="50%" valign="top">
      <h3>Audio-Text Agent</h3>
      <p><strong>LLM-assisted transcript intelligence for audio and video cases.</strong></p>
      <p>
        Engineered a session-aware assistant that answers questions over processed cases using transcript context, multilingual sentiment outputs, diarization signals, and analysis-conditioned prompting.<br/>
        Combined transcript generation, speaker-aware text analytics, and chat history persistence for traceable multi-turn investigation workflows.
      </p>
      <p><strong>Stack:</strong> Django, Gemini 1.5, Whisper, Hugging Face, SpeechBrain, Librosa, Parselmouth, Celery</p>
    </td>
  </tr>
</table>

---

## Research and Recognition

- Published at **ACL 2025 (SemEval Workshop)** for multilingual claim retrieval using transformer-based ranking pipelines.
- Published at **CLEF 2025** with a dual-encoder scientific discourse detection system achieving **Macro F1 = 0.8262** and **9th global rank**.
- Built cross-lingual retrieval systems for **SemEval-2025 Task 7**, reaching **22nd global rank**.
- Contributed to multilingual fact-checking research on Indian-language news datasets with transformer-based evidence retrieval workflows.

---

## Public Repositories

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ArPaN-DS/music-mood-classification">music-mood-classification</a></h3>
      <p>Audio feature engineering and machine learning for mood prediction from music tracks.</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ArPaN-DS/Bank-Customer-Classification-MLP">Bank-Customer-Classification-MLP</a></h3>
      <p>PySpark-based customer classification with large-scale preprocessing and MLP-driven modeling.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ArPaN-DS/Fraud-Detection-Model-Development">Fraud-Detection-Model-Development</a></h3>
      <p>End-to-end fraud detection workflow with data preprocessing, feature engineering, and machine-learning modeling.</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ArPaN-DS/reddit-AI-bot">reddit-AI-bot</a></h3>
      <p>LLM-powered reply automation built around prompt-based response generation and real-time interaction loops.</p>
    </td>
  </tr>
</table>

<p>
  Additional public work includes <a href="https://github.com/ArPaN-DS/breast-cancer-diagnostic">breast-cancer-diagnostic</a>,
  <a href="https://github.com/ArPaN-DS/Zomato-Data-Analysis">Zomato-Data-Analysis</a>, and other data-science projects across ML, analytics, and automation.
</p>

---

## Core Stack

**Languages**  
Python, R, SQL, JavaScript, HTML, CSS

**Speech and Audio AI**  
WavLM, Wav2Vec2, ECAPA-TDNN, Silero VAD, Whisper, Librosa, SoundFile, FFmpeg, Praat / Parselmouth

**NLP and GenAI**  
Transformers, Hugging Face, Gemini, OpenAI, LLaMA, MiniLM, XLM-RoBERTa, MuRIL, SciBERT, FAISS, RAG

**ML, DL, and Data**  
PyTorch, TensorFlow, scikit-learn, XGBoost, LightGBM, PySpark, Pandas, NumPy

**Backend and MLOps**  
Django, Django Channels, FastAPI, Flask, Celery, Redis, WebSockets, PostgreSQL, MySQL, Docker, AWS, Linux VPS

**Computer Vision**  
MediaPipe, OpenCV, ViT, Face Mesh

---

## GitHub Snapshot

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ArPaN-DS&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&ring_color=58a6ff" alt="GitHub Stats" width="49%"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ArPaN-DS&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" alt="Top Languages" width="49%"/>
</p>

---

## Contact

<p align="center">
  <a href="https://www.linkedin.com/in/arpan-majumdar-">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:arpanmajumdar952@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

<p align="center">
  Open to conversations around speech AI, multimodal intelligence, NLP, LLM systems, and research-driven ML engineering.
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,45:161b22,100:0f4c81&height=120&section=footer" width="100%" />
</p>
