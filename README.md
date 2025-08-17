# Weed-Class Project

## Overview
This repository contains the **Weed-4Class classification project**, which aims to classify images of weeds into four classes using various machine learning and deep learning techniques. The dataset also contains a set of negative images (non-weed samples). The project is divided into multiple phases (P1–P4), each using different techniques for feature extraction, classification, and clustering.

---

## Repository Structure
```
Weed-4Class-Project/
├── Weed-4class-43/ # Images for Weed Class 
├── Weed-4class-36/ # Images for Weed Class 
├── Negatives/ # Non-weed images
├── DM_P1.ipynb # Phase 1: ML techniques (Grayscale, Histograms, ORB, PCA)
├── DM_P2.ipynb # Phase 2: Advanced classifiers (Gradient Boost, Perceptron, etc.)
├── DM_P3.pdf   # Phase 3: Deep Learning - Convolutional Neural Network (CNN)
├── DM_P4.pdf   # Phase 4: Unsupervised Learning (Spectral Clustering, K-Means, DBSCAN)
├── DM_P1.pdf # PDF report for Phase 1
├── DM_P2.pdf # PDF report for Phase 2
├── DM_P3.pdf # PDF report for Phase 3
├── DM_P4.pdf # PDF report for Phase 4
├── getting-started-1.py # Helper Python scripts
└── Untitled.ipynb # Miscellaneous experiments
```

markdown
Copy
Edit

---

## Dataset

- **Weed Classes:**  
  - `Weed-4class-36` – Weed Class  
  - `Weed-4class-43` – Weed Class   

- **Negatives:** Non-weed images used to improve classification performance.  

> Each folder contains representative images used for training, testing, and validation.

---

## Project Phases

### Phase 1: Traditional Machine Learning
- **Techniques Used:** Grayscale conversion, Histogram features, ORB (Oriented FAST and Rotated BRIEF), PCA for dimensionality reduction.  
- **Files:** `DM_P1.ipynb`, `DM_P1.pdf`  
- **Goal:** Extract meaningful features and classify weed images using classical ML algorithms.

### Phase 2: Advanced Classification
- **Techniques Used:** Gradient Boosting, Perceptron, and other classical classifiers.  
- **Files:** `DM_P2.ipynb`, `DM_P2.pdf`  
- **Goal:** Improve classification accuracy and generate detailed classification reports.

### Phase 3: Deep Learning
- **Techniques Used:** Convolutional Neural Networks (CNN) for end-to-end image classification.  
- **Files:** `DM_P3.pdf`  
- **Goal:** Use deep learning for higher accuracy on weed classification.

### Phase 4: Unsupervised Learning / Clustering
- **Techniques Used:** Spectral Clustering, K-Means, DBSCAN, and other clustering algorithms.  
- **Files:** `DM_P4.pdf`  
- **Goal:** Explore grouping patterns in weed images without labels.

---

## Installation

To run the notebooks locally, ensure you have Python 3.8+ installed along with the following packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn opencv-python tensorflow keras jupyter
Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/lakshmiravuri544-hash/Weed-Class-Project.git
cd Weed-Class-Project
Open the respective Jupyter Notebook for the phase you want to explore:

bash
Copy
Edit
jupyter notebook DM_P1.ipynb
Follow the notebooks step by step for data preprocessing, feature extraction, model training, evaluation, and visualization.

Sample Images / Results
Weed Class Images

Negatives (Non-weed Images)

License
This project is for educational purposes and research only.

Author
Lakshmi Ravuri
Email: lakshmiravuri544@example.com
GitHub: https://github.com/lakshmiravuri544-hash
