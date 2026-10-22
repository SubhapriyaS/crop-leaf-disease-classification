# Crop Leaf Disease Classification Using EfficientNetB0

## Project Overview
This mini project uses deep learning to classify crop leaf images into two categories: **Healthy** and **Diseased**.

## Objectives
- Build a binary crop leaf image classifier.
- Use transfer learning with EfficientNetB0.
- Evaluate performance using accuracy, precision, recall, F1-score, and a confusion matrix.

## Dataset
The project uses the PlantVillage dataset from TensorFlow Datasets, containing 38 original leaf classes grouped into Healthy and Diseased categories.

## Methodology
1. Load and preprocess images using TensorFlow Datasets.
2. Resize images to 224 × 224 pixels.
3. Use a pretrained EfficientNetB0 model.
4. Train a binary classification output layer.
5. Evaluate the model on a held-out test split.

## Results
- Test accuracy: **98.77%**
- Test loss: **0.0365**
- Healthy F1-score: **0.98**
- Diseased F1-score: **0.99**

These results apply to the dataset split used in this experiment. Performance on real-world field images may differ.

## Limitations
The current model classifies leaves as Healthy or Diseased. It does not estimate the percentage of damaged leaf area, and it has not been independently validated on field images.

## Future Work
- Test the model on real crop field photographs.
- Explore disease severity estimation using image segmentation.
- Improve generalization to different lighting and backgrounds.

## Technologies
- Python
- TensorFlow and Keras
- TensorFlow Datasets
- EfficientNetB0
- Matplotlib and scikit-learn

## How to Run
Open `crop_leaf_disease.ipynb` in Google Colab and run the notebook cells in order. The dataset will be loaded through TensorFlow Datasets.

## Author
Student mini project
