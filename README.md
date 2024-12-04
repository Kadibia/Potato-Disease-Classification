Potato Disease Classification

Introduction

Potato diseases can significantly impact crop yields and quality. Early and accurate detection is crucial for effective disease management. This project aims to develop a machine learning model capable of identifying various potato diseases based on leaf images.

Dataset

The dataset used for training and testing the model consists of a large number of images of potato leaves affected by different diseases, as well as healthy leaves. The dataset is carefully curated and preprocessed to ensure optimal model performance.

Model Architecture

We employed a Convolutional Neural Network (CNN) architecture, a popular choice for image classification tasks. The CNN model consists of multiple layers, including convolutional layers, pooling layers, and fully connected layers. The convolutional layers extract features from the input images, while the fully connected layers classify the images into different disease categories.   

Training and Evaluation

The model was trained using a combination of techniques, such as data augmentation, transfer learning, and optimization algorithms. The training process involved minimizing the cross-entropy loss function using stochastic gradient descent. The model's performance was evaluated using metrics like accuracy, precision, recall, and F1-score.

Usage

Clone the Repository:
Bash
`git clone https://github.com/kadibia/potato-disease-classification.git`


Install Dependencies:
`Bash`
`pip install -r requirements.txt`


Prepare Images: Ensure images are in a suitable format (e.g., JPEG, PNG) and resized to a consistent size.
Run the Model: Execute the provided script to load the trained model and classify input images.
Future Work

Expand Dataset: Incorporate a more diverse dataset to improve model robustness.
Experiment with Different Architectures: Explore other deep learning architectures, such as EfficientNet or ResNet.
