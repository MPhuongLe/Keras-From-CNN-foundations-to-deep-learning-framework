# Keras: From CNN foundations to Deep learning framework

Introduction to Big Data course – fit@hcmus  
Updated: May 26, 2024  

## Introduction  

This is our teamwork for the *Introduction to Big Data* course, where we explore **Keras**, a high-level and user-friendly deep learning framework that runs on **TensorFlow**, **JAX**, and **PyTorch** backends.  

The report introduces **deep learning through Convolutional Neural Networks (CNNs)** — starting from the basic concepts and intuition, and moving toward the **MNIST handwritten digit classification** example. This serves both as theoretical grounding and as a practical demonstration for understanding Keras’ power and simplicity.  

## Contents

### 1. Problem Statement  

This section introduces deep learning by explaining the intuition behind **Convolutional Neural Networks (CNNs)**, inspired by the human visual system. It covers the structure and role of key CNN layers such as convolution, pooling, and dense layers, illustrating how they process images hierarchically to detect patterns and objects.  

To apply these concepts, we use the **MNIST handwritten digit classification** problem — a benchmark dataset of 70,000 images of digits (0–9). By classifying these images using CNNs, we gain a foundational understanding of how Keras enables efficient model building and experimentation in image recognition tasks.  

### 2. Keras History and Development  

We explore the journey of Keras from the early days of deep learning to its current cross-backend design. Starting with the **rise of ImageNet and AlexNet**, the section explains how these milestones led François Chollet to create Keras in 2015 as an accessible deep learning API. Later, Google’s involvement integrated Keras tightly with TensorFlow, making it one of the most popular frameworks in the field.  

The section also compares **Keras**, **TensorFlow**, and **PyTorch**, highlighting their strengths in usability, flexibility, and performance. It concludes with real-world applications of Keras across research and industry, including usage by Netflix, Uber, NASA, and CERN.  

### 3. Keras Architecture  

Here, we delve into how Keras is structured and why it is so approachable for developers. The framework is built around two core components — **Layers** and **Models** — where each layer represents a tensor-in/tensor-out transformation.  

Keras provides three main APIs for model construction: the **Sequential API** for simple linear models, the **Functional API** for flexible architectures, and **Model Subclassing** for advanced custom implementations. The section also discusses **Keras 3.0** innovations, including its **cross-backend architecture** that allows seamless switching between TensorFlow, JAX, and PyTorch. Features like `keras.ops` unify backend operations, making Keras versatile for research, training, and deployment workflows.  

### 4. Demonstration  

This section presents the full implementation of a **CNN for MNIST digit classification** using Keras. It covers every step — importing libraries, preprocessing data, building the CNN architecture, training the model, and evaluating its performance.  

The demonstration shows how Keras simplifies the entire workflow with functions like `fit()`, `evaluate()`, and `predict()`. The trained model achieves high accuracy and can be saved for reuse. Additionally, we built a **live digit prediction app** using **OpenCV**, where users can draw digits on a canvas and see instant predictions — a practical example of how deep learning models can interact with real-world input.  

---

## About us: GROUP CQ2021-01  
Our team includes 4 members:  
- 21120275  Huỳnh Cao Khôi  
- 21120308  Phạm Lê Tú Nhi  
- 21120496  Chu Hải Linh  
- 21120533  Lê Thị Minh Phương  
