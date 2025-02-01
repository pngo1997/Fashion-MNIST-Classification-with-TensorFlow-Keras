# 👕 Fashion MNIST Classification with TensorFlow/Keras  

## 📜 Overview  
This project explores **image classification** using a **Multi-layer Feed-Forward Neural Network** on the **Fashion MNIST dataset**, a drop-in replacement for the traditional MNIST dataset. The goal is to **experiment with different model architectures and hyperparameters** to optimize performance.  

📌 **Dataset**: **Fashion MNIST** (28×28 grayscale images, 10 classes)  
📌 **Framework**: **TensorFlow & Keras**  
📌 **Programming Environment**: **Google Colab**  

## 🚀 1️⃣ Getting Started  
### **Model Constraints**  
To ensure correct execution, the following **must not be changed**:  
- **Input Layer**: Must have `Flatten(input_shape=(28, 28))`.  
- **Output Layer**: Must be `Dense(10)` with **`sparse_categorical_crossentropy(from_logits=True)`**.  

## 🎯 2️⃣ Objectives  
1. **Compare Model Architectures**:  
   - Baseline: **Single hidden layer**  
   - Experiment: **Additional hidden Dense(32) layer before output**  

2. **Hyperparameter Tuning**:  
   - **Learning Rate** (`Keras Optimizer`)  
   - **Regularization Methods** (`Keras Regularizer`)  
   - **Dropout Layer** (before output layer)  

3. **Analyze Best Model Performance**  
   - **Classification Accuracy**  
   - **Loss Value**  
   - **Learning Stability**  
   - **Overfitting & Generalization**  

## 🧪 3️⃣ Experimentation Strategy  
1. **Test baseline model** (one hidden layer).  
2. **Add a Dense(32) hidden layer** and compare performance.  
3. **Tune hyperparameters sequentially**:  
   - **Step 1**: Test different **learning rates** (log scale).  
   - **Step 2**: Apply **L1/L2 regularization**.  
   - **Step 3**: Introduce **Dropout** and optimize.  
4. **Select the best-performing configuration** based on accuracy, loss, and overfitting.  
📌 **Results are reported after each step.**

## 📌 Summary  
✅ Implemented Fashion MNIST classification using TensorFlow/Keras.

✅ Compared model architectures with additional hidden layers.

✅ Experimented with learning rate, regularization, and dropout.

✅ Analyzed best hyperparameter settings for performance & generalization.
