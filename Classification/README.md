# 📊 Urban Noise Clustering (NYC 311)

### 🎯 Problem Statement

New York City receives thousands of noise complaints daily through the 311 system. These complaints, though rich in behavioral and urban patterns, are currently underutilized. This project aims to identify **natural clusters of nightlife-driven noise activity** in NYC using unsupervised learning.

By clustering spatial and temporal patterns of noise complaints, the city can uncover **hidden nightlife zones**, **emerging hotspots**, and **time-based trends** that could help in zoning regulation, law enforcement, or policy design.

---

### 🧾 Dataset

**Source**: [NYC 311 Service Requests (Open Data)](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9)  
**Subset Used**: Complaints where `Complaint Type = "Noise"`  
**Key Features**:
- `Created Date`
- `Complaint Type`, `Descriptor`
- `Location Type`, `Incident Zip`
- `Latitude`, `Longitude`
- `Borough`

---

### 📌 Objectives

- Perform spatial and temporal feature engineering on complaints.
- Apply clustering (DBSCAN, HDBSCAN, KMeans) to discover natural groupings.
- Analyze and visualize noise activity clusters across NYC.
- Provide actionable insights for city planning and public safety teams.

---

### 🧠 Techniques Used

- Feature Engineering: Hour, weekday/weekend, geo-coordinates
- Clustering: DBSCAN, HDBSCAN, KMeans (for comparison)
- Dimensionality Reduction: t-SNE or PCA
- Visualization: Plotly, Folium (geospatial maps)

---

### 📍 Key Questions

- Where are the densest nightlife-related noise zones in NYC?
- Do noise clusters follow weekday vs. weekend patterns?
- Can we detect areas that are becoming louder over time?

---

### 📎 Outcome

- Cluster profiles with location & time-based characteristics
- Interactive maps showing cluster zones
- Recommendations for proactive city responses
