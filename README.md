Task 8 – Generative AI and Deep Learning Model Optimization
Student Details

Student Name: Snehal Sahebrao Patil
Roll No.: 34
College: B.K. Birla College of Arts, Science & Commerce, Kalyan
Subject: Deep Learning
Task: Task 8 – Generative AI and Deep Learning Model Optimization

Objective

To explore generative deep learning models and deployment-oriented optimization techniques for efficient inference.

The task includes implementing a Deep Convolutional Generative Adversarial Network (DCGAN), generating synthetic images, and applying model optimization techniques such as pruning, quantization, and knowledge distillation.

Dataset

MNIST Dataset

The MNIST dataset contains handwritten digit images from 0 to 9.

Training Images: 60,000
Testing Images: 10,000
Image Size: 28 × 28 pixels
Image Type: Grayscale
Number of Classes: 10

The MNIST dataset was used for DCGAN image generation and deep learning model optimization experiments.

Part A – Generative AI
DCGAN

A Deep Convolutional Generative Adversarial Network (DCGAN) was implemented using the MNIST dataset.

The DCGAN consists of two main networks:

Generator: Generates synthetic handwritten digit images.
Discriminator: Distinguishes between real and generated images.
Implementation

The following steps were performed:

Loaded the MNIST dataset.
Preprocessed and normalized the images.
Built the Generator model.
Built the Discriminator model.
Trained the DCGAN.
Generated synthetic MNIST images.
Analyzed the generated outputs.
Visualized the Generator and Discriminator losses.
Part B – Model Optimization

The following deep learning optimization techniques were explored:

1. Model Pruning

Pruning was applied to remove less important model parameters and reduce model complexity.

2. Quantization

Quantization was used to reduce the numerical precision of model parameters and improve deployment efficiency.

3. Knowledge Distillation

Knowledge distillation was performed using a larger Teacher model and a smaller Student model. The Student model learned useful information from the Teacher model.

Performance Comparison

The optimized models were compared using different performance measures.

Model	Accuracy	Model Size	Inference Time
Baseline CNN	—	—	—
Pruned Model	—	—	—
Quantized Model	—	—	—
Student Model	—	—	—

The actual values obtained during execution are included in the project results.

Results

The DCGAN generated synthetic handwritten digit images similar to the patterns present in the MNIST dataset.

The optimization experiments demonstrated how pruning, quantization, and knowledge distillation can help reduce model complexity and improve the efficiency of deep learning models.

Repository Contents
Task_8_Generative_AI_Optimization.ipynb – Complete implementation
README.md – Project documentation
Generated image samples
Training graphs
Model optimization results
Other supporting files
Tools and Technologies
Python
Google Colab
TensorFlow
Keras
NumPy
Matplotlib
MNIST Dataset
Conclusion

This task demonstrated the use of generative AI through DCGAN and explored important deep learning model optimization techniques. The practical showed how synthetic images can be generated and how pruning, quantization, and knowledge distillation can be used to make deep learning models more efficient for deployment.
