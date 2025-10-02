# SOMOSPIE Documentation

<img src="./assets/logo_white.png" alt="SOMOSPIE: SOil MOisture SPatial Inference Engine"/>

Welcome to the documentation for the  **SOMOSPIE** Library!

SOil MOisture SPatial Inference Engine (SOMOSPIE) is a data-driven tool designed to improve the representation of soil moisture. It addresses the limitations of remote sensing (i.e., satellites), such as coarse resolution and spatial gaps, through various machine learning algorithms based on meaningful terrain features.

SOMOSPIE supports reproducibility, explainability, and portability of results, contributing to FAIR principles. Its use of containerization and methods usable with publicly available datasets allows users to use and experiment with SOMOSPIE easily.

## 🚀 Quick Start

- [⚙️ Installation](./installation.md): Learn how to install SOMOSPIE for various software environments.
- [📖 Data Guide](./data_guide.md): Learn about what type of data to use and how it should be prepared.
- [🌍 Soil Moisture Prediction](./soil_moisture_predictions.md): Learn about the machine learning methods used to estimate soil moisture at high resolution.
- [✨ Additional Features](additional_features.md): Explore all of the other functionalities of SOMOSPIE. 

## 🧰 Features
- **🛰️  Retrieve/Download Satellite Data** - Fetch coarse-resolution soil moisture datasets from satellites (ESA-CCI). 
- **✂️ Crop to Region of Interest** - Define an area of interest for efficient and localized analysis.
- **🔍 Predict Missing Values and Downscale**: Fill spatial gaps and downscale to a finer resolution with various machine learning algorithms. 
- **📊 Analysis and Visualization**: Generate statistical outputs and visual maps for interpretation and evaluation. 