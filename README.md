# Plastic-waste-classification-CNN
A CNN-based deep learning model to classify images of plastic waste into categories, enabling efficient sorting and recycling.

## 📂 Dataset

The dataset used for training the model is **not included** in this repository due to its large size. However, you can access the dataset via the following link:

[Dataset Link](https://www.kaggle.com/datasets/techsash/waste-classification-data)

## Week 1 Progress

### Tasks Completed:
1. **Environment Setup**

2. **Dataset Handling**:
   - Downloaded and unzipped the waste classification dataset.
   - Explored the dataset to understand its structure and visualize sample images.

3. **Data Preprocessing**:
   - Implemented `ImageDataGenerator` to augment and preprocess the images:
     - Rescaling pixel values to `[0, 1]`.
     - Rotation, width/height shift, and zoom augmentation.
