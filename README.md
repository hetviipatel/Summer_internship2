# Summer_internship2
# AI/ML Developer Internship – Summer 2025

> **2-month internship** documenting my learning journey (**Weeks 1–4**) and the development of my **Smart Agriculture Assistance Web Portal** with **Crop Disease Detection** (**Weeks 5–8**).

---

## 📑 Table of Contents
- [Overview](#overview)
- [Internship Timeline](#internship-timeline)
  - [Phase 1: Learning (Weeks 1–4)](#phase-1-learning-weeks-1-4)
  - [Phase 2: Project (Weeks 5–8)](#phase-2-project-weeks-5-8)
- [Smart Agriculture Assistance Web Portal](#smart-agriculture-assistance-web-portal)
  - [Key Features](#key-features)
  - [Tech Stack](#tech-stack)
- [Results & Outcomes](#results--outcomes)
- [Future Improvements](#future-improvements)
- [Acknowledgements](#acknowledgements)
- [License](#license)

---

## Overview
This repository showcases my **AI/ML Developer Internship** at **TechMicra**.

- **Weeks 1–4:** Focused on learning the foundations of AI/ML and technologies required for the project.
- **Weeks 5–8:** Developed a production-style **web app** for **plant disease detection**, weather insights, and crop management.

---

## Internship Timeline

### Phase 1: Learning (Weeks 1–4)

#### Week 1 – Python & Programming Foundations
- Installed **Anaconda** and configured **Jupyter/VS Code** environments.
- Learned core Python: variables, data types, loops, conditionals, functions, file I/O.
- Explored data structures: lists, tuples, sets, dictionaries.
- Basics of **Git/GitHub** (clone, branch, commit, PR).

#### Week 2 – Data Handling, EDA & Visualization
- **NumPy:** arrays, broadcasting, vectorized operations.
- **Pandas:** loading CSVs, merging datasets, cleaning data, handling missing values, encoding.
- **Matplotlib**/**Seaborn:** histograms, bar charts, line charts, scatter plots, heatmaps.
- Fundamentals of **EDA** to identify patterns and class balance.

#### Week 3 – Machine Learning & Image Processing
- Learned ML concepts: supervised vs. unsupervised learning, bias/variance, overfitting/underfitting.
- Implemented **Logistic Regression, KNN, Decision Trees, Random Forest** using **scikit-learn**.
- Image preprocessing with **OpenCV**/**Pillow**: resizing, normalization, augmentation.
- Performed train/validation/test splits, evaluated with accuracy, precision, recall, and F1-score.

#### Week 4 – Deep Learning & Flask Basics
- Studied **Neural Networks**: layers, activation functions (ReLU, Sigmoid, Softmax), loss functions, and optimizers.
- Built **CNNs** with Conv2D, MaxPooling, Flatten, Dense layers; applied regularization and augmentation.
- Created an image classifier using **TensorFlow/Keras**.
- Learned **Flask** basics: routing, templates, forms, and integrating ML inference APIs.

---

### Phase 2: Project (Weeks 5–8)

#### Week 5 – Dataset Preparation
- Curated and preprocessed the **PlantVillage** dataset.
- Applied resizing, normalization, and augmentation to improve model performance.

#### Week 6 – Model Development
- Designed a CNN architecture in **Keras** for leaf disease classification.
- Implemented early stopping and checkpointing to save the best model.

#### Week 7 – Model Evaluation & Optimization
- Measured accuracy, precision, recall, and F1-score.
- Performed hyperparameter tuning to improve prediction quality.

#### Week 8 – Web Integration & Final Testing
- Integrated the trained model into **Flask**.
- Built a responsive UI with **Bootstrap** and implemented user authentication.
- Conducted final testing to ensure smooth predictions and fast load times.

---

## Smart Agriculture Assistance Web Portal

A complete web solution for farmers to:
- Detect crop/leaf diseases via an AI model
- View real-time & 7-day **weather** forecasts
- Manage crops, history, and treatment recommendations

---

### Key Features
- 🌿 **Plant Disease Detection**
  - Upload or capture leaf images
  - CNN-based prediction with confidence score
  - Disease information & treatment suggestions
  - Multi-crop support

- 🌤 **Weather Module**
  - Real-time weather & 7-day forecast
  - Agricultural tips based on conditions

- 📊 **Crop Management**
  - Track crops & disease history
  - Generate and export reports

- 🔐 **User System & UI**
  - Register/Login with **Flask-Login**
  - Responsive UI with **Bootstrap 5**

---

### Tech Stack
- **Backend:** Python, Flask, Flask-SQLAlchemy, Flask-Login, Flask-WTF
- **AI/ML:** TensorFlow/Keras, scikit-learn, OpenCV, Pillow, NumPy, Pandas
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5
- **Database:** SQLite
- **Tools:** Git/GitHub, Jupyter Notebook, VS Code

---

## Results & Outcomes
- Delivered a fully functional AI-powered agriculture portal.
- Achieved high prediction accuracy on test data.
- Gained hands-on experience in full-stack AI/ML development.

---

## Future Improvements
- Support more crop and disease categories.
- Implement model explainability with Grad-CAM.
- Deploy to cloud platforms like AWS or Render.
- Create a mobile-friendly PWA version.

---

## Acknowledgements
- **TechMicra** for mentorship and resources.
- **PlantVillage** dataset contributors.
- Open-source community for tools and libraries.

---

## License
This project is licensed under the MIT License.
