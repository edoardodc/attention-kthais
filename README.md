# 🧠 Attention KTH-AIS — Visualization and Understanding of the Attention Mechanism

This repository contains a hands-on exploration of the **Transformer attention mechanism**, inspired by the original paper ["Attention is All You Need"](https://arxiv.org/abs/1706.03762) and implemented using **PyTorch**.  
It was developed as part of a project for the **KTH AI Society** to visualize and explain how the attention layers (K, Q, V matrices) work inside Transformer models.

---

## 📘 Project Overview

The goal of this notebook is to:
- Explain the role and interaction of **Key (K)**, **Query (Q)**, and **Value (V)** matrices in attention.
- Visualize attention patterns using **BERTViz** and **PyTorch**.
- Demonstrate how different words attend to each other in a sentence.
- Provide a clear, visual, and intuitive understanding of how Transformer models process context.

---

## 🚀 Launch the Notebook Online

You can **run this notebook interactively** without installing anything locally thanks to [Binder](https://mybinder.org):

👉 **[Open in Binder](https://mybinder.org/v2/gh/edoardodc/attention-kthais/HEAD?labpath=attention-kthais.ipynb)**

> Binder will automatically install all dependencies and open the notebook in JupyterLab.

---

## 🧩 Installation (optional, local setup)

If you prefer running it locally:

```bash
# 1️⃣ Clone the repository
git clone https://github.com/edoardodc/attention-kthais.git
cd attention-kthais

# 2️⃣ Create a virtual environment
python -m venv venv
source venv/bin/activate  # (Windows: venv\Scripts\activate)

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Launch Jupyter Notebook
jupyter notebook attention-kthais.ipynb
```
