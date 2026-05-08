# 🔷 Deep Archetypal Analysis

> *Extending classical Archetypal Analysis into non-linear latent spaces using deep generative models.*

---

## 📖 Overview

Classical **Archetypal Analysis (AA)** describes every data point as a convex combination of extreme "pure types" — the archetypes — which sit at the boundary of the data convex hull. It is an inherently interpretable dimensionality reduction method, but is limited to linear feature spaces.

This project implements and explores **Deep Archetypal Analysis (DeepAA)**: integrating the archetype model into the latent space of a **Variational Autoencoder (VAE)**, enabling non-linear, generative archetypal decomposition that scales to complex high-dimensional data such as images.

---

## 🔬 Key Concepts

- **Archetypes** — extreme, interpretable prototypes that span the latent convex hull; every data point is a mixture of these
- **Variational Autoencoder** — encoder-decoder architecture that learns a structured probabilistic latent space
- **Archetype Loss** — distance-dependent loss that drives latent representations toward a convex archetypal structure
- **Convex Mixing** — latent codes are constrained to be convex combinations of learned archetypes via softmax-constrained weight matrices

---

## 🛠️ Stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

**Key libraries:** `torch` · `numpy` · `matplotlib` · `scikit-learn` · `scipy`

---


## 📚 Context

Developed as a project for **02456 – Deep Learning** at DTU – Technical University of Denmark (Autumn 2025).

---

## 👤 Author

**João Mata** and Manuel Charneca.
