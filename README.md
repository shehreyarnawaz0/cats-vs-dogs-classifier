# 🐱🐶 Cats vs. Dogs Image Classifier

A deep learning project that classifies images as either **cat** or **dog** using **transfer learning** with the **MobileNetV2** model and **TensorFlow (Keras)**.

## 🚀 Overview
Build an image classifier using a pretrained MobileNetV2 model to differentiate between cats and dogs with high accuracy using transfer learning.

## 📂 Dataset Structure
```
cat vs dog/
├── cats/
│   ├── cat.1.jpg
│   └── ...
├── dogs/
│   ├── dog.1.jpg
│   └── ...
```

## 🧠 Model Architecture
- 📦 Base Model: MobileNetV2 (pretrained on ImageNet)
- 🔧 Transfer Learning: Feature extraction
- 🧰 Frameworks: TensorFlow + Keras

## 📊 Results
- ✅ Validation Accuracy: ~88–90%
- 📈 Includes accuracy/loss graphs and confusion matrix
- 🧪 Saved model: `cats_vs_dogs_model.h5`

## 💻 How to Use

### 1. Train the Model
Open `cats-vs-dogs.ipynb` and run all cells to:
- Load and preprocess dataset
- Train MobileNetV2 with transfer learning
- Evaluate and save the model

### 2. Predict an Image
Open `predict_image.ipynb` to:
- Upload an image of a cat or dog
- Get the predicted label

## 🖼️ Sample Prediction Output
```
Prediction: Dog ✅
```

## 🔍 Features
- ✅ Pretrained MobileNetV2 used
- ✅ Clean image preprocessing pipeline
- ✅ Model accuracy and loss plots
- ✅ Confusion matrix visualization
- ✅ Upload image and get prediction
- ✅ Model saving in `.h5` format

## 🚧 Future Enhancements
- 📸 Real-time webcam prediction (OpenCV)
- 🌐 Web deployment using Flask / Streamlit
- 🎯 Fine-tuning MobileNetV2 top layers

## 📄 License
Licensed under the **MIT License**.

## 🙋‍♂️ Author
**Shehreyar Nawaz**  
📧 shehreyarnawaz0@gmail.com  
🔗 [GitHub](https://github.com/shehreyarnawaz0)
