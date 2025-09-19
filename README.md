# IoT Intrusion Detection Repository

This repository contains a reproducible pipeline for building and testing lightweight intrusion detection models on IoT traffic data. It is designed for researchers and practitioners who want to experiment with feature selection, model compression, and deployment on resource-limited devices.

---

## What’s Inside

- **notebooks/**: A Jupyter notebook with end-to-end code for preprocessing, training, and evaluation.  
- **LICENSE**: Open-source license (MIT by default).  
- **README.md**: Documentation and usage instructions.  

---

## Key Features

- Data preprocessing with numeric standardization and categorical encoding.  
- Ranking and pruning of features using SHAP values.  
- Training a larger "teacher" network for supervision.  
- Building a compact "student" network with Kronecker-structured layers.  
- Transferring knowledge from teacher to student for higher accuracy.  
- Optional quantization to reduce memory and latency for edge deployment.  

---

## Dataset

The experiments use the **TON_IoT dataset**, which contains IoT network traffic with multiple attack categories.  
- Dataset link: [ToN-IoT official page](https://research.unsw.edu.au/projects/toniot-datasets)  
- The notebook includes preprocessing steps to prepare the dataset.  

---
