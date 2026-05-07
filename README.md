# AI Threat Hunter

A security-focused AI system designed to analyze network traffic and detect advanced cyber threats using behavioral analytics and machine learning.

---

## 🎯 Objective
Simulate a real-world SOC tool that identifies:
- Data exfiltration patterns
- Command & Control (C2) communication
- Malware behavior anomalies
- Suspicious network flows

---

## 🧩 Architecture

Core pipeline:

1. Packet ingestion (PCAP / live traffic)
2. Feature extraction
3. ML anomaly detection
4. Behavioral analysis engine
5. Threat scoring + classification
6. MITRE ATT&CK mapping layer

---

## ⚙️ Features

- ML-based anomaly detection engine
- Behavioral fingerprinting of network sessions
- Graph-based traffic relationship analysis
- Rule + AI hybrid detection model
- MITRE ATT&CK technique tagging

---

## 🛠 Tech Stack

- Python
- Scapy
- Scikit-learn
- NetworkX
- TensorFlow / PyTorch (optional layer)

---

## ▶️ Usage

```bash
python main.py examples/sample.pcap
