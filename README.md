## ⚙️ Environment Setup

- 🧠 **InternVL**, **LLaVA-Next-7B**, and **Video-LLaVA-7B**  
  → Use **`env1.yaml`** to replicate the target conda environment.

- 🦉 **mPLUG-Owl3-7B**  
  → Use **`env2.yaml`**, as it requires a specific version of the `transformers` package.

---

## 🎯 Project Overview

This repository is built to **evaluate the reasoning and grounding capabilities** of  
**Video-Language Models (VLMs)**.  

- 📏 Focus: **Moderate-sized models (< 10B parameters)**  
- 🎬 Domain: **Video-based understanding and reasoning**  
- ⚡ Goal: Benchmark **grounded reasoning** performance efficiently

---

## 📂 Repository Structure

Each model’s directory contains:
- 🧩 Original scripts from the respective source repositories  
- 🔧 **Modified and optimized versions** tailored to our evaluation setup  
- 📓 Jupyter notebooks for testing and visualization

---

## 🚀 Quick Note

Ensure that you activate the correct conda environment before running any notebook:  

```bash
conda env create -f env1.yaml   # For InternVL / LLaVA-Next / Video-LLaVA
conda env create -f env2.yaml   # For mPLUG-Owl3
