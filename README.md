# HandwrittenRecognitionSystem-Visual-computing- using CNN (LeNet-5)


##  Project Goal

To train a neural network that accurately classifies handwritten digits (0–9) from grayscale images and evaluate its performance using training, validation, and test datasets.

---

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib


---

## 📁 Dataset Format

The dataset used consists of two main folders:
- `train/` — contains subfolders `0/` to `9/`, each holding digit images.
- `test/` — similar structure for evaluating the model.

Images are converted to grayscale, resized to 28x28 pixels, and normalized for training.

---

##  Model Architecture

A simplified version of **LeNet-5**:
- Convolutional Layers
- Max Pooling Layers
- Fully Connected Layers
- Softmax Output (10 classes)

---

## Evaluation

- Accuracy measured on both validation and test sets.
---

##  Results

The trained model achieves high accuracy on clean test data and performs well on new digit images with similar formatting.

---

## Note

Ensure custom test images have a **black background** and **white digits**, and are properly **resized** and **centered**, or preprocessing may be needed to match the training conditions.

---

##  Example Output

- Training Accuracy: ~99%
- Validation Accuracy: ~98%
