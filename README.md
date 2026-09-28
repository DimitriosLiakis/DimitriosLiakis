<h1 align="center">Hi, I'm Dimitrios Liakis 👋</h1>

<p align="center">
  Electrical &amp; Computer Engineer (NTUA) · Machine learning for medical imaging
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/dimitris-liakis-303886277/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:el20846@mail.ntua.gr"><img src="https://img.shields.io/badge/Email-D14836" alt="Email"/></a>
</p>

---

### About me

I recently completed my Diploma (integrated MEng) in Electrical & Computer Engineering at the
**National Technical University of Athens (NTUA)**. My thesis studied **semi-supervised 3D
medical image segmentation**: State Space Models (Mamba) versus CNNs, uncertainty-aware training
with very few labels, and post-processing, all on a single free Kaggle GPU.

I'm looking for **junior Machine Learning / Computer Vision roles**, starting in summer 2027.

### Featured project: diploma thesis

**[Swin-UMamba vs. 3D U-Net for semi-supervised pancreas segmentation](https://github.com/DimitriosLiakis/swin-umamba-dycon-lcc)**

- Compared a Mamba-based backbone (Swin-UMamba) with a 3D U-Net on pancreas CT, both trained with
  the DyCON semi-supervised framework (CVPR 2025).
- With only **12 labeled scans**, 3D U-Net + DyCON + LCC reaches **71.1% Dice**, on par with 71.9% for full
  supervision on 62 scans.
- Showed that largest-connected-component post-processing is the biggest single lever for boundary
  accuracy: it halved Swin-UMamba's HD95.
- Fit 3D training on one Kaggle GPU with mixed precision, gradient accumulation and chunked
  slice-wise processing.

### Tech

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![MONAI](https://img.shields.io/badge/MONAI-00A3E0)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?logo=kaggle&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)

Deep learning · 3D medical image segmentation · semi-supervised & contrastive learning ·
State Space Models (Mamba)
