<div align="center">

# Sourav Das

### ML Engineer · Computer Vision · SAP Developer · Full-Stack

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sourav-das-02121996)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:das.sour@northeastern.edu)
[![Portfolio](https://img.shields.io/badge/Live%20Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://www.derm-platform.me)
[![GCP Architect](https://img.shields.io/badge/GCP%20Pro%20Cloud%20Architect-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://cloud.google.com/certification)

</div>

---

## About Me

MS Computer Science student at **Northeastern University** (GPA 3.58) with **3+ years of industry experience** at Accenture as an Application Development Analyst — building enterprise SAP systems and ML-powered applications that operate at scale.

I bridge two worlds: **enterprise backend engineering** (SAP ABAP, S/4HANA, ETL pipelines, REST APIs) and **applied machine learning** (computer vision, NLP, semantic retrieval). I don't just train models — I ship full production systems end to end.

- 🏢 Built & maintained enterprise SAP ecosystems processing millions of records daily at Accenture
- 🔬 Researching multimodal clinical AI for skin cancer diagnosis at Northeastern
- 🤖 Exploring SAP Joule (SAP's generative AI copilot) for intelligent ERP automation
- 📍 Boston, MA — open to full-time SWE / MLE / SAP roles

---

## Work Experience

### Accenture — Application Development Analyst `May 2021 – Dec 2024`

Delivered enterprise SAP solutions across **SAP ECC**, **S/4HANA**, **SAP HANA**, and **SAP Fiori** for large-scale clients.

**SAP ABAP & Backend Engineering**
- Engineered an ETL data migration pipeline transferring **2 million records** from SAP ECC to S/4HANA using standard **BAPIs**, achieving 100% data accuracy through rigorous schema validation
- Developed automated distributed batch processing with **XML-based data transmission**, fault-tolerant retry logic, and schema validation — reducing turnaround from 10.4 → 6.0 hrs and cutting manual effort by **36% (~58 hrs/month)**
- Diagnosed and resolved a critical production defect, restoring **500+ daily automated workflows** and reducing downtime by 40%
- Resolved ~**180 monthly production incidents** across distributed enterprise systems, maintaining **98% SLA compliance**

**SAP Fiori · OData · SAP Gateway · SAP Connectors**
- Integrated SAP Fiori web frontend with backend services via **OData REST APIs (SAP Gateway)**, following SAP architecture best practices
- Led code reviews and implemented automated unit tests, improving Fiori page load time by **20%** and enforcing regression coverage
- Designed and maintained **SAP connector interfaces** for cross-system data exchange, enabling reliable XML/JSON data transmission across distributed SAP landscapes

**SAP HANA**
- Worked on **SAP HANA** as the in-memory database layer backing S/4HANA workloads — optimizing data models, CDS views, and query performance for high-throughput enterprise transactions

**SAP Joule (Generative AI for ERP)**
- Hands-on exploration of **SAP Joule**, SAP's embedded generative AI copilot, for intelligent workflow automation, natural-language ERP queries, and AI-assisted incident triage within the SAP Business Technology Platform (BTP)

---

### Wefivesoft — Software Engineer Trainee `Mar 2021 – May 2021`

- Built RESTful microservices and APIs in **C# (ASP.NET)** with transaction management for the LMS Markers Pro platform
- Optimized API performance by **40%** via async/await patterns and implemented data validation for improved reliability

---

## Featured Projects

### 🩺 Multimodal Skin Cancer Detection — *Medical AI · Computer Vision · NLP*
> 6-class clinical skin lesion classifier fusing visual and textual patient data with Explainability.

- Built on **PAD-UFES-20** using **MedSigLIP** (vision) + **ClinicalBERT** (text) with **cross-attention fusion**
- Benchmarked across 10 text encoders; includes fairness evaluation and **XAI** (Explainable AI) visualizations
- Deployed as a **Streamlit** interactive demo at [derm-platform.me](https://www.derm-platform.me/)
- **Stack:** PyTorch · scikit-learn · OpenCV 4 · HuggingFace · Streamlit · XAI

[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/Sourav-02121996/multimodal-skin-cancer-detection)
[![Live](https://img.shields.io/badge/Live-Demo-28a745?style=flat-square)](https://www.derm-platform.me/)

---

### 🔍 Semantic Search & Recommendation Engine — *NLP · Information Retrieval · FAISS*
> High-performance dense retrieval pipeline with LLM embeddings and approximate nearest-neighbor indexing.

- Used **Sentence-Transformers** for LLM embeddings + **FAISS** (IVF-Flat & IVFPQ) for scalable ANN search
- Achieved **95% recall@10**, **80% smaller index**, and **5× faster queries** vs. exact search
- Covers NLP, Generative AI, and Recommendations/Ranking use cases
- **Stack:** Python · FAISS · Sentence-Transformers · HuggingFace · pytest

[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/Sourav-02121996/Semantic_Retrieval)

---

### 🧠 Brainstorm BCI Track 1 — *Brain-Computer Interface · EEG Signal Processing*
> Neural signal decoding system for motor-imagery tasks, built for a BCI competition track.

- EEG signal processing and classification pipeline using temporal convolution networks
- Frequency-domain feature extraction for motor-imagery classification
- **Stack:** Python · MNE · PyTorch · NumPy

[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/Sourav-02121996/Brainstorm-BCI-Track1)

---

### 🏆 Sports Celebrity Image Classifier — *Computer Vision · Full-Stack ML App*
> End-to-end ML web app: OpenCV face detection → wavelet features → scikit-learn classifier → live deployment.

- OpenCV face detection + **PyWavelets** feature extraction + scikit-learn SVM classifier
- Flask REST API backend with JavaScript/Bootstrap frontend; deployed live on Render
- **Stack:** Python · Flask · scikit-learn · OpenCV · NumPy · PyWavelets · JavaScript · Bootstrap

[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/Sourav-02121996/Sport_Celebrity_Image_Classification)
[![Live](https://img.shields.io/badge/Live-Demo-28a745?style=flat-square)](https://frontend-image-classification.onrender.com/)

---

### 👁️ Recognition Using Deep Networks — *Deep Learning · Architecture Benchmarking*
> Systematic benchmark of CNN and ViT architectures on visual recognition tasks.

- Compared **ResNet**, **EfficientNet**, and **Vision Transformer (ViT)** on recognition benchmarks
- Custom training loops, data augmentation, and ablation studies
- **Stack:** PyTorch · torchvision · Matplotlib

[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/Sourav-02121996/Recognition-using-Deep-Networks)

---

### 🥽 Calibration and Augmented Reality — *Computer Vision · AR*
> Real-time camera calibration pipeline with 3D AR object overlay.

- Full camera calibration (intrinsics, extrinsics, distortion) + pose estimation for AR overlays
- **Stack:** Python · OpenCV · NumPy

[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/Sourav-02121996/Calibration-and-Augmented-Reality)

---

### 📦 LostNFound — *Full-Stack Web App*
> Real-time lost-and-found platform with geolocation, image upload, and category filtering.

- REST API backend with JWT auth, image upload, and geolocation filtering; React frontend
- **Stack:** Node.js · Express · MongoDB · React · Render

[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/Sourav-02121996/Project_4_LostNFound)
[![Live](https://img.shields.io/badge/Live-Demo-28a745?style=flat-square)](https://lostnfound-dwz6.onrender.com/)

---

### 🍔 Grill and Go — *Full-Stack Web App*
> Restaurant ordering and menu management application with full CRUD operations.

- **Stack:** Node.js · Express · PostgreSQL · React · Render

[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/Sourav-02121996/Project2_Grill_and_Go)
[![Live](https://img.shields.io/badge/Live-Demo-28a745?style=flat-square)](https://project2-grill-and-go.onrender.com/)

---

## Tech Stack

**ML / AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**SAP Ecosystem**

![SAP](https://img.shields.io/badge/SAP%20ABAP-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![SAP HANA](https://img.shields.io/badge/SAP%20HANA-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![S4HANA](https://img.shields.io/badge/S%2F4HANA-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![SAP Fiori](https://img.shields.io/badge/SAP%20Fiori-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![SAP Joule](https://img.shields.io/badge/SAP%20Joule%20AI-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![OData](https://img.shields.io/badge/OData%20%2F%20SAP%20Gateway-0FAAFF?style=flat-square&logo=sap&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![CSharp](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Web & Cloud**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes%20AKS-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

---

## Certifications

| Badge | Certification | ID |
|---|---|---|
| ![GCP](https://img.shields.io/badge/GCP-Professional%20Cloud%20Architect-4285F4?style=flat-square&logo=googlecloud&logoColor=white) | Google Cloud Certified — Professional Cloud Architect | `100076` |
| ![GCP](https://img.shields.io/badge/GCP-Associate%20Cloud%20Engineer-4285F4?style=flat-square&logo=googlecloud&logoColor=white) | Google Cloud Certified — Associate Cloud Engineer | `139218` |

---

## GitHub Stats

<div align="center">

![Sourav's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Sourav-02121996&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Sourav-02121996&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

*3+ years of enterprise engineering · MS Computer Science @ Northeastern · Google Cloud Certified*

**Open to full-time roles in ML Engineering, Software Engineering, and SAP Development.**

</div>
