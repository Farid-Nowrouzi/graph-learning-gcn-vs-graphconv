# 🌌 Graph Learning on Astrophysical Data: GCN vs GraphConv

This project explores the application of **Graph Neural Networks (GNNs)** on a synthetic astrophysical dataset. It compares two powerful spatial GNN architectures — **Graph Convolutional Networks (GCN)** and **GraphConv** — in a node classification setting designed to simulate celestial graph structures (e.g., galaxies, particles, or astrophysical systems).

The experiment focuses on learning patterns from graph-based data and evaluating how architectural improvements influence accuracy.

---

## 🚀 Project Overview

- 🛰️ Simulates astrophysical graph structures with labeled node features
- ⚙️ Applies two GNN models:  
  - `GCN`: classic Graph Convolutional Network  
  - `GraphConv`: more expressive, with skip connections
- 🎯 Task: Classify each graph based on its structural and node features
- 📊 Objective: Evaluate model performance and generalization under identical training conditions

---

## 🧠 Key Insights

- The notebook demonstrates **graph-level classification** using global pooling and 3-layer message-passing networks.
- `GCN` reaches ~55% test accuracy under the current setup.
- `GraphConv` is introduced as an architectural upgrade to potentially mitigate over-smoothing and improve performance.

---

## 🛠️ Technologies Used

- Python 3.x
- PyTorch & PyTorch Geometric
- NetworkX
- Matplotlib
- Jupyter Notebook

---

## 📁 Recommended Folder Structure

Graph_Learning_GCN_GraphConv/
├── graph_learning_gcn_vs_graphconv.ipynb # Main notebook
├── README.md # Project documentation
├── data/ # (Optional) Graph data files
├── images/ # (Optional) Graph visualizations
├── .gitignore # (Optional) Cleanup rules
└── LICENSE # (Optional) License for open use




---

## 📚 Contents of the Notebook

1. **Data Loading**  
   - Loads synthetic graph dataset inspired by molecular/astrophysical networks.

2. **Model #1 – GCN**  
   - A 3-layer Graph Convolutional Network  
   - Uses `global_mean_pool` for graph embedding  
   - Reaches ~55% test accuracy

3. **Model #2 – GraphConv**  
   - Incorporates skip connections  
   - Uses the same pipeline to allow a fair comparison  
   - Intended to preserve node-level info and reduce over-smoothing

4. **Evaluation**  
   - Accuracy metrics on both training and test sets  
   - Direct model comparison between `GCN` and `GraphConv`

---

## 🎯 Motivation

This project is part of a growing portfolio focused on applying **machine learning to space-inspired and graph-structured data**. It reflects my interest in leveraging deep learning models like GNNs for real-world astrophysics, astronomy, and future space research.

---

## 👤 Author

**Farid Nowrouzi**  
Aspiring AI researcher with a focus on Graph Neural Networks, Astrophysics, and intelligent space systems.

---

## 📘 License

This project is open-source under the MIT License.
