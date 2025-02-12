# Sea Creature Classification Using EfficientNetB5

### **Project Overview**  
The "Sea Creature Classification Using EfficientNetB5" project focuses on classifying different species of sea creatures using deep learning. It utilizes a dataset of sea animal images and applies EfficientNetB5, a pre-trained convolutional neural network, for image classification. The goal is to develop a robust model that can accurately categorize sea creatures into 23 different classes.

### **Technical Highlights**  
- **Dataset Handling:** The dataset is sourced from Kaggle and preprocessed using TensorFlow and OpenCV. Data augmentation techniques, including rotation, zoom, brightness adjustment, and shifting, are applied to enhance model generalization.  
- **Model Architecture:** EfficientNetB5 serves as the feature extractor, followed by batch normalization, a dense layer with L1/L2 regularization, dropout, and a final softmax classification layer.  
- **Training and Optimization:** The model is trained using Adamax optimizer with categorical cross-entropy loss. The learning process is monitored using validation accuracy and loss metrics.  
- **Evaluation Metrics:** Confusion matrix and classification reports are used for performance assessment, and loss/accuracy trends are plotted for analysis.  

### **Purpose and Applications**  
The project aims to assist in marine biodiversity research, conservation efforts, and automated species identification in oceanographic studies. It can be used in marine life monitoring, underwater exploration, and educational tools for understanding marine ecosystems.

**Installation**  
To set up and run the project, follow these steps:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/BhaveshBhakta/Sea-Creature-Classification-Using-EfficientNetB5.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd Sea-Creature-Classification-Using-EfficientNetB5
   ```
3. **Run the jupyter notebook**:

**Collaboration**  
Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.
