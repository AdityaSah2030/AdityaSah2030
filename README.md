<h1 align="center">Hi, I'm Aditya Kumar Sah 👋</h1>

<h3 align="center">Computer Science Engineering Student | AI/ML | Generative AI | Computer Vision</h3>

<div align="center">
  <a href="https://adityasah2030.github.io/MyPortfolio/"><img src="https://img.shields.io/badge/Portfolio-Visit%20Website-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>  <a href="https://www.linkedin.com/in/adityasah2030"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>  <a href="https://mail.google.com/mail/?view=cm&fs=1&to=adityasah2030@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Contact Me"/></a>
</div>

---

## 👨‍💻 About Me

I'm a Computer Science and Engineering student specializing in Artificial Intelligence and Machine Learning at **Techno Main Salt Lake, Kolkata**.

I enjoy building practical applications that combine AI/ML, backend engineering, and computer vision. My projects range from a multi-document research paper assistant powered by RAG to facial recognition systems and autonomous robotics.

* **Building:** AI-powered applications, RAG systems, and computer vision projects.
* **Exploring:** Generative AI, machine learning, and intelligent systems.
* **Core Technologies:** Python, FastAPI, PostgreSQL, LangChain, and OpenCV.
* **Currently Learning:** Data Structures & Algorithms, Machine Learning, and Software Engineering.
* **Community:** Media & Content Lead at GDG On Campus, Techno Main Salt Lake.

---

## 🚀 Featured Projects

### 1. Research Paper Assistant | Multi-Document RAG

An AI-powered research assistant for querying multiple research papers and generating context-grounded answers with page-level source attribution.

<table>
<tr>
<td><b>Key Features</b></td>
<td>

- **PDF Processing:** Extracted text page by page and split it into overlapping chunks using LangChain.
- **Semantic Search:** Generated Gemini embeddings and stored them in Qdrant for vector similarity retrieval.
- **Multi-Paper Retrieval:** Retrieved relevant passages independently from each document for cross-paper question answering.
- **Context-Grounded Answers:** Used Google Gemini to generate answers from retrieved passages with document and page citations.
- **Session Isolation:** Separated document workspaces using session IDs to prevent cross-session retrieval.
- **Document Versioning:** Replaced older uploads of the same filename without deleting other indexed papers.

</td>
</tr>
<tr>
<td><b>Tech Stack</b></td>
<td>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" />
</td>
</tr>
<tr>
<td><b>Links</b></td>
<td>
<a href="https://github.com/AdityaSah2030/research-paper-assistant"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://research-paper-assistant-pwd1.onrender.com/"><img src="https://img.shields.io/badge/Live-Demo-2EA44F?style=for-the-badge&logo=render&logoColor=white" /></a>
</td>
</tr>
</table>

### 2. Vision Studio | Face Recognition & Computer Vision

A computer vision application combining facial recognition, biometric matching, image-to-ASCII conversion, and interactive visual effects.

<table>
<tr>
<td><b>Key Features</b></td>
<td>

- **Face Enrollment:** Registered users with six facial poses for multi-pose biometric matching.
- **Facial Embeddings:** Generated normalized 512-dimensional facial representations using InsightFace.
- **Similarity-Based Recognition:** Matched faces using PostgreSQL, pgvector, cosine distance, and configurable similarity thresholds.
- **Multi-Match Scoring:** Aggregated top-k pose matches to improve user identification.
- **Image-to-ASCII Conversion:** Applied bilateral denoising, CLAHE contrast enhancement, and grayscale-to-character mapping.
- **Live Visual Filters:** Implemented ASCII Art, Neon Edge Contours, Thermal Vision, Retro 8-Bit, and Pop-Art Halftone effects.
- **Interactive Filter Controls:** Added adjustable resolution, contrast, color palettes, mirroring, and image export options.

</td>
</tr>
<tr>
<td><b>Tech Stack</b></td>
<td>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
<img src="https://img.shields.io/badge/InsightFace-000000?style=flat-square" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/pgvector-336791?style=flat-square" />
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
</td>
</tr>
<tr>
<td><b>Links</b></td>
<td>
<a href="https://github.com/AdityaSah2030/vision-studio"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://drive.google.com/drive/u/2/folders/19eNkXj5W27Hor5zScRLDKerBJTpqyg6F"><img src="https://img.shields.io/badge/Google_Drive-Project_Showcase-4285F4?style=for-the-badge&logo=googledrive&logoColor=white" /></a>
</td>
</tr>
</table>

### 3. Line Following Robot | PID-Based Autonomous Navigation

