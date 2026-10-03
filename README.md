# Human Action Detection

## 📌 Overview
This project develops a Computer Vision pipeline to classify human actions from image and video data. It was developed as part of a Machine Learning Internship at 1Stop.ai, focusing on spatial feature extraction and deep learning techniques.

## 📊 Dataset
*   **Source:**  mhealth_raw_data.csv
*   **Description:** A collection of images/videos representing various human actions (e.g., walking, running, jumping).
*   **Preprocessing:** Utilized OpenCV for frame extraction, resizing, and pixel normalization.

## ⚙️ Tech Stack
*   Python
*   OpenCV (Image/Video Processing)
*   TensorFlow / Keras (Deep Learning)
*   NumPy & Pandas
*   Matplotlib (Visualization)

## 🧠 Methodology
1.  **Data Pipeline:** Built a script using OpenCV to extract frames from video data and preprocess images (resizing and normalization) for neural network input.
2.  **Model Architecture:** Implemented a Convolutional Neural Network (CNN) to extract spatial features and classify distinct human actions.
3.  **Training:** Trained the model using categorical cross-entropy loss and optimized using the Adam optimizer.
4.  **Evaluation:** Evaluated model performance using accuracy and confusion matrices to identify misclassifications between similar actions.

## 📈 Results
*   Achieved a validation accuracy of 88%.
*   Successfully built an end-to-end pipeline from raw video frames to action classification.

## 🚀 How to Run
1. Clone this repository:
   `git clone https://github.com/dlalitha0127-maker/human-action-detection.git`
2. Install the required libraries:
   `pip install -r requirements.txt`
3. Run the Python script:
   `python human_action_detection.py`
