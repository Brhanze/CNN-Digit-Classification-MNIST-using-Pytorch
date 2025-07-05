# 🧠 CNN Digit Classification with PyTorch

This project demonstrates how to build, train, and evaluate a Convolutional Neural Network (CNN) using PyTorch on the **MNIST dataset**. The model achieves over **98.5% accuracy** on handwritten digit classification — making it a great introduction to computer vision and deep learning.

---

## 📌 Key Highlights

- ✅ Built using **PyTorch**
- 📦 Dataset: **MNIST** (handwritten digits)
- 📈 Training Accuracy: **99.1%**
- 🧪 Test Accuracy: **98.57%**
- 🕐 Training Time: ~**3.74 minutes**
- 📊 Plotted **loss** and **accuracy curves**
- 🔍 Inference on custom test images

---

## 🧠 Project Workflow

### 1. 📥 Dataset
- Loaded the **MNIST dataset** using `torchvision.datasets`
- Applied transformations (`ToTensor`, normalization)

### 2. 🧱 Model Architecture
A simple yet effective CNN architecture:
- Conv2D → ReLU → MaxPool
- Conv2D → ReLU → MaxPool
- Flatten → Fully Connected → Output Layer

### 3. ⚙️ Training
- Optimizer: `Adam`
- Loss: `CrossEntropyLoss`
- Epochs: `5`
- Batch Size: `600`
- Trained using GPU if available

### 4. 📊 Visualization
- Plotted training vs. validation **loss**
- Plotted training vs. validation **accuracy**



### 5. 📌 Evaluation
- Final Test Accuracy: **98.57%**
- Validated using entire test set
- Visualized sample predictions




## 🛠️ Tech Stack

- Python 3.x
- PyTorch
- torchvision
- matplotlib
- NumPy

---

## 🧪 How to Run

1. Clone the repo:

```bash
git clone [https://github.com/yourusername/](https://github.com/Brhanze/CNN-Digit-Classification-MNIST-using-Pytorch/blob/main/CNN.ipynb)/CNN-Digit-Classification.git
cd CNN-Digit-Classification
