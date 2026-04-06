# Deep_Learning-Defect-prediction-framework-using-CodeBERT-and-GAT

# 🚀 GNNLineDef-XAI  
**AI-Based Line-Level Defect Prediction using Hybrid GNN with Explainability**

---

## 📌 Overview

GNNLineDef-XAI is a hybrid deep learning framework designed for **fine-grained line-level defect prediction** in large-scale Python codebases.  

Unlike traditional file-level defect prediction approaches, this model identifies **defect-prone lines of code**, enabling developers to focus on the most suspicious regions during code review.

The framework integrates **semantic, sequential, and structural learning**, along with **explainable AI (XAI)** to provide interpretable insights into predictions.

---

## 🎯 Key Features

- 🔍 **Line-Level Defect Prediction**
- 🧠 **Hybrid Architecture**
  - CodeBERT → Semantic representation  
  - BiLSTM → Sequential context  
  - RGAT → Structural relationships (AST, CFG, PDG)
- 📊 **Ranking-Based Evaluation**
  - 78% Recall@20% LOC  
  - 1% Effort@20%  
  - 0.00 IFA (Initial False Alarms)
- 🔎 **Explainability Integration**
  - Graph-based explanations (GNNExplainer)  
  - Feature-based explanations (LIME)
- ⚡ **Designed for Large-Scale Python Projects in Modern Software Enterprices**

---

## 🏗️ Model Architecture
