# 🚀 MobileNetV1 on Caltech101

This project implements **MobileNetV1** to classify images from the **Caltech101 dataset** using **TensorFlow** and **Keras**. The model is trained with different configurations to evaluate its performance.

## 📂 Dataset  

The **Caltech101 dataset** consists of **101 object categories** and a background category, containing a total of **~9,000 images**. Each category has **40 to 800 images**.  

## 🏗 Model Architecture  

- 🏛 **Base Model:** MobileNetV1 (pretrained on **ImageNet**)  
- 🔗 **Additional Layers:** Fully connected layers for classification  
- ⚡ **Activation Function:** ReLU  
- 📏 **Batch Normalization:** Applied for faster convergence  
- 🎯 **Loss Function:** Categorical Cross Entropy / Focal Cross Entropy  
- ⚙ **Optimizer:** Adam  
- 📉 **Learning Rate Scheduling:** ReduceLROnPlateau (optional)  

## 🏋️ Training Configuration  

- 📦 **Batch Size:** 32  
- 🔄 **Epochs:** 10+ (can be increased for better results)  
- ⚙ **Optimizer:** Adam (alternatives: SGD with momentum, AdamW)  
- ❌ **Loss Function:** Cross Entropy / Focal Loss  
- 🖼 **Data Augmentation:** Random flipping, rotation, normalization (optional)  

## 📊 Results  

The model achieves significant improvements in **validation accuracy** during training, demonstrating its ability to **generalize well** to the dataset.  

## 🚀 Future Improvements  

- 🏗 **Implement data augmentation** for better generalization  
- 📉 **Use a learning rate scheduler**  
- ⚙ **Experiment with different optimizers**  
- ⏳ **Train for more epochs**  

## 👨‍💻 Contributors  

- **Quan-Hoang-Ngoc**  
