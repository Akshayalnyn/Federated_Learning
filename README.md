Federated learning is a decentralized approach to machine learning that allows you to train models without centralizing the data. Instead of gathering all the data in one place, federated learning enables the training process to occur locally on individual devices while keeping the data secure and private.

In this project, we implemented a decentralized machine learning algorithm using federated learning with a differential privacy feature. The goal was to develop a system that could perform image classification while ensuring data privacy by keeping the data decentralized and secure.

The dataset used for image classification was the Fashion MNIST dataset, which consists of grayscale images of various clothing items such as shirts, dresses, shoes, etc. Each image is labeled with a corresponding class.

To simulate the decentralized environment, we created virtual workers using TensorFlow Federated (TFF) and PySyft packages in Python. These virtual workers acted as independent devices that held and processed the data locally, preventing the need for centralized data storage.
