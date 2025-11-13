## 🌾 Rice Variety Classification using CNN

Developed a **Convolutional Neural Network (CNN)** model to classify different varieties of rice based on image data.
The model is trained to identify rice types such as **Basmati, Jasmine, and others** from image features using deep learning.


## 🧠 Project Overview

* Implemented a **CNN model** using **TensorFlow/Keras** to classify rice varieties.
* Preprocessed and normalized the image dataset for better training performance.
* Split dataset into training and testing sets to evaluate the model.
* Achieved high classification accuracy through multiple training epochs.
* Visualized accuracy and loss to understand model performance.

## 📂 Dataset Information

* Dataset Name: Rice Image Dataset
* Classes (5 types):

1. Arborio
2. Basmati
3. Ipsala
4. Jasmine
5. Karacadag

* Each folder contains images of the respective rice variety.
* These images were used for training, validation, and testing.

## ⚙️ Technologies Used

* **Python**
* **TensorFlow / Keras**
* **NumPy**
* **Matplotlib**


## 📊 Model Workflow

1. **Load and preprocess dataset** (resizing, scaling).
2. **Build CNN model** with convolution, pooling, and dense layers.
3. **Compile** model using an appropriate optimizer and loss function.
4. **Train** model on the dataset.
5. **Evaluate and predict** rice varieties on test data.

## 📈 Results

* Model trained successfully with high accuracy.
* Tested with rice images for prediction.
* Visualized performance metrics and prediction results.


## 📂 Project Structure

```
Rice_variety_classification_using_CNN.ipynb   # Jupyter notebook with full implementation
Rice_Image_Dataset                            # Image Dataset
README.md                                     # Project description file
```

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/Viswavani/Rice_variety_classification_using_CNN.git
   ```
2. Open the notebook in Jupyter or VS Code.
3. Run all cells to train and test the CNN model.
