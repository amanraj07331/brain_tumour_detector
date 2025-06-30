# 🧠 Brain Tumor Classification using Deep Learning

This project demonstrates a deep learning approach to **brain tumor detection** using medical images (likely MRI scans). By leveraging the power of **TensorFlow** and **Convolutional Neural Networks (CNNs)**, the model can classify brain tumors with high accuracy.

> ⚕️ Early detection of brain tumors can significantly improve treatment outcomes. This project aims to aid radiologists and medical professionals with AI-assisted diagnosis.

---

## 📁 Project Structure

- **`brain_tumour.ipynb`** – Main Jupyter Notebook with model loading and prediction workflow.
- **Google Colab Drive** – Integration for loading datasets/models from Google Drive.

---

## 🚀 Features

- ✅ Deep learning-based image classification
- ✅ Easy model loading and inference
- ✅ Cloud integration via Google Drive
- ✅ Clean modular notebook design

---

## 🔍 How to Run

1. Clone this repo or open the notebook in Colab:
   ```bash
   git clone https://github.com/amanraj07331/brain-tumour-detection
   ```

2. Install required dependencies:
   ```bash
   pip install tensorflow matplotlib numpy opencv-python
   ```

3. Mount Google Drive (if using Colab):
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```

4. Load the trained model and run inference on test images.

---

## 🧪 Example Results

> ![Brain Tumor Detection Output](https://github.com/amanraj07331/brain_tumour_detector/blob/main/Screenshot%202025-06-30%20235248.png)

---
## Folder Structure
📁 brain-tumour-detection
├── brain_tumour.ipynb
├── output.png
└── README.md


## 🧠 Model Architecture 

- Input: MRI scan image (resized)
- CNN Layers: Convolution → ReLU → MaxPooling
- Dense Layers: Fully Connected → Dropout
- Output: Softmax layer for multi-class classification (e.g., Glioma, Meningioma, Pituitary)

---



## 🤝 Acknowledgements

- Medical datasets used (e.g., Kaggle Brain MRI Dataset)
- Open Source Contributors

---

## 📜 License

This project is licensed under the MIT License. Feel free to use and modify it for research or educational purposes.

---

> Made with ❤️ for advancing medical AI by Aman Raj ([amanraj07331](https://github.com/amanraj07331))
