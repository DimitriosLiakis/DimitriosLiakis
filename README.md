<h1 align="center">Hi, I'm Dimitrios Liakis 👋</h1>

<p align="center">
  Electrical &amp; Computer Engineer (NTUA) · Deep learning for medical image analysis · Computer vision
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/dimitris-liakis-303886277/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:dimliakis2001@gmail.com"><img src="https://img.shields.io/badge/Email-D14836" alt="Email"/></a>
</p>

---

### About me

I'm an Electrical & Computer Engineering graduate (Diploma, integrated MEng) from the
**National Technical University of Athens (NTUA)**, specializing in deep learning for medical image analysis.
For my thesis, I built and evaluated a semi-supervised 3D segmentation pipeline for pancreas CT. It compares a
Mamba (State Space Model) backbone with a 3D U-Net and runs end to end on a single free GPU.

I'm looking for **AI/ML engineering roles**, especially in **medical imaging and computer vision**, based in
Greece or remote, and I'm available to start now. Fluent in English (C2).

Outside engineering, I'm a trained Byzantine and classical singer, which is where I get my patience for detail.

### Featured project: diploma thesis

**[Mamba vs. 3D U-Net for semi-supervised pancreas segmentation](https://github.com/DimitriosLiakis/mamba-vs-unet3d-pancreas-ct)**

- Integrated a 2D Mamba U-Net (Swin-UMamba) into DyCON (CVPR 2025), a semi-supervised mean-teacher framework
  for 3D CT, and compared it with a 3D U-Net.
- Trained everything on one free 16 GB GPU, using:
  - 64³ patches and gradient accumulation;
  - chunked slice-wise processing;
  - full-state checkpoints to resume across time-limited sessions.
- Found that a parameter-free post-processing step, largest connected component, gave the largest single
  improvement. It halved Swin-UMamba's HD95 and cut the 3D U-Net's surface distance from 21.6 to 2.2 voxels.
- A code review after submission found two issues inherited from the upstream code: evaluation scans that overlap
  the training list, and ground-truth masks of "unlabeled" scans leaking into the contrastive loss. The
  repository documents both and evaluates on held-out scans by default.

### Other projects

- **[Toll Interoperability Platform](https://github.com/DimitriosLiakis/toll-interoperability-platform)**: a
  full-stack platform for highway toll operators (team project, Software Engineering 2024–25). I built the React
  front-end: the station map (Leaflet), the statistics dashboard, debt settlement and the UI for the ML traffic
  forecasts.
- **[clearSKY](https://github.com/DimitriosLiakis/clearsky-grading-saas)**: a microservices SaaS for university
  grades (team project, SaaS 2025). I built most of the Express/EJS front-end, the grade charts (ECharts) and its
  Docker setup, plus the endpoints it needs in the Go orchestrator.
- **[Pulse Festival Database](https://github.com/DimitriosLiakis/pulse-festival-database)**: a MySQL database for
  a music festival with triggers, 15 analytical queries and query optimization (individual project, Databases
  2024–25).
- **[MediaLab Assistant](https://github.com/DimitriosLiakis/medialab-task-manager)**: a JavaFX desktop task manager
  with priorities, deadlines, reminders and JSON persistence (individual project, Multimedia Technology 2024–25).
- **[Chordify](https://github.com/klarinetos/chordify)**: the Chord distributed hash table with configurable
  replication and two consistency models (team project, Distributed Systems).

### What I work with

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![MONAI](https://img.shields.io/badge/MONAI-00A3E0)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?logo=kaggle&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)

Deep learning · 3D medical image segmentation (CT) · semi-supervised and contrastive learning ·
State Space Models (Mamba) · training under tight GPU budgets · model evaluation
