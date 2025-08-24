## Overview
This project implements a **Face Retrieval System** designed for efficient querying in large-scale face datasets. The system combines **Convolutional Neural Networks (CNNs, MobileNet)** for feature extraction with **Locality-Sensitive Hashing (LSH)** to accelerate similarity search. It includes a **Flask backend** and an **Android application** for practical deployment.

## Features
- Extracts facial features using **MobileNet CNN** for high-accuracy representation.
- Employs **Modified LSH** for fast and efficient face retrieval in large datasets.
- Backend server built with **Flask** to manage queries and database interaction.
- **Android application** for capturing and querying face images in real time.

## Dataset
- Evaluated on the **FaceScrub dataset**, containing over **50,000 images** of **530 celebrities**.

## Results
- Achieved a significant improvement in **search speed** while maintaining competitive accuracy.
- Demonstrated effective handling of large-scale image datasets with reduced computational complexity.
- Recognized with a **Consolation Prize** at the Student Scientific Research Contest 2023–2024.

## Applications
- Entertainment (celebrity look-alike finder).
- Security and identity management.
- Large-scale multimedia database search.