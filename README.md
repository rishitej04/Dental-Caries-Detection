
## Project Title: Teeth Decay Detection using Deep Learning

### Description

This project involves the development and implementation of a deep learning model to detect teeth decay from images. The primary goal is to classify dental images into categories such as "caries" (decayed) and "no-caries" (healthy).

### Key Features:

- **Data Preparation**: 
  - The dataset is organized into training and testing directories. The training set is used to teach the model to differentiate between decayed and healthy teeth, while the testing set is used to evaluate the model's performance.
  - A CSV file is generated for both the training and testing datasets, containing image paths and corresponding labels.

- **Model Architecture**:
  - The model is built using TensorFlow and Keras, incorporating layers like `Dense`, `Flatten`, `Dropout`, and others.
  - Image augmentation techniques are applied using `ImageDataGenerator` to enhance the robustness of the model.

- **Training**:
  - The model is trained with various callbacks, including `ModelCheckpoint` for saving the best model, and `WandbCallback` for monitoring the training process with Weights and Biases.
  - RMSprop optimizer is utilized to optimize the model during training.

- **Visualization**:
  - The project includes visualization tools like `seaborn` and `matplotlib` for plotting and analyzing the training process and results.
  - Visualizations of model architecture and performance metrics are generated.

### Tools and Libraries:
- TensorFlow and Keras for deep learning model development.
- OpenCV for image processing.
- Pandas for data handling.
- Weights and Biases (Wandb) for experiment tracking.
- Seaborn and Matplotlib for data visualization.
