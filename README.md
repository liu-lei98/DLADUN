# 🎯 Degradation Learning Adaptive Deep Unfolding Network for Spectral Compressive Imaging (DLADUN))

<div align="center">

<!-- [![Paper Status](https://img.shields.io/badge/Paper-Published%20in%20IEEE%20TMM-success?style=for-the-badge)](https://ieeexplore.ieee.org/document/10214675)-->
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge)](LICENSE)
<!-- [![GitHub stars](https://img.shields.io/github/stars/liu-lei98/DADFNet?style=for-the-badge)](https://github.com/liu-lei98/DADFNet)-->

</div>

## 📌 Overview
This repository contains the official PyTorch implementation of our paper:

**"Degradation Learning Adaptive Deep Unfolding Network for Spectral Compressive Imaging"**

**more details will be released after the journal's publication.**

## 🏗️ Network Architecture
<div align="center">
  <img src="https://github.com/liu-lei98/DLADUN/blob/main/Figures/overall.png"   alt="">
  <p><em>Figure 1: The overall architecture of DLADUN </em></p>
  <img src="https://github.com/liu-lei98/DLADUN/blob/main/Figures/subfigure.png" alt="">
  <p><em>Figure 2: The overall architecture of sub-models </em></p>
  <img src="https://github.com/liu-lei98/DLADUN/blob/main/Figures/ZOOM_SIM_5.png"  alt="">
  <p><em>Figure 3: The Visual Comparison </em></p>
  <img src="https://github.com/liu-lei98/DLADUN/blob/main/Figures/ZOOM_SIM_8.png"  alt="">
  <p><em>Figure 3: The Visual Comparison </em></p>
  <img src="https://github.com/liu-lei98/DLADUN/blob/main/Figures/ZOOM-REAL-1.png"  alt="">
  <p><em>Figure 3: The Visual Comparison </em></p>
  <img src="https://github.com/liu-lei98/DLADUN/blob/main/Figures/ZOOM-REAL-4.png"  alt="">
  <p><em>Figure 3: The Visual Comparison </em></p>
</div>

## 🚀 Quick Start

### Prerequisites
- Linux or macOS
- NVIDIA GPU + CUDA cuDNN
- Python 3.8+
- PyTorch 1.10+

### Installation

# Create and activate conda environment
- conda create -n DLADUN python=3.8
- conda activate DLADUN

# Install dependencies
- pip install -r requirements.txt

### Experiement

>- Following TSA-Net and DGSMP, we use the CAVE dataset (cave_1024_28) as the simulation training set. Both the CAVE (CAVE_512_28) and KAIST (KAIST_CVPR2021) datasets are used as the real training set.
>- Training for Simulation: python train.py
>- Training for Real: python train_real.py
>- Testing for Simulation: python test.py
>- Result:[Baidu Disk](https://pan.baidu.com/s/q27j1oLF10q3ghTuFu1p-4R9bDA?pwd=)