An autonomous robot that uses sensor feedback and PID control for path tracking, motor-speed adjustment, and track recovery.

<table>
<tr>
<td><b>Key Features</b></td>
<td>

- **Line Position Sensing:** Calculated track position using an 8-channel IR sensor array.
- **PID-Based Navigation:** Implemented proportional, integral, and derivative control to correct tracking errors.
- **Differential Motor Control:** Adjusted left and right motor speeds through a TB6612FNG motor driver.
- **Wireless PID Tuning:** Modified Kp, Ki, and Kd parameters in real time using an HC-05 Bluetooth module.
- **Crossroad & Finish-Line Detection:** Implemented track detection logic for intersections and the finish line.
- **Lost-Line Recovery:** Added recovery logic to help the robot reacquire the track.
- **Serial Debugging:** Enabled runtime monitoring of sensor readings and control parameters.

</td>
</tr>
<tr>
<td><b>Tech Stack</b></td>
<td>
<img src="https://img.shields.io/badge/Arduino_Nano-00979D?style=flat-square&logo=arduino&logoColor=white" />
<img src="https://img.shields.io/badge/Embedded_C%2FC++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/PID_Control-6A5ACD?style=flat-square" />
<img src="https://img.shields.io/badge/IR_Sensor_Array-555555?style=flat-square" />
<img src="https://img.shields.io/badge/Bluetooth_HC--05-0082FC?style=flat-square" />
</td>
</tr>
<tr>
<td><b>Links</b></td>
<td>
<a href="https://github.com/AdityaSah2030/line-following-robot-pid"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://drive.google.com/file/d/1wBVVs2DsTPJmfV0YM2yuASs2mvwEGUs9/view"><img src="https://img.shields.io/badge/Watch-Working_Demo-FF0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>
</td>
</tr>
</table>

---

## 🛠️ Technical Skills

<table>
  <tr>
    <td><strong>Programming Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
      <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C"/>
    </td>
  </tr>
  <tr>
    <td><strong>AI/ML & Data Science</strong></td>
    <td>
      <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
      <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
      <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=matplotlib&logoColor=white" alt="Matplotlib"/>
      <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="Scikit-learn"/>
      <img src="https://img.shields.io/badge/OpenCV-27338E?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
    </td>
  </tr>
  <tr>
    <td><strong>Generative AI & RAG</strong></td>
    <td>
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
      <img src="https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Google Gemini"/>
      <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" alt="Qdrant"/>
      <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama"/>
    </td>
  </tr>
  <tr>
    <td><strong>Backend & Databases</strong></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
      <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector"/>
      <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL"/>
    </td>
  </tr>
  <tr>
    <td><strong>Development Tools</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
      <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"/>
    </td>
  </tr>
  <tr>
    <td><strong>Embedded Systems & Robotics</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white" alt="Arduino"/>
      <img src="https://img.shields.io/badge/PID%20Control-2C3E50?style=flat-square" alt="PID Control"/>
      <img src="https://img.shields.io/badge/IR%20Sensors-546E7A?style=flat-square" alt="IR Sensors"/>
      <img src="https://img.shields.io/badge/Bluetooth-0082FC?style=flat-square&logo=bluetooth&logoColor=white" alt="Bluetooth"/>
    </td>
  </tr>
  <tr>
    <td><strong>Technical Design & Diagramming</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Excalidraw-6965DB?style=flat-square&logo=excalidraw&logoColor=white" alt="Excalidraw"/>
      <img src="https://img.shields.io/badge/Eraser-000000?style=flat-square&logo=eraser&logoColor=white" alt="Eraser"/>
      <img src="https://img.shields.io/badge/draw.io-F08705?style=flat-square&logo=diagramsdotnet&logoColor=white" alt="draw.io"/>
    </td>
  </tr>
</table>

---

## Leadership & Community

**Media & Content Lead | Google Developer Groups (GDG) On Campus, Techno Main Salt Lake**

* Progressed from photography and video editing to a leadership role spanning media, design, and content creation.
* Co-managed a 50+ member organizing team alongside the On-Campus Lead.
* Contributed to workshops, speaker sessions, and technical events engaging 100+ students.

---

## 📊 GitHub Statistics

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=AdityaSah2030&show_icons=true&hide_border=true&theme=radical" alt="GitHub Statistics"/>
  <img height="165" src="https://streak-stats.demolab.com?user=AdityaSah2030&theme=radical&hide_border=true&border_radius=8" alt="GitHub Contribution Streak"/>
</p>

---

<p align="center">
  Copyright © 2026 Aditya Kumar Sah. All rights reserved.
</p>
