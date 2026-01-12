# Plant Disease Detection System 🌿

### Project Overview
This is a Deep Learning-based mini project aimed at helping farmers identify plant diseases early. By using Computer Vision, the system analyzes images of leaves to detect infections that are often missed by the naked eye.

---

### 📋 Key Features
* **Automated Diagnosis:** Instant detection of diseases using image processing.
* **Deep Learning Model:** Built using **CNN (Convolutional Neural Networks)** for high accuracy.
* **User-Friendly Interface:** Simple image upload feature for non-technical users.
* **Real-time Results:** Provides the disease name along with a confidence percentage.

### 🛠️ Tech Stack
* **Language:** Python
* **Deep Learning:** TensorFlow / Keras
* **Libraries:** OpenCV (for image processing), NumPy, Pandas
* **Web Framework:** Streamlit (or Flask/Django)

### 📊 Dataset
The model was trained on the **PlantVillage Dataset**, which contains thousands of images of healthy and diseased leaves across various species like Tomato, Potato, and Pepper.



### 🚀 How It Works
1. **Upload:** User uploads a clear image of a plant leaf.
2. **Pre-processing:** The system resizes and normalizes the image to $224 \times 224$ pixels.
3. **Prediction:** The CNN model extracts features and classifies the disease.
4. **Output:** The UI displays the detected disease name and treatment suggestions.

### 🎯 Future Scope
* Adding a "Treatment Suggestion" feature for each detected disease.
* Deploying the model as a mobile application for field use.
