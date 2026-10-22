# In-Field Crop Leaf Disease Identification and Severity Quantification

## 📌 Project Overview

Crop diseases are a major challenge in agriculture because they can reduce crop quality and yield. Early identification of leaf diseases can help farmers take appropriate action and protect their crops.

This project uses deep learning to classify crop leaf images into two categories: **Healthy** and **Diseased**. It uses the EfficientNetB0 model with TensorFlow and Keras to identify whether a leaf is healthy or shows signs of disease.

The project is developed as a mini project at SRM Institute of Science and Technology, Tiruchirappalli.

## 🎯 Objectives

- To develop a deep learning-based crop leaf classification system.
- To identify healthy and diseased crop leaves from images.
- To use transfer learning with the EfficientNetB0 model.
- To evaluate model performance using test accuracy and classification metrics.
- To explore the use of AI in supporting agricultural disease identification.

## 🧠 Model and Technologies

- **Programming Language:** Python
- **Deep Learning Framework:** TensorFlow and Keras
- **Pre-trained Model:** EfficientNetB0
- **Dataset:** PlantVillage
- **Development Environment:** Google Colab
- **Image Processing:** Image resizing and preprocessing
- **Task:** Binary image classification

## 📂 Dataset

The project uses the PlantVillage dataset, which contains images of healthy and diseased plant leaves across multiple crop types.

The original dataset contains 54,303 images across 38 classes. These classes are grouped into two categories for this project:

- **Healthy:** Images of healthy plant leaves.
- **Diseased:** Images of plant leaves affected by disease.

The dataset is divided into training, validation, and testing subsets to train and evaluate the model.

## ⚙️ Methodology

1. **Dataset Preparation:** Load the PlantVillage dataset and group the original classes into Healthy and Diseased categories.
2. **Image Preprocessing:** Resize images to 224 × 224 pixels and prepare them for model input.
3. **Data Splitting:** Divide the dataset into training, validation, and testing subsets.
4. **Transfer Learning:** Use the pre-trained EfficientNetB0 model to extract useful image features.
5. **Classification:** Add a binary classification layer to predict whether a leaf is healthy or diseased.
6. **Model Training:** Train the classification layer and monitor validation performance.
7. **Evaluation:** Evaluate the trained model using test accuracy, loss, a confusion matrix, and classification metrics.

## 📊 Results

The trained  model achieved the following performance on the test dataset:

- **Test Accuracy:** 98.77%
- **Test Loss:** 0.0365
- **Healthy Class F1-Score:** 0.98
- **Diseased Class F1-Score:** 0.99

These results indicate that the model performed well at distinguishing healthy and diseased leaf images in the evaluated PlantVillage test split.

**Note:** Performance on real-world field images may differ and requires further testing.

## 📈 Project Outputs

The project includes the following visualizations:

- Training and validation accuracy and loss graphs.
- Confusion matrix.
- Sample leaf images with predicted classifications.

## 🚀 How to Run

1. Open the Jupyter Notebook in Google Colab.
2. Import the required libraries.
3. Load the PlantVillage dataset.
4. Run the notebook cells in order to preprocess the data, train the model, and evaluate its performance.
5. Use the trained model to classify leaf images as Healthy or Diseased.

## 🔮 Future Enhancements

- Extend the model to identify individual crop diseases.
- Add disease severity estimation as a percentage.
- Test the model on real-world field images under different lighting and background conditions.
- Develop a user-friendly web or mobile application for farmers.
- Explore reliable agricultural recommendations for disease management.

## 👩‍💻 Authors

- **SUBHAPRIYA S**
- **MADHUMITHA R**
- **MAHA V.**

**Institution:** SRM Institute of Science and Technology, Tiruchirappalli

## 🏁 Conclusion

This project demonstrates how deep learning and transfer learning can be applied to crop leaf image classification. Using EfficientNetB0, the system achieved **98.77% test accuracy** in distinguishing healthy and diseased leaf images on the evaluated PlantVillage dataset.

The project provides a foundation for future work in crop disease recognition and severity estimation. Further validation is needed before using the model in real agricultural field conditions.
