# Intrusion Detection Using Self-Supervised Learning

## Overview
This repository contains the implementation of my MSc thesis on **Intrusion Detection** using **Self-Supervised Learning**. The objective of this research is to develop a robust and efficient intrusion detection system (IDS) that leverages self-supervised learning techniques to detect malicious activities in network traffic.

## Motivation
With the increasing complexity of cyber threats, traditional supervised learning-based IDS systems face challenges such as:
- Dependence on labeled data
- High false positive rates
- Limited adaptability to emerging threats

Self-supervised learning (SSL) offers a promising solution by learning meaningful representations from unlabeled data, making it more suitable for real-world intrusion detection.

## Methodology
The research follows these key steps:
1. **Data Collection & Preprocessing**: Gathering and cleaning network traffic datasets (e.g., CICIDS, UNSW-NB15, KDD99, etc.).
2. **Self-Supervised Pretraining**: Leveraging SSL techniques such as contrastive learning, masked autoencoders, or clustering-based methods.
3. **Fine-Tuning for Intrusion Detection**: Using labeled data to train a downstream classifier for anomaly detection.
4. **Evaluation**: Measuring the performance using metrics like accuracy, F1-score, precision, recall, and ROC-AUC.

## Dataset
The research will utilize well-known intrusion detection datasets such as:
- [CICIDS 2017](https://www.unb.ca/cic/datasets/ids-2017.html)
- [UNSW-NB15](https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/)
- [KDD CUP 1999](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)

## Technologies Used
- **Programming Language**: Python
- **Deep Learning Frameworks**: PyTorch / TensorFlow
- **Libraries**: Scikit-learn, NumPy, Pandas, Matplotlib, Seaborn
