# Persian Handwritten Digit Recognition
A deep learning project for recognizing Persian handwritten digits using Convolutional Neural Networks (CNNs) built with TensorFlow and Keras.

## Features
- Persian handwritten digit classification (0-9)
- CNN-based architecture
- Image preprocessing
- Dataset caching using NumPy
- Training accuracy and loss visualization
- Confidence score for predictions
- Early stopping to prevent overfitting

## Technologies Used
- Python 3.13
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

## Model Architecture
```text
Conv2D(32) → MaxPooling2D
Conv2D(64) → MaxPooling2D
Conv2D(128)
Flatten
Dense(128)
Dropout(0.5)
Dense(10)
```

## Dataset
- 80,000 Persian handwritten digit images
- 10 classes (0-9)
- Grayscale images
- Resolution: 32×32

## Results
| Metric | Value |
|----------|----------|
| Test Accuracy | 99.56% |
| Wrong Predictions | 70 / 16000 |
