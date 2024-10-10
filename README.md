# Satellite Image Classification using CNN and Fine-Tuning NASNet Mobile





**Introduction**  
The "Satellite Image Classification" project utilizes a dataset from Kaggle that comprises satellite images categorized into four distinct classes: "Cloudy," "Desert," "Green_Area," and "Water." These images provide a rich source of data for analyzing various geographical features from satellite views, allowing for machine learning models to learn patterns and make accurate predictions.

**Dataset Description**  
The dataset contains high-resolution satellite images, each resized to 256x256 pixels, providing a standardized input for training the model. The images are evenly distributed across the four categories, enabling balanced classification tasks. The data is publicly available on Kaggle, making it accessible for benchmarking and experimentation. Each image is labeled according to one of the four classes, which represent common land and weather conditions as observed from space. This diverse dataset provides a challenging classification problem due to the visual similarity in some categories.

**Objective**  
The objective of this project is to classify satellite images with high accuracy by leveraging Convolutional Neural Networks (CNNs) and transfer learning techniques. By fine-tuning the pre-trained NASNetMobile model, the goal is to enhance performance and achieve an accuracy of 95%. Fine-tuning involves adjusting the NASNetMobile architecture to adapt to the specific satellite image dataset, optimizing the model for this particular classification task.

By using CNNs and fine-tuning a pre-trained model, this project seeks to build a robust system that accurately distinguishes between the different types of satellite imagery while optimizing performance metrics like accuracy, precision, recall, and others.
