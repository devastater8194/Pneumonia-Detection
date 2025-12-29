Pneumonia Detection from Chest X-Ray Images

a deep learning model using CNN that detects whether the image of the x ray provided has pneumonia or not
This project implements a deep learning–based binary classification model to detect pneumonia from chest X-ray images using convolutional neural networks and transfer learning techniques.

The model is trained on the publicly available Kaggle Chest X-Ray Pneumonia dataset and evaluated using separate training, validation, and test splits. Special care is taken to handle class imbalance and assess performance using medically relevant metrics.

Dataset

Chest X-Ray Pneumonia Dataset (Kaggle):
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

The dataset is not included in this repository due to size constraints.

Model Performance

Training Accuracy: 99.8%

Validation Accuracy: 100%

Test Accuracy: ~78%

(Accuracy is reported alongside precision and recall due to the imbalanced nature of medical data.)

Tech Stack

Python

TensorFlow / Keras

NumPy, Matplotlib

Scikit-learn

Notes
