# Real-Time Drowsiness Monitoring

This repository contains a deep learning and computer vision project focused on real-time drowsiness detection from facial images. The project compares multiple transfer learning architectures for classifying driver state into **Alert** and **Drowsy** categories, then extends the workflow toward lightweight real-time deployment.

## Project Objective

The main objective of this project is to detect driver drowsiness from images using deep learning techniques. The project also compares multiple pretrained convolutional neural network architectures in order to identify an accurate and efficient model for real-time use.

## Models Implemented

The following models were implemented and evaluated:

- EfficientNetB5.
- EfficientNetB3.
- EfficientNetB1.
- EfficientNetB0.
- MobileNetV3-Small.

## Project Workflow

The notebook covers the following steps:

1. Data loading and preprocessing.
2. Dataset splitting into train, validation, and test sets.
3. Verification of class distribution and sample counts.
4. Image loading using TensorFlow datasets.
5. Transfer learning model building and training.
6. Comparison of multiple pretrained architectures.
7. CPU inference timing analysis.
8. Data augmentation for improved generalization.
9. Final training of a lightweight MobileNetV3-Small model.
10. TensorFlow Lite conversion.
11. Face detection integration using YuNet.
12. Real-time local inference pipeline for drowsiness monitoring.

## Repository Contents

- `Real-Time Drowsiness Monitoring.ipynb` — Main Jupyter Notebook containing the full implementation and analysis.

## Dataset

The dataset used in this project is **not included in this repository** because of its large file size.

The notebook expects the dataset to be organized into two classes:

- `alert`
- `drowsy`

If you would like to run the notebook locally, please place the dataset in the appropriate working directory and update the dataset path in the notebook if necessary.

## Technologies Used

- Python.
- Jupyter Notebook / Google Colab.
- TensorFlow / Keras.
- TensorFlow Lite.
- OpenCV.
- NumPy.
- Matplotlib.
- Seaborn.
- Scikit-learn.
- PIL.
- ipywidgets.

## Evaluation and Analysis

The models were evaluated using:

- Validation performance comparison.
- Test set evaluation.
- CPU inference timing.
- Practical deployment suitability.

These analyses were used to compare the deep learning architectures in terms of both predictive performance and efficiency.

## Notes

- The project uses transfer learning with pretrained CNN backbones.
- Data augmentation was applied to improve generalization.
- The final workflow includes TensorFlow Lite conversion for lightweight deployment.
- YuNet face detection was integrated to support real-time face-based inference.

## How to Run

1. Open the notebook `Real-Time Drowsiness Monitoring.ipynb`.
2. Make sure all required Python libraries are installed.
3. Provide the dataset in the appropriate directory structure.
4. Update dataset and file paths in the notebook if necessary.
5. Run the notebook cells sequentially.

## Academic Context

This project was completed as part of an academic deep learning and computer vision workflow focused on real-time drowsiness monitoring.

## Author

**Mostafa El Hajjar**

## License

This repository is shared for academic and portfolio purposes.
