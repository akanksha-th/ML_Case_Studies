# 🔐 Unsupervised Intrusion Detection in Network Traffic (IoT Focus)

### 🎯 Problem Statement

With the explosion of IoT devices and smart infrastructure, traditional rule-based intrusion detection systems often fail to catch novel or subtle attacks. This project aims to build an **unsupervised anomaly detection system** that can cluster and flag **network behavior deviating from normal activity**—even when attack types are unknown.

The system focuses on **learning the normal patterns** of IoT network traffic and using clustering to detect **suspicious deviations** that may represent intrusions.

---

### 🧾 Dataset

**Source**: [TON_IoT Network Datasets](https://research.unsw.edu.au/projects/toniot-datasets)  
**Used Subset**: Network traffic features for IoT devices

**Features Include**:
- Packet-based stats (bytes in/out, protocols, flags)
- Device-level logs
- Time-based features (timestamp, durations)

---

### 📌 Objectives

- Preprocess and normalize raw network traffic data
- Apply unsupervised learning (e.g., k-Means, DBSCAN, Autoencoder Embeddings)
- Identify anomalies/clusters of unusual activity
- Compare clustering labels to known attack labels (for evaluation only)

---

### 🧠 Techniques Used

- Dimensionality Reduction: PCA, Autoencoders
- Clustering: k-Means, DBSCAN, Isolation Forest
- Anomaly Detection: Mahalanobis distance, One-Class SVM
- Evaluation: Confusion Matrix, ROC-AUC (against known attacks)

---

### 📍 Key Questions

- Can we detect attacks without labeled training data?
- Which features are most important in distinguishing normal vs. abnormal traffic?
- How do unsupervised methods compare in real-world detection?

---

### 📎 Outcome

- A lightweight, interpretable intrusion detection prototype
- Performance metrics on unseen attack types
- Insights into real-time anomaly detection for IoT networks
