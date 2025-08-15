# 😷 Face Mask Detection using CNN

This project is a machine learning application that detects whether a person in an image is wearing a face mask or not. It uses a **Convolutional Neural Network (CNN)** built with **TensorFlow** and **Keras** for image classification.

### ✨ Key Features
* **Image Classification:** Accurately classifies images into two categories: `with_mask` and `without_mask`.
* **CNN Model:** Leverages a custom-built CNN architecture for robust feature extraction from images.
* **Data Preprocessing:** Includes steps for resizing, normalizing, and converting images to NumPy arrays.
* **Model Evaluation:** Provides performance metrics like **accuracy and loss** on a separate test dataset.
* **Predictive System:** A functional system that can take a new image as input and make a real-time prediction.

### 💻 Tech Stack
* **Frameworks:** TensorFlow, Keras
* **Libraries:** NumPy, Matplotlib, OpenCV (`cv2`)
* **Environment:** Google Colab (with GPU acceleration)

### 🚀 Getting Started
To run this project, you will need to set up the environment and acquire the dataset. The project code is designed to run in a Google Colab environment.

1.  **Open the Notebook:** Open the project notebook in Google Colab.
2.  **Enable GPU:** Go to `Runtime > Change runtime type` and select `GPU` as the hardware accelerator.
3.  **Download Dataset:** The project uses a Kaggle dataset. You'll need a Kaggle account and API token (`kaggle.json`) to download the data directly into your Colab environment.

### 📈 Model Performance
The trained model achieved a high level of accuracy, demonstrating its effectiveness in distinguishing between masked and unmasked faces.

* **Training Accuracy:** ~93%
* **Test Accuracy:** ~92%

---

Made with ❤️ Thrishi
