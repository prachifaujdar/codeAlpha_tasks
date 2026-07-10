Handwritten Character Recognition using CNN

Overview:-
This project implements a Handwritten Character Recognition system using a Convolutional Neural Network (CNN). The model is trained on the EMNIST dataset to recognize handwritten English characters with high accuracy.

Features:
- Handwritten character recognition
- Deep Learning using CNN
- Image preprocessing
- Model training and evaluation
- Character prediction with confidence score
- Accuracy and Loss visualization

Technologies Used:
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- TensorFlow Datasets (EMNIST)
- Google Colab

Dataset:
**EMNIST (Extended MNIST)**
- Handwritten English characters
- Image Size: 28 × 28 pixels
- Grayscale Images

Model Architecture:
- Conv2D (32 Filters)
- MaxPooling2D
- Conv2D (64 Filters)
- MaxPooling2D
- Flatten
- Dense (128 Neurons)
- Dropout
- Dense Output Layer (Softmax)

 Results:
- Training Accuracy: ~93%
- Validation Accuracy: ~92%
- High-confidence handwritten character prediction

Example Output:

Predicted Character: N
Confidence: 99.97%

How to Run:

1. Open the notebook in Google Colab.
2. Install the required libraries.
3. Run all cells sequentially.
4. Train the CNN model.
5. View evaluation metrics and prediction results.

Output:
- Character Prediction
- Accuracy Graph
- Loss Graph
- Model Evaluation

Future Improvements:
- Support complete word recognition
- CRNN/LSTM based sequence recognition
- Real-time webcam handwriting recognition
- Multi-language handwritten OCR

