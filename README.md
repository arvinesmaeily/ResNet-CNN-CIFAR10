# ResNet-CNN-CIFAR10

A complete PyTorch implementation of a **custom CNN** and a **ResNet-based architecture** for classifying images in the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html).  
The project includes:
- Full data preprocessing pipeline  
- Albumentations-based augmentation  
- Model comparison between a standard CNN and a ResNet-style CNN  
- Training/evaluation loop with learning rate scheduling  
- Accuracy and loss visualization  

---

## 🚀 Features

- **Custom CNN** built manually layer-by-layer  
- **Residual Network (ResNet)** implementation from scratch using residual blocks  
- **Data augmentation** using Albumentations for better generalization  
- **Training with Adam optimizer + StepLR scheduler**  
- **Automatic GPU detection** for CUDA acceleration  
- **Training and testing accuracy visualization**

---

## 🧩 Model Architectures

### 🔹 CNN Network
A simple sequential convolutional model with 4 convolution blocks and batch normalization.

### 🔹 ResNetCNN Network
Implements skip connections and residual learning:
- Four residual stages (64 → 128 → 256 → 512)
- Adaptive average pooling
- Fully connected classification layer

---

## 📊 Gained Results

(TBN)

---

## 🧠 Training

Run the training notebook (includes data download and extraction)

The notebook will:
1. Download and unpack CIFAR-10  
2. Apply augmentations  
3. Train both CNN and ResNet models  
4. Plot loss/accuracy curves

---

## 📈 Visualization

The code automatically generates:
- Training vs. test **loss curves**
- Training vs. test **accuracy curves**
- 
---

## 🧾 License

MIT License © 2025 [Arvin Esmaeily](https://github.com/arvinesmaeily/ResNet-CNN-CIFAR10/blob/main/LICENSE) 

You’re free to use, modify, and share this project for research and educational purposes.

---

## 🌟 Acknowledgments

- [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)
- [PyTorch](https://pytorch.org/)
- [Albumentations](https://albumentations.ai/)
