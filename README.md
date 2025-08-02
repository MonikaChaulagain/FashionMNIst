# 🧵 FashionMNIST CNN Classifier

This project implements a simple convolutional neural network (CNN) to classify images from the [FashionMNIST](https://github.com/zalandoresearch/fashion-mnist) dataset. It achieves ~87.5% accuracy on the test set and includes code to test your own grayscale fashion images.

> **Why?**
> FashionMNIST is a better drop-in replacement for MNIST, featuring clothing images rather than digits — a more realistic computer vision challenge.


## 🚀 Features

✅ Convolutional neural network from scratch in PyTorch
✅ Trained on 28x28 grayscale fashion items
✅ Testing loop with accuracy tracking
✅ Code to predict your own custom fashion image
✅ Clean, minimal structure — easy to expand


## 🧩 Project Structure

```
fashion_mnist_project/
│
├── model.py            # CNN architecture
├── train.py            # Training pipeline
├── test.py             # Test accuracy evaluation
├── predict.py          # For custom image prediction



## 📈 Results

| Metric   | Value                       |
| -------- | --------------------------- |
| Test Acc | 87.5%                       |
| Model    | 2 Conv layers + 2 FC layers |
| Dataset  | FashionMNIST (10 classes)   |

---

## ⚠️ Limitations

* Trained on **28x28 grayscale sketches** only — real-life photos (e.g. a shirt on a hanger) will likely misclassify.
* For production-grade fashion recognition, consider transfer learning on **real clothing datasets** (e.g., DeepFashion).

