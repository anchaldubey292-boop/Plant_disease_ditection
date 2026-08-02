# 🌿 Plant Disease Detection System using Deep Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=for-the-badge&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red?style=for-the-badge&logo=keras)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-FF4B4B?style=for-the-badge&logo=streamlit)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv)
![License](https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge)

---

## 📌 Overview

The **Plant Disease Detection System** is a Deep Learning-based web application that identifies diseases in plant leaves from images. The system helps farmers, researchers, and agricultural professionals detect diseases at an early stage, reducing crop losses and improving sustainable farming practices.

The project is built using **TensorFlow/Keras** for model training and **Streamlit** for an interactive web interface.

---

## 🚀 Features

- 🌱 Detects diseases from plant leaf images
- 🍃 Supports **38 Plant Disease Classes**
- 📷 Upload images directly through the web interface
- 🤖 CNN-based Deep Learning Model
- 📊 Displays prediction with confidence score
- 📈 Shows Top-3 probable diseases
- ⚡ Fast and user-friendly Streamlit application
- 🌍 Ready for deployment

---

## 🧠 Deep Learning Model

The model is trained using a Convolutional Neural Network (CNN) with:

- Convolution Layers
- Max Pooling Layers
- Batch Normalization
- Dropout Regularization
- Global Average Pooling
- L2 Regularization
- Softmax Classification

Training improvements include:

- ✅ Data Augmentation
- ✅ Early Stopping
- ✅ Reduce Learning Rate on Plateau
- ✅ Model Checkpointing
- ✅ Best Model Saving

---

## 📂 Project Structure

```
Plant-Disease-Detection/
│
├── train_data/
├── valid_data/
├── test_data/
│
├── Train_plant_disease.ipynb
├── Test_plant_disease.ipynb
├── trained_plant_disease_model.keras
├── main.py
├── Diseases.png
├── requirements.txt
├── README.md
└── .gitattributes
```

---

## 🖥️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/Plant-Disease-Detection.git

cd Plant-Disease-Detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run Streamlit Application

```bash
streamlit run main.py
```

The application will automatically open in your browser.

---

## 📸 Application Workflow

1. Launch Streamlit application
2. Upload a plant leaf image
3. Click **Predict**
4. View:

- Disease Name
- Prediction Confidence
- Top 3 Predictions

---

## 🌿 Supported Plant Categories

- Apple
- Blueberry
- Cherry
- Corn
- Grape
- Orange
- Peach
- Pepper
- Potato
- Raspberry
- Soybean
- Squash
- Strawberry
- Tomato

Total Classes: **38**

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| TensorFlow | Deep Learning |
| Keras | Model Building |
| Streamlit | Web Application |
| OpenCV | Image Processing |
| NumPy | Numerical Computing |
| Matplotlib | Visualization |
| Scikit-Learn | Model Evaluation |

---

## 📈 Future Improvements

- Transfer Learning (EfficientNet/MobileNet)
- Real-time Camera Detection
- Disease Severity Estimation
- Treatment & Fertilizer Recommendation
- Multi-language Support
- Cloud Deployment
- Mobile Application

---

## 📷 Screenshots

### Home Page

> Add your screenshot here
<img width="1916" height="822" alt="Screenshot 2026-08-02 101428" src="https://github.com/user-attachments/assets/96d94543-f774-4a45-8d9a-1491fe246c64" />

```
images/home.png
```

### Prediction Page

> Add your screenshot here
<img width="1855" height="874" alt="Screenshot 2026-08-02 101527" src="https://github.com/user-attachments/assets/92fe1bf1-f70f-4b8d-b927-3d6852903d46" />

```
images/prediction.png
```

---

## 📊 Model Performance

| Metric | Value |
|--------|-------|
| Image Size | 128 × 128 |
| Classes | 38 |
| Framework | TensorFlow/Keras |
| Output | Disease Prediction |

> Update the accuracy values after evaluating the model on your validation/test dataset.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 👩‍💻 Author

**Anchal Dubey**

AI/ML Enthusiast | Python Developer | Deep Learning Learner

GitHub: https://github.com/anchaldubey292-boop

---

## ⭐ Support

If you found this project helpful, please ⭐ **Star** this repository and share it with others.

---

## 📜 License

This project is licensed under the **MIT License**.

---

### 🌱 *"Empowering Sustainable Agriculture through Artificial Intelligence.
