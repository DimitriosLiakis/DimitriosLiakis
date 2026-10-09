<h1 align="center">Hi, I'm Dimitrios Liakis 👋</h1>

<p align="center">
  Electrical &amp; Computer Engineer (NTUA) · AI/ML engineering · Medical image analysis
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/dimitris-liakis-303886277/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:el20846@mail.ntua.gr"><img src="https://img.shields.io/badge/Email-D14836" alt="Email"/></a>
</p>

---

### About me

I recently completed my Diploma (integrated MEng) in Electrical & Computer Engineering at the
**National Technical University of Athens (NTUA)**. For my thesis I built and evaluated a semi-supervised
3D segmentation pipeline for pancreas CT. It compares a Mamba (State Space Model) backbone with a 3D U-Net and
runs end to end on a single free GPU.

I'm looking for **junior AI/ML engineering roles**, especially in **medical imaging and healthcare AI**,
starting in summer 2027.

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
- A post-submission audit found two issues inherited from the upstream code: evaluation scans that overlap
  the training list, and ground-truth masks of "unlabeled" scans leaking into the contrastive loss. The
  repository documents both and evaluates on held-out scans by default.

### What I work with

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![MONAI](https://img.shields.io/badge/MONAI-00A3E0)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?logo=kaggle&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)

Deep learning · 3D medical image segmentation (CT) · semi-supervised and contrastive learning ·
State Space Models (Mamba) · training under tight GPU budgets · model evaluation
