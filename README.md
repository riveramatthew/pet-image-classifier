# 🐶 Image Classification for a City Dog Show

## 📌 Project Goal
The goal of this project is to improve Python programming skills while applying image classification techniques to identify dog breeds.  
You will **not** build a classifier from scratch—instead, you will use a provided classifier to filter and identify dog breeds from submitted images.

---

## 📖 Project Description
Your city is hosting a **citywide dog show**, and you have volunteered to help with contestant registration.  
Participants must submit:
- An image of their dog
- Biographical information

However, some participants may try to register pets that are **not dogs**.  
Your task is to use a **pre-built image classifier** to:
1. Verify whether each participant’s submission is a dog.
2. Identify the breed if it is a dog.

You will:
- Compare three convolutional neural network (CNN) architectures (**AlexNet, VGG, ResNet**).
- Determine which works best for:
  - Classifying "dog" vs "not-a-dog".
  - Correctly identifying the dog's breed.
- Measure runtime performance for each model.

---

## 🎯 Objectives
1. **Identify Dogs vs. Not Dogs**  
   Ensure non-dog entries are rejected.

2. **Breed Classification**  
   Determine which CNN architecture gives the best accuracy.

3. **Performance Measurement**  
   Time each model to analyze the trade-off between speed and accuracy.

---

## 🧠 Background
- **Convolutional Neural Networks (CNNs)** are powerful for image recognition because they detect features such as **edges, colors, and textures**.
- The classifier you will use has been trained on **ImageNet**, a dataset of **1.2 million images**.
- Some breeds look **very similar**, making classification challenging:
  - Great Pyrenees ↔ Kuvasz
  - German Shepherd ↔ Malinois
  - Beagle ↔ Walker Hound

---

## 🛠️ Tools Provided
- `classifier.py` → Function to classify an image using AlexNet, VGG, or ResNet.
- `test_classifier.py` → Example of how to use the classifier function.
- Pre-trained CNN models.

---

## 📂 Project Structure
