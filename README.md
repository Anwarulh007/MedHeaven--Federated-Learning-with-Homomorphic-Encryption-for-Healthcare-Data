# MedHeaven- Federated Learning with Homomorphic Encryption for Healthcare Data

This project demonstrates a privacy-preserving federated learning system using **TensorFlow Federated (TFF)** and **homomorphic encryption** to secure patient data in collaborative healthcare environments. The project leverages Google Drive as the global server, securely managing model updates and ensuring that no private data is exposed during training.

<p align="center"> 
 <img src="https://github.com/Anwarulh007/MedHeaven--Federated-Learning-with-Homomorphic-Encryption-for-Healthcare-Data/blob/main/WhatsApp%20Image%202024-10-24%20at%2012.46.40.jpeg" alt="Medheaven" style="width: auto; height: 350px;"/> 
</p>

## 📜 **Project Description**
In this project, we work with a healthcare dataset to predict patient readmission rates using federated learning. To enhance privacy, we apply **homomorphic encryption** to encrypt the model weights during the federated learning process. This ensures that sensitive information, such as patient details, remains secure and only the encrypted model updates are shared.

<p align="center"> 
 <img src="https://github.com/Anwarulh007/MedHeaven--Federated-Learning-with-Homomorphic-Encryption-for-Healthcare-Data/blob/main/FL%20Final.jpg" alt="Medheaven" style="width: auto; height: 350px;"/> 
</p>

### Key Features:
- **Federated Learning**: Train machine learning models across distributed datasets without transferring sensitive data to a central server.
- **Homomorphic Encryption**: Securely encrypt model weights, enabling computations on encrypted data and preserving privacy throughout the learning process.
- **Google Drive Integration**: Google Drive is used as a global server to store encrypted model updates, ensuring easy access and collaboration.
- **Healthcare Dataset**: Utilizes hospital data while anonymizing patient identifiers to maintain privacy.

## ⚙️ **Technologies and Libraries**
- **TensorFlow** & **TensorFlow Federated**: For building and training the federated learning models.
- **PySEAL**: For implementing homomorphic encryption.
- **Google Drive API**: To manage global server functionality and save model updates.
- **Scikit-learn**: For data preprocessing and splitting.
- **Pandas**: For handling and cleaning the dataset.

## Flowchart

<p align="center"> 
 <img src="https://github.com/Anwarulh007/MedHeaven--Federated-Learning-with-Homomorphic-Encryption-for-Healthcare-Data/blob/main/Flowchart%20Final.jpg" alt="Flowchart" style="width: auto; height: 700px;"/> 
</p>

## 🚀 **Project Workflow**
1. **Authentication**: Set up Google Drive as a global server to store model updates securely.
2. **Data Preprocessing**: Clean and preprocess healthcare data, applying encoding and standardization techniques.
3. **Federated Learning**: Distribute the training process across multiple clients (e.g., hospitals), preserving data privacy.
4. **Homomorphic Encryption**: Encrypt model weights using **PySEAL** and securely transfer updates without exposing sensitive information.
5. **Federated Averaging**: Aggregate encrypted updates from different clients on the global server (Google Drive) and perform federated learning.
6. **Validation**: Compare encrypted and decrypted model weights to ensure accuracy and privacy preservation.

## 🚀 **Project Workflow Diagram**
<img src="https://github.com/Anwarulh007/MedHeaven--Federated-Learning-with-Homomorphic-Encryption-for-Healthcare-Data/blob/main/Presentation1%20(1).jpg" width = "1000">

## 🔐 **Privacy Preservation**
This project is designed to ensure privacy at every step. By using **homomorphic encryption**, we maintain the confidentiality of model weights, and by using **federated learning**, no private data leaves the local environment. The privacy measure function checks for any discrepancies between the original and decrypted weights to guarantee privacy.

## 🖥️ **How to Run**
1. Clone this repository.
   ```bash
   git clone https://github.com/Anwarulh007/MedHeaven--Federated-Learning-with-Homomorphic-Encryption-for-Healthcare-Data
2. Install the required packages:
pip install -r requirements.txt
3. Upload the necessary dataset (e.g., johns_hospital_data.csv) to your Colab environment.
4. Run the Anwarul_TFF.pynb script to start federated learning with encrypted weights.
## 📊 Dataset
The dataset used in this project consists of anonymized patient information from hospitals, focusing on features relevant to readmission predictions. Columns such as patient name, doctor name, and admission dates have been removed to enhance privacy.

<img src="https://github.com/Anwarulh007/Medheaven/blob/main/dataset%20pic.jpg" alt="Dataset" width = "1000">

## Output
<img src="https://github.com/Anwarulh007/Medheaven/blob/main/output%20of%20tff.jpg" alt="Dataset" width = "1000">

## ✨ Key Algorithms
**Federated Averaging**
: A method to average model updates from multiple clients.

<p align="center"> 
 <img src="https://github.com/Anwarulh007/MedHeaven--Federated-Learning-with-Homomorphic-Encryption-for-Healthcare-Data/blob/main/Federated%20Averaging.jpg" alt="Medheaven" style="width: auto; height: 100px;"/> 
</p>


**Homomorphic Encryption**
: Using this encryption model from TenSEAL to encrypt model parameters.

<p align="center"> 
 <img src="https://github.com/Anwarulh007/MedHeaven--Federated-Learning-with-Homomorphic-Encryption-for-Healthcare-Data/blob/main/Homomorphic%20Encryption.jpg" alt="Medheaven" style="width: auto; height: 200px;"/> 
</p>

## 🌐 Contributors
Anwarul - Project Lead and Developer

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

## Made with 🤍 by Anwarul Haque
