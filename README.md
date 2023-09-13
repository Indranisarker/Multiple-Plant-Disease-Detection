# Plant Classification and Disease Detection System

## Overview

This project employs a total of 5 Artificial Neural Network (ANN) models to classify plants and identify diseases. To enhance model performance, we applied transfer learning using the pre-trained VGG16 model. The primary ANN model was initially trained with 8000 plant leaf images for plant classification, while the remaining Sub-ANN models were fine-tuned for disease detection in each plant species. Image augmentation was performed to address data scarcity issues in some classes.

## Key Steps

1. **Training ANN Models**

   - Utilized pre-trained VGG16 model weights as a starting point.
   - Trained the primary ANN model on 8000 plant leaf images for plant species classification.

2. **Sub-ANN Models for Disease Detection**

   - Developed Sub-ANN models dedicated to detecting diseases in each plant species.
   - Fine-tuned these models to achieve accurate disease identification.

3. **Image Augmentation**

   - Applied image augmentation techniques to augment data for classes with limited samples.
   
4. **User Interface**

   - Created a user-friendly web interface enabling users to upload images of four plant leaf varieties.
   - Based on the provided images, the interface determines the plant species and assesses its health status.

## Technologies

- **Programming Language**: Python for model development.
- **Deep Learning Frameworks**: TensorFlow or PyTorch for training ANN models.
- **Pre-trained Model**: VGG16 for transfer learning.
- **Web Development**: HTML, CSS, and JavaScript for building the user interface.
- **Data Augmentation**: Techniques like rotation, scaling, and flipping for data augmentation.

## Conclusion

This Plant Classification and Disease Detection System leverages ANN models, image augmentation, and user-friendly interfaces to accurately classify plant species and identify diseases from leaf images. By facilitating early disease detection and plant health assessment, this project contributes to plant management and agricultural practices.

