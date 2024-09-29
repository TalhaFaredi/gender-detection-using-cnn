

# Gender Prediction Model

This repository contains a Convolutional Neural Network (CNN) implemented using TensorFlow/Keras to classify gender based on images. The model uses three convolutional layers followed by max pooling and dense layers. It’s trained on a binary dataset for classification and can predict gender from images.

### **Model Features**
- Three convolutional layers for feature extraction.
- Max-pooling for dimensionality reduction.
- Binary classification with sigmoid activation.
- Real-time image prediction.

### **Installation**

```bash
pip install tensorflow numpy pillow
```

### **Usage**

1. Place images in the `Training` and `val` folders for model training and validation.
2. Train the model by running the script.
3. Use a test image to predict the gender.

### **Example**

```python
python train.py
```



