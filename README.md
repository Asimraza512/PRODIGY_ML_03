🐶🐱 Cats vs Dogs Classification using SVM
This project implements a Support Vector Machine (SVM) algorithm to classify images of cats and dogs using the popular Dogs vs. Cats dataset from Kaggle.

The goal is to build a binary image classifier that can distinguish between images of cats and dogs using supervised machine learning.

📂 Dataset
Source: Kaggle - Dogs vs. Cats Dataset

Files:

train.zip: Contains 25,000 labeled images (cats and dogs)

test1.zip: Contains 12,500 unlabeled images for testing (optional)

Format: Images are labeled in the filename (cat.0.jpg, dog.1.jpg)

🧠 Objective
Load and preprocess image data (resize, grayscale/flatten)

Train an SVM classifier (linear or kernel-based)

Evaluate model performance on a test set

Visualize a few predictions

📊 Approach
Data Preprocessing:

Resize images to a uniform size (e.g. 64x64)

Convert images to grayscale or flatten RGB

Normalize pixel values

Assign binary labels (0 for cat, 1 for dog)

Model Training:

Use sklearn.svm.SVC with linear or RBF kernel

Use a subset of data due to computational limits

Model Evaluation:

Accuracy, confusion matrix

Show sample predictions

📚 Libraries Used
numpy – numerical operations

pandas – data handling

matplotlib / seaborn – plotting results

opencv-python – image loading and preprocessing

scikit-learn – SVM implementation and evaluation

os / glob – file handling

