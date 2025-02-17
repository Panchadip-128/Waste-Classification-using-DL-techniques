# Waste Classification Using Deep Learning Methods
----------------------------------------------------

## Project Overview:
--------------------
1) Data Preparation:
Imported the required libraries.

2) Loaded the dataset.
Split the data into training, validation, and testing sets.

3) Model Development:
Built and evaluated several models:
- ANN (Artificial Neural Network)
- Basic CNN (Convolutional Neural Network)
- VGG16 (Pre-trained model)
- ResNet (Pre-trained model)
- MobileNetV2 (Pre-trained model)
  
Compared their performance to find the best model.

4) Models & Libraries
Models Used:

ANN
Basic CNN
VGG16
ResNet
MobileNetV2
Libraries Needed:

TensorFlow
Matplotlib
OpenCV-Python
NumPy
Random
Shutil

5) Performance Visualizations
Performance graphs are provided for each model:

ANN Model Performance
![ANN_Performance](https://github.com/user-attachments/assets/ad1e13ef-232e-4cc7-b608-9cdbdcccfede)

Basic CNN Model Performance
![CNN_Performance](https://github.com/user-attachments/assets/61c8ee39-90d6-4436-ab78-82fe744e6a3e)

VGG16 Model Performance
![VGG16_Performance](https://github.com/user-attachments/assets/e62c37d8-5a85-45dc-a4ad-ac9e84fbbb69)

ResNet Model Performance
![VGG16_Performance](https://github.com/user-attachments/assets/0eb61838-ac14-4aad-b88a-ed06b9b797ff)

MobileNetV2 Model Performance
![MobileNetV2_Performance](https://github.com/user-attachments/assets/ed2fa25d-56d5-467f-a406-14eb95aca32b)

### **Model Accuracies**

| **Model**        | **Architecture** | **Accuracy on Test Data (%)** |
|------------------|------------------|-------------------------------|
| **Model 1**      | ANN              | 81.73                         |
| **Model 2**      | Basic CNN        | 87.31                         |
| **Model 3**      | VGG16            | 90.65                         |
| **Model 4**      | ResNet           | 76.88                         |
| **Model 5**      | MobileNetV2      | 90.85                         |

6) Conclusion:

ANN: Provided a basic starting point with 81.73% accuracy.
Basic CNN: Improved accuracy to 87.31%.
VGG16: Performed well with 90.65%, showing the power of transfer learning.
ResNet: Had a lower accuracy of 76.88%, possibly due to overfitting.
MobileNetV2: Achieved the best accuracy (90.85%) and is efficient for deployment.
Overall: MobileNetV2 is the best choice for this waste classification task due to its high accuracy and efficiency. 

Future improvements could involve fine-tuning the models further, adding more data augmentation, and experimenting with different hyperparameters.
