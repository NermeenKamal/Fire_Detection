![image](https://github.com/user-attachments/assets/7bd785bd-61f7-450b-a5a2-170e3d2327a4)

# 🔥 Fire Detection Using Classical & Deep Learning Techniques

This project focuses on fire detection using a hybrid approach that combines **classical computer vision methods** and **modern deep learning algorithms**. Implemented in a Jupyter notebook, the goal is to analyze grayscale images and detect fire using multiple techniques.

## 📁 Project Structure

* `CV_Project.ipynb`: Main notebook implementing the complete fire detection pipeline.
* `README.md`: Project description and instructions.

---

## 🚀 Features

### 🔍 Classical Methods

* **Histogram Analysis**
* **Otsu Thresholding**
* **Valley-Emphasis Thresholding**
* **Region Growing Segmentation**

### 📐 Feature-based Methods

* **Harris Corner Detector**
* **HOG (Histogram of Oriented Gradients)**
* **SIFT (Scale-Invariant Feature Transform)**

### 🤖 Deep Learning

* **YOLO (You Only Look Once)** for real-time fire detection (optional or using pretrained models)

---

## 🧠 Goals

* Compare the effectiveness of classical segmentation and feature-based detection against modern object detection (YOLO).
* Evaluate performance on grayscale fire datasets.
* Implement all core methods **from scratch**, especially the classical ones.

---

## ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/fire-detection-cv.git
   cd fire-detection-cv
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:

   ```bash
   jupyter notebook CV_Project.ipynb
   ```

---

## 📊 Dataset

* Fire and Non-Fire images from [Kaggle](https://www.kaggle.com/datasets/phylake1337/fire-dataset) or any custom dataset.
* You can organize images as:

  ```
  /dataset
    /fire
    /non_fire
  ```

---

## 📈 Output

The notebook provides:

* Visualizations of histogram thresholds.
* Region-growing segmented masks.
* Feature point overlays (SIFT, Harris, etc.).
* Bounding boxes for detected fire regions (YOLO).

---

## 🤝 Contributors

* 👤 Nermeen Kamal – Backend, Computer Vision, Integration
* 
---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
