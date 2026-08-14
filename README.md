# 🍔 Food Image Classification using CNN & PyTorch

Build your own **Food Image Classification AI** using a custom **Convolutional Neural Network (CNN)** with **PyTorch**! 🚀

This project demonstrates how to build an end-to-end image classification pipeline — from downloading a food dataset with **Roboflow** and preprocessing images to training a custom CNN and predicting food categories on unseen images.

🎥 **Watch the Full Tutorial**

👉 [YouTube Tutorial](YOUR_YOUTUBE_VIDEO_LINK_HERE)

---

## 🚀 Project Overview

In this project, we build a custom CNN model using **PyTorch** to classify different types of food images.

The complete workflow includes:

* 📥 Downloading the dataset from Roboflow
* 🗂️ Organizing the food classification dataset
* 🖼️ Image preprocessing and normalization
* ⚙️ Creating a custom PyTorch Dataset
* 📦 Loading images using DataLoader
* 🧠 Building a CNN from scratch
* 🔥 Training the model with Cross Entropy Loss
* ⚡ Using Adam optimizer
* 📊 Visualizing training loss and accuracy
* 💾 Saving and loading the trained model
* 🔍 Predicting food categories from test images

---

## 🧠 Model Architecture

The custom CNN consists of:

* Convolutional Layers
* ReLU Activation
* Max Pooling
* Flatten Layer
* Fully Connected Layers
* Final Classification Layer

The model takes RGB images resized to **60 × 60 pixels** as input and produces predictions for the food classes.

---

## 🛠️ Technologies Used

* Python
* PyTorch
* Torchvision
* CNN
* Deep Learning
* Computer Vision
* Roboflow
* NumPy
* Matplotlib
* PIL

---

## 📂 Project Workflow

```text
Food Dataset
     ↓
Image Preprocessing
     ↓
Custom PyTorch Dataset
     ↓
DataLoader
     ↓
CNN Model
     ↓
Model Training
     ↓
Loss & Accuracy Visualization
     ↓
Save Model
     ↓
Food Classification
```

---

## 📊 Training

The model is trained using:

* **Optimizer:** Adam
* **Loss Function:** Cross Entropy Loss
* **Epochs:** 50
* **Batch Size:** 32
* **Learning Rate:** 0.0006

Training loss and accuracy are recorded and visualized to monitor the learning process.

---

## 🔮 Prediction

After training, the saved model can be loaded and used to classify new food images.

The prediction pipeline:

```text
Input Image
     ↓
Resize & Normalize
     ↓
CNN Model
     ↓
Predicted Class
```

---

## 🎯 What You'll Learn

By working through this project, you'll understand how to:

✅ Build a CNN from scratch with PyTorch
✅ Create a custom image classification dataset
✅ Preprocess images for deep learning
✅ Train a CNN model
✅ Monitor model performance
✅ Save and load PyTorch models
✅ Perform inference on unseen images

---

## ▶️ Run the Project

Install the required libraries:

```bash
pip install torch torchvision matplotlib pandas pillow roboflow tqdm torchsummary
```

Then run the notebook/script and follow the training pipeline.

---

## 🎥 Tutorial

Learn the complete project step-by-step in the YouTube tutorial:

👉 **[Watch the Food Image Classification Tutorial](https://youtu.be/wHSP8y5zoFI)**

---

## ⭐ Support the Project

If you found this project useful:

⭐ Star this repository
🍴 Fork the repository
📺 Watch the tutorial
🔔 Subscribe for more AI & Computer Vision projects

---

## 🔖 Topics

`food-classification` `image-classification` `cnn` `pytorch` `deep-learning` `computer-vision` `python` `machine-learning` `roboflow` `ai`
