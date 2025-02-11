<h1 align="center">🌱 <strong>Leaves Disease Classification</strong> 🌿</h1>

> **This project is the spring semester graduate project for second academic year 2023 | CSC227 - Work-based Professional Project in Computer Science (I).**

This project focuses on detecting plant leaf diseases using machine learning techniques, specifically leveraging Convolutional Neural Networks (CNNs) with the VGG16 architecture. The primary objective is to enable early and accurate detection of plant diseases, contributing to sustainable agriculture and reduced crop losses.

## 🌟 Abstract
Early detection of plant diseases is crucial for minimizing crop losses and promoting sustainable agriculture. This project utilizes a CNN-based machine learning model to classify different plant leaf diseases accurately. By leveraging advanced data augmentation techniques and a robust architecture, the model achieves remarkable accuracy, offering an efficient solution for disease diagnosis in agriculture.

## 🧪 Methodology
- **Data Collection:** Plant leaf images were sourced and divided into training and validation sets.
- **Data Preprocessing:** Rescaling pixel values, applying data augmentation techniques such as rotations and flipping.
- **Model Selection:** VGG16 architecture with custom layers for classification.
- **Training:** The model was trained using TensorFlow and Keras with a sparse categorical cross-entropy loss function.
- **Evaluation:** Performance metrics were computed for both training and validation datasets.
- **Deployment:** A Flask web application can be developed for real-time predictions.

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Model Architecture](#model-architecture)
- [Data Augmentation](#data-augmentation)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## 🌍 Project Overview
The project aims to classify different types of plant leaf diseases by training a CNN model on a dataset of plant leaf images. The trained model helps in detecting diseases early, which is crucial for minimizing crop loss.

## 📁 Dataset
The dataset used for this project contains images of healthy and diseased plant leaves. The dataset is divided into training and validation sets. You can access the dataset from the following link:
[Dataset Link](https://drive.google.com/drive/folders/1QwBJ8290gU5xUXBQL6OjW1bCQxhCTzrb?usp=sharing)

- Training data directory: `ds/`
- Validation data directory: `vs/`

## 🛠️ Technologies Used
- **TensorFlow** for model building and training
- **Keras** for high-level neural network APIs
- **VGG16** as the base CNN architecture
- **Matplotlib** for visualization
- **ImageDataGenerator** for data augmentation

## 🏗️ Model Architecture
The model is based on the VGG16 architecture with additional custom layers for classification. The architecture includes:
- Convolutional layers for feature extraction
- Fully connected layers for classification
- Sparse categorical cross-entropy loss function

## 🔄 Data Augmentation
To improve the model's generalization ability, the following data augmentation techniques were applied:
- Rescaling pixel values
- Random rotations
- Horizontal flipping

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```
2. Navigate to the project directory:
   ```bash
   cd Leaves-Disease-Classification
   ```
3. Install the required dependencies:
   ```bash
   pip install tensorflow matplotlib
   ```

## 🚀 Usage
1. Prepare the training and validation datasets in the specified directories (`ds/` for training, `vs/` for validation).
2. Run the training script:
   ```bash
   python train.py
   ```
3. Evaluate the model and visualize results.

## 📊 Results
The model achieved the following performance metrics:
- **Training Accuracy:** 98.75% ✅
- **Validation Accuracy:** 97.40% ✅
- **Training Loss:** 0.065 📉
- **Validation Loss:** 0.089 📉

These results demonstrate the model's effectiveness in classifying leaf diseases, highlighting its potential for early disease detection and agricultural support.

## 🤝 Contributing
Contributions are welcome! Please fork this repository and submit pull requests for any improvements or additional features.

## 📜 License
This project is licensed under the [MIT License](LICENSE).


## 🌟 Abstract
Early detection of plant diseases is crucial for minimizing crop losses and promoting sustainable agriculture. This project utilizes a CNN-based machine learning model to classify different plant leaf diseases accurately. By leveraging advanced data augmentation techniques and a robust architecture, the model achieves remarkable accuracy, offering an efficient solution for disease diagnosis in agriculture.

## 🧪 Methodology
- **Data Collection:** Plant leaf images were sourced and divided into training and validation sets.
- **Data Preprocessing:** Rescaling pixel values, applying data augmentation techniques such as rotations and flipping.
- **Model Selection:** VGG16 architecture with custom layers for classification.
- **Training:** The model was trained using TensorFlow and Keras with a sparse categorical cross-entropy loss function.
- **Evaluation:** Performance metrics were computed for both training and validation datasets.
- **Deployment:** A Flask web application can be developed for real-time predictions.

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Model Architecture](#model-architecture)
- [Data Augmentation](#data-augmentation)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## 🌍 Project Overview
The project aims to classify different types of plant leaf diseases by training a CNN model on a dataset of plant leaf images. The trained model helps in detecting diseases early, which is crucial for minimizing crop loss.

## 📁 Dataset
The dataset used for this project contains images of healthy and diseased plant leaves. The dataset is divided into training and validation sets. You can access the dataset from the following link:
[Dataset Link](https://drive.google.com/drive/folders/1QwBJ8290gU5xUXBQL6OjW1bCQxhCTzrb?usp=sharing)

- Training data directory: `ds/`
- Validation data directory: `vs/`

## 🛠️ Technologies Used
- **TensorFlow** for model building and training
- **Keras** for high-level neural network APIs
- **VGG16** as the base CNN architecture
- **Matplotlib** for visualization
- **ImageDataGenerator** for data augmentation

## 🏗️ Model Architecture
The model is based on the VGG16 architecture with additional custom layers for classification. The architecture includes:
- Convolutional layers for feature extraction
- Fully connected layers for classification
- Sparse categorical cross-entropy loss function

## 🔄 Data Augmentation
To improve the model's generalization ability, the following data augmentation techniques were applied:
- Rescaling pixel values
- Random rotations
- Horizontal flipping

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/salahabdelkhabir/Leaves-Disease-Classification
   ```
2. Navigate to the project directory:
   ```bash
   cd Leaves-Disease-Classification
   ```
3. Install the required dependencies:
   ```bash
   pip install tensorflow matplotlib
   ```

## 🚀 Usage
1. Prepare the training and validation datasets in the specified directories (`ds/` for training, `vs/` for validation).
2. Run the training script:
   ```bash
   python train.py
   ```
3. Evaluate the model and visualize results.

## 📊 Results
The model achieved the following performance metrics:
- **Training Accuracy:** 98.75% ✅
- **Validation Accuracy:** 97.40% ✅
- **Training Loss:** 0.065 📉
- **Validation Loss:** 0.089 📉

These results demonstrate the model's effectiveness in classifying leaf diseases, highlighting its potential for early disease detection and agricultural support.

## 🤝 Contributing
Contributions are welcome! Please fork this repository and submit pull requests for any improvements or additional features.

## 📜 License
This project is licensed under the [MIT License](LICENSE).
