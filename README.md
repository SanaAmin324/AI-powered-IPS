# AI-Powered Network Intrusion Prevention System

## Overview

This project implements a machine learning-based Network Intrusion Prevention System (AI-IPS) that analyzes network traffic, identifies potentially malicious activities, and initiates preventive responses.

The system combines machine learning-based traffic classification with a policy-driven threat decision engine, simulated IP blocking, security event logging, and an interactive monitoring dashboard.

## Objectives

- Analyze network traffic using machine learning.
- Classify traffic as benign or malicious.
- Identify selected network attack categories.
- Evaluate threats using configurable security policies.
- Simulate prevention through an application-level IP blocklist.
- Record security events and prevention actions.
- Visualize detection results through an interactive dashboard.

## Technologies

- Python
- Pandas and NumPy
- Scikit-learn
- Jupyter Notebook
- Matplotlib and Seaborn
- Streamlit
- Joblib

## Dataset

The project uses the CIC-IDS2017 dataset published by the Canadian Institute for Cybersecurity.

Dataset: https://www.unb.ca/cic/datasets/ids-2017.html

The dataset files are not included in this repository due to their size.

See dataset/README.md for dataset instructions.

## Project Structure

`	ext
AI-powered-IPS/
|-- dataset/
|-- notebooks/
|-- models/
|-- src/
|-- dashboard/
|-- logs/
|-- tests/
|-- docs/
|-- requirements.txt
|-- .gitignore
|-- README.md


