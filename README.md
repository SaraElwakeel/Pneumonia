# Chest X-Ray Pneumonia Detection

## Project Overview
This project focuses on using deep learning techniques to classify chest X-ray images into two categories: **Normal** or **Pneumonia**. It involves preprocessing image datasets, building a convolutional neural network (CNN), training and evaluating the model, and visualizing results.

## Project Structure
- `chest_xray_pneumonia.ipynb`: Jupyter Notebook containing the full implementation.

## Key Steps Implemented
- Import libraries
- Mount Google Drive
- Import the dataset
- Data augmentation for training set
- Data preprocessing
- Create CNN model
- Compile the model
- Train the model
- Plot training and validation metrics
- Evaluate the model

## How to Run
1. Install the required libraries: TensorFlow, Keras, Matplotlib, NumPy, etc.
2. Run the notebook `chest_xray_pneumonia.ipynb` cell by cell.
3. Ensure the chest X-ray dataset is correctly placed within the specified directory before model training.

## Dataset
The project uses a Chest X-ray dataset to distinguish between normal and pneumonia cases.  
It is divided into training, validation, and testing sets.

## Results
The model training and validation accuracies are tracked across epochs.  
Evaluation metrics (accuracy, loss) are plotted to assess model performance.

## License
This project is intended for **educational purposes** only.
