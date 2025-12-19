# financial-fraud-ml-pipeline
Credit card fraud detection using Federated Learning (FedAvg) with machine learning on imbalanced data.
📌 Project Overview

This project implements a credit card fraud detection system using Federated Learning, focusing on privacy-preserving machine learning over imbalanced financial transaction data. Instead of centralizing sensitive data, model training is distributed across multiple clients using the Federated Averaging (FedAvg) algorithm.

The goal is to accurately identify fraudulent transactions while maintaining data privacy and addressing class imbalance.

🚀 Key Features

Federated Learning implementation using FedAvg

Logistic Regression as the base model

Handles highly imbalanced data

Distributed client-side training

Centralized aggregation of model weights

Model evaluation using standard ML metrics

Data visualization and preprocessing

🧠 Federated Learning Approach

The project follows the standard Federated Learning workflow:

Transaction data is split across multiple clients

Each client trains a local model on its private data

Local model weights are sent to a central server

The server aggregates weights using Federated Averaging (FedAvg)

The updated global model is redistributed for evaluation

This approach ensures data privacy, as raw transaction data never leaves the client.

🛠️ Technologies Used

Python

NumPy, Pandas

Scikit-learn

Matplotlib / Seaborn

Federated Averaging (FedAvg)

📊 Dataset

Credit card transaction dataset

Highly imbalanced classes (fraud vs non-fraud)

Preprocessing includes scaling and feature handling

📈 Model Evaluation

The model performance is evaluated using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Special attention is given to recall, as detecting fraudulent transactions is critical.

📂 Project Structure
├── Research_pro.ipynb
├── README.md

🎯 Use Cases

Privacy-preserving financial fraud detection

Distributed machine learning systems

Federated learning research and experimentation

🔮 Future Improvements

Use advanced FL algorithms (FedProx, Secure Aggregation)

Add differential privacy

Experiment with deep learning models

Deploy using FL frameworks like Flower or TensorFlow Federated

👤 Author

Shruti Pathak
