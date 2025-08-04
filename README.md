# Truth-vs-Hype

## 🔍 Project Overview

**Truth‑vs‑Hype** is a comprehensive repository exploring the gap between media scrutiny and public perception. It helps readers identify factual reporting versus exaggerated narratives across trending topics.

This repository includes:

- A curated collection of news articles, sources, and fact‑checks  
- Python scripts and utility tools for analyzing sentiment, bias, and misinformation patterns  
- Sample datasets and visualization dashboards  

## ⚙️ Features

- **Media Analysis Toolkit** – Fetch and evaluate articles with support for automated sentiment and credibility scoring  
- **Interactive Dashboards** – Visualize coverage vs. verified facts  
- **Bias Classifier** – Pre‑trained model to detect sensational storytelling  

## 📁 Repository Structure

Truth-vs-Hype/
├── data/ # Sample news datasets, fact-check collections
├── notebooks/ # Jupyter notebooks illustrating workflows and tests
├── scripts/ # Python tools and preprocessing utilities
├── dashboard/ # Visualization setup (e.g. Dash, Streamlit)
├── models/ # Trained bias classifier, embeddings
├── LICENSE
└── README.md


## 🚀 Getting Started

### Prerequisites

You'll need:
- Python 3.9+  
- pipenv or virtualenv (recommended)  

### Installation

```bash
git clone https://github.com/sanket-srivastwa/Truth-vs-Hype.git
cd Truth-vs-Hype
python -m venv venv
source venv/bin/activate       # (macOS/Linux)
venv\Scripts\activate          # (Windows)
pip install -r requirements.txt

### **Run a script to analyze articles:**
python scripts/analyze_article.py --url "<article URL>"

### **Launch dashboards:**
streamlit run dashboard/main.py
