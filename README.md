# Deep-Learning-for-Seismic-Data-in-Ground-Movement-Detection

**📌 Overview**

This project focuses on detecting and classifying ground movements using seismic data and deep learning techniques. The system utilizes geo-phones and a data acquisition system (DAS) to capture ground vibrations, which are then processed and classified using a Convolutional Neural Network (CNN).

The model classifies seismic activity into three categories:

-🚗 Car Movement
-🚶 Human Activity
-🟢 No Movement

**🎯 Objectives**
- Capture seismic signals using geo-phones
- Convert analog signals into digital data using DAS
- Transform signals into spectrograms
- Train a CNN model for classification
- Achieve accurate and efficient ground movement detection

**🛠️ Tech Stack**
. Python
. TensorFlow / Keras
. NumPy & Pandas
. Matplotlib
. Obspy (for seismic data processing)

**📂 Project Workflow**
**1️⃣ Data Collection**
. Geo-phones are placed in the ground to capture vibrations
. Signals are transmitted to the Data Acquisition System (DAS)
. Data includes:
. Human walking activity
. Vehicle movement
. No movement scenarios

**2️⃣ Data Preprocessing**
. Noise filtering
. Signal correction
. Conversion into time-series format
. Transformation into spectrograms

**3️⃣ Model Building (CNN)**
. Convolutional layers for feature extraction
. Pooling layers for dimensionality reduction
. Fully connected layers for classification
. Softmax activation for multi-class output

**4️⃣ Model Training**
. Trained for 13 epochs
. Optimizer: Adam
. Loss Function: Categorical Crossentropy


**5️⃣ Results**
✅ Model Accuracy: 85.5%
Successfully classifies:
. Car
. Human (Run/Walk)
. No Movement


**📊 Sample Dataset**

Images are given below:

![car (36)](https://github.com/user-attachments/assets/e6dd9dbb-d243-4b62-b8fc-aade5c2baf20)
![nm (6)](https://github.com/user-attachments/assets/8b81a97d-e29b-443d-87ba-8782d2c1c652)
![run (6)](https://github.com/user-attachments/assets/8f9bfdee-4f1e-4b23-942c-22fac2930e0d)

**📈 Output Examples**

. Seismogram plots
. Accuracy & Loss graphs
. Classification predictions


**⚠️ Challenges**
. Noisy seismic data
. Feature extraction complexity
. Model generalization

**📄 Project Report**
[Project_Report.pdf](https://github.com/user-attachments/files/26490190/Project_Report.pdf)





