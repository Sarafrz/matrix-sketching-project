# Matrix Monitoring, Sketching & Mining (UCI Online Retail Dataset)

This repository contains all code, data, and results for my project on **Matrix Monitoring**, **Matrix Sketching**, and **Matrix Mining** using the UCI *Online Retail* dataset.  
It’s designed to show how large transactional data can be compressed, monitored, and analyzed for structure, anomalies, and frequent patterns — all in a streaming (batch-by-batch) setup.

---

## 🧠 Project Summary

The goal of this project is to simulate a real-world **data stream** and explore how matrix sketching algorithms like  
**Frequent Directions (FD)**, **Incremental PCA (IPCA)**, and **Gaussian Random Projection (GRP)**  
can efficiently monitor and compress data without losing its essential structure.

Later stages also explore:
- How these algorithms behave over time (stability & reconstruction quality)
- How well they detect **anomalies**
- How much structural information (like **frequent item patterns**) is preserved after compression.