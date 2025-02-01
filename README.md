# Plastic-waste-classification-CNN
A CNN-based deep learning model to classify images of plastic waste into categories, enabling efficient sorting and recycling.

## **🚀 Project Overview**  
This project leverages a **Convolutional Neural Network (CNN)** to classify waste into different categories, enabling automated waste management and efficient recycling. The model is trained on a dataset containing labeled images of various waste types.  


## **📂 Dataset Details**  
- **Source:** [Dataset Link](https://www.kaggle.com/datasets/techsash/waste-classification-data)
- **Categories:** Organic, Recyclable, Non-Recyclable, etc.  
- **Preprocessing:**  
  - Resized to **128x128 pixels** for uniformity.  
  - Pixel values **normalized** to [0,1] for faster convergence.  
  - **Data Augmentation:** Rotation, width/height shifts, and zoom to enhance model generalization.  


# **📝 Weekly Progress Report**  

## **✅ Week 1 Progress**  
### **🔹 Environment Setup & Dataset Handling**  
✔️ Set up a deep learning environment with TensorFlow/Keras.  
✔️ Downloaded and unzipped the **waste classification dataset**.  
✔️ Explored the dataset to understand its structure and **visualized sample images**.  

### **🔹 Data Preprocessing**  
✔️ Implemented **ImageDataGenerator** to preprocess and augment images:  
   - Rescaled pixel values to **[0,1]**.  
   - Applied **rotation, width/height shift, and zoom augmentation** for better generalization.  


## **✅ Week 2 Progress**  
### **🔹 Model Architecture Design**  
✔️ Defined a **CNN model** with:  
   - **Conv2D layers** for feature extraction.  
   - **MaxPooling layers** to reduce dimensionality.  
   - **Dropout layers** to prevent overfitting.  
   - **Dense layers** for classification.  
   - **Softmax activation** for multi-class classification.  


### **🔹 Model Compilation & Training**  
✔️ Compiled the model using **Adam optimizer** and **Categorical Crossentropy loss**.  
✔️ Trained the model for **25 epochs** with **early stopping** to prevent overfitting.  


### **🔹 Model Evaluation**  
✔️ Evaluated model performance on the **validation dataset**.  
✔️ Plotted **training & validation accuracy/loss curves**.  


### **🔹 Performance Metrics Computation**  
✔️ Computed **Precision, Recall, and F1-score** to analyze classification performance.  

### **✅ Key Learnings & Next Steps**  
✔️ Fine-tuned **CNN layers and hyperparameters** for better accuracy.  
✔️ Addressed **overfitting risks** using **dropout layers and early stopping**.  
✔️ Next focus: **Testing, Optimization, and Deployment Strategies**.  

## **📊 Model Performance**  
✔️ **Accuracy:** %  
✔️ **Loss:** %  
✔️ **Evaluation Metrics:** Precision, Recall, F1-score  

## **📌 Future Enhancements**  
✅ **Use Transfer Learning** (MobileNet, ResNet) to improve accuracy.  
✅ **Deploy as a Web App** using Flask or TensorFlow.js.  
✅ **Optimize with Hyperparameter Tuning** for better performance.  


### **🔹 Summary of the Project**  
This **CNN-based waste classification model** automates the process of identifying waste categories using deep learning. The workflow includes:  

1️⃣ **Dataset Preparation & Preprocessing**  
2️⃣ **CNN Model Design & Training**  
3️⃣ **Evaluation & Performance Metrics**  
4️⃣ **Future Deployment & Enhancements**  

🚀 **This project serves as a foundation for AI-driven waste classification and sustainable waste management.**
