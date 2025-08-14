# Summer_internship2
# AI/ML Developer Internship – Summer 2025
> 2-month internship documenting my learning journey (Weeks 1–4) and the development of my **Smart Agriculture Assistance Web Portal** with **Crop Disease Detection** (Weeks 5–8).

---

## 📑 Table of Contents
- [Overview](#overview)
- [Internship Timeline](#internship-timeline)
  - [Phase 1: Learning (Weeks 1–4)](#phase-1-learning-weeks-1–4)
  - [Phase 2: Project (Weeks 5–8)](#phase-2-project-weeks-5–8)
- [Smart Agriculture Assistance Web Portal](#smart-agriculture-assistance-web-portal)
  - [Key Features](#key-features)
  - [Tech Stack](#tech-stack)
  - [Project Structure](#project-structure)
  - [Setup & Run](#setup--run)
  - [Model Training (Optional)](#model-training-optional)
  - [Usage](#usage)
- [Results & Outcomes](#results--outcomes)
- [Future Improvements](#future-improvements)
- [Acknowledgements](#acknowledgements)
- [License](#license)

---

## Overview
This repository showcases my **AI/ML Developer** internship at **TechMicra**.  
- **Weeks 1–4:** I focused on learning the foundations required for AI/ML and this project.  
- **Weeks 5–8:** I built a production-style web app for **plant disease detection**, weather insights, and crop management.

---

## Internship Timeline

### Phase 1: Learning (Weeks 1–4)

#### Week 1 — Python & Programming Foundations
- Installed **Anaconda** and configured **Jupyter/VS Code** environments.
- Core Python: variables, data types, loops, conditionals, functions, file I/O.
- Data structures: lists, tuples, sets, dictionaries.
- Basics of **Git/GitHub** (clone, branch, commit, PR).

#### Week 2 — Data Handling, EDA & Visualization
- **NumPy**: arrays, broadcasting, vectorized ops.
- **Pandas**: loading CSVs, merging, cleaning, missing values, encoding.
- **Matplotlib**/**Seaborn**: histograms, bar/line charts, scatter, heatmaps.
- Fundamentals of **EDA** for discovering class balance & patterns.

#### Week 3 — Machine Learning & Image Processing
- ML concepts: supervised vs. unsupervised, bias/variance, over/underfitting.
- Implemented **Logistic Regression, KNN, Decision Trees, Random Forest** with **scikit-learn**.
- Image preprocessing with **OpenCV**/**Pillow**: resizing, normalization, augmentation.
- Train/validation/test splits, metrics (accuracy, precision, recall, F1).

#### Week 4 — Deep Learning & Flask Basics
- **Neural Networks**: layers, activations (ReLU, Sigmoid, Softmax), loss & optimizers.
- **CNNs**: Conv2D, MaxPooling, Flatten, Dense; regularization & augmentation.
- Built an image classifier with **TensorFlow/Keras**.
- **Flask** basics: routing, templates, forms, integrating ML inference APIs.

---

### Phase 2: Project (Weeks 5–8)

- **Week 5:** Dataset curation & preprocessing (resize, normalize, augment).
- Curated and preprocessed a PlantVillage dataset.
- Applied resizing, normalization, and augmentation to improve model performance.
- **Week 6:** CNN architecture design & training with Keras; early stopping/checkpointing.
- Built a CNN architecture with Keras for leaf disease classification.
- Used early stopping and checkpointing to save the best model.
- **Week 7:** Evaluation & optimization; confusion matrix, hyperparameter tuning.
- Measured accuracy, precision, recall, and F1-score.
- Tuned hyperparameters to improve prediction quality.
- **Week 8:** Flask integration, UI with Bootstrap, authentication, final testing & docs.
- Integrated the trained model into Flask.
- Created a responsive UI with Bootstrap and implemented user authentication.
- Conducted final testing, ensuring smooth predictions and fast loading times.

---

## Smart Agriculture Assistance Web Portal

A complete web solution for farmers to:
- Detect crop/leaf diseases via an AI model,
- View real-time & 7-day **weather** forecasts,
- Manage crops, history, and treatment recommendations.


### Key Features
- 🌿 **Plant Disease Detection**
  - Upload or camera capture of leaf images
  - CNN-based prediction with confidence score
  - Disease info & treatment suggestions
  - Multi-crop support

- 🌤 **Weather Module**
  - Real-time weather & 7-day forecast
  - Agriculture tips based on conditions

- 📊 **Crop Management**
  - Track crops & disease history
  - Reports (export/share)

- 🔐 **User System & UI**
  - Register/Login (Flask-Login)
  - Responsive UI (Bootstrap 5)

### Tech Stack
- **Backend:** Python, Flask, Flask-SQLAlchemy, Flask-Login, Flask-WTF
- **AI/ML:** TensorFlow/Keras, scikit-learn, OpenCV, Pillow, NumPy, Pandas
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5
- **Database:** SQLite
- **Tools:** Git/GitHub, Jupyter/VS Code
