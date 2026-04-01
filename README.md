![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![Status](https://img.shields.io/badge/Project-Active-success)
![License](https://img.shields.io/badge/License-MIT-green)

# 🚀 AutoMorph — Autonomous Neural Architecture Mutation Agent

Agentic AI system that autonomously designs, trains, and mutates neural network architectures using PyTorch and LangGraph.

---

## 📌 Overview

AutoMorph is an agentic AI system that autonomously designs, trains, evaluates, and mutates neural network architectures with minimal human intervention.

The system monitors real-time training metrics and dynamically modifies model architecture to improve performance over multiple iterations.

This project explores a Neural Architecture Search (NAS)-inspired approach enhanced with LLM-driven or rule-based decision-making.

---

## 🎯 Problem Statement

Designing optimal neural network architectures requires extensive manual experimentation and hyperparameter tuning.

AutoMorph solves this by introducing an intelligent agent loop that:

- Observes model performance (loss, accuracy, overfitting)  
- Reasons about improvements  
- Applies architectural mutations automatically  

---

## 🧠 Key Features

- 🔁 Agent-driven mutation loop  
- 📊 Real-time metric monitoring  
- 🏗️ Dynamic model builder  
- ⚙️ Architecture mutations (layers, activations, dropout, optimizers)  
- 📈 Experiment tracking & visualization  
- 🧪 Benchmarking with accuracy, precision, recall, F1-score  

---

## 🔁 System Architecture

```
Dataset → Model → Training → Metrics → Agent → Mutation → New Model → Repeat
```

---

## ⚙️ Tech Stack

- Python  
- PyTorch  
- Scikit-learn  
- LangGraph  
- LangChain  
- GPT-4o-mini  
- Matplotlib  
- Gradio (optional)  

---

## 🧠 Agent Decision Logic (Example)

```
IF validation_loss increases:
    add dropout

IF accuracy stagnates:
    increase layer depth

IF underfitting detected:
    increase model capacity
```

---

## 📊 Results

(Add your results here)

- Baseline Accuracy: XX%  
- Final Accuracy: XX%  

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python main.py
```

---

## 👩‍💻 Author

Mahek Sorathiya
