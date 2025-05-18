# -Cat-vs-Dog-Image-Classification
 This repository consist of the Convolution NN on dataset cats-vs-dogs
# 🐱🐶 Cat vs Dog Image Classification

A Convolutional Neural Network (CNN) based deep learning model to classify images as either a **cat** or a **dog**. Built using Keras and trained on the Dogs vs. Cats dataset from Kaggle.

## 📌 Dataset

- [Dogs vs. Cats Dataset - Kaggle](https://www.kaggle.com/datasets/salader/dogs-vs-cats)

## 📈 Model Summary

- ✅ CNN with 3 Convolutional layers + MaxPooling
- ✅ Dense layers for classification
- ✅ Sigmoid activation for binary output
- ✅ Binary crossentropy loss

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy, Matplotlib

## 🧪 Training

```python
model.fit(train_ds, epochs=10, validation_data=validation_ds)
```

## 🧾 Prediction

```python
prediction = model.predict(img)
label = "dog" if prediction[0][0] > 0.5 else "cat"
```

## 🔧 Setup

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/cat-dog-classification.git
   cd cat-dog-classification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Add your `kaggle.json` to root or `~/.kaggle/`.

## 🙋‍♀️ Author

- [SAKSHI SRIVASTAVA](https://github.com/Sakshi-Srivastava19)

## 📃 License

MIT
