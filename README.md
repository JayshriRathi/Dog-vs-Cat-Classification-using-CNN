## 🐶🐱 Dog vs Cat Image Classification using CNN

This project demonstrates a simple Convolutional Neural Network (CNN) model built using TensorFlow and Keras to classify images of cats and dogs. It includes data preprocessing, model training, evaluation, and testing on custom images — including both local and web-based images.

---

### 📌 Features

- Image classification using a CNN model
- Preprocessing with Keras `ImageDataGenerator`
- Custom prediction on user-provided images
- Matplotlib visualization for input images
- Easily extendable for more classes

---

### 🧠 Model Architecture

- Convolutional layers with ReLU activation
- MaxPooling for spatial reduction
- Fully connected Dense layers
- Output layer with softmax (2-class: cat or dog)


Use any dataset (e.g., [Kaggle Dogs vs Cats](https://www.kaggle.com/c/dogs-vs-cats/data)) and split accordingly.


### 📌 Requirements

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
- Pillow
- Requests (for web image testing)

You can install them using:
```bash
pip install tensorflow numpy matplotlib pillow requests
```



### 🏁 Conclusion

This project showcases the effectiveness of CNNs for basic image classification tasks. It can be expanded to multi-class classification or used as a base for object detection tasks.

