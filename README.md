# Plant Disease Classification using CNNs 

Image classification using **Convolutional Neural Networks (CNNs)** has proven to be highly effective in recognizing patterns and diagnosing plant diseases from leaf images. This approach is increasingly applied in both **research settings** and the **agricultural industry**, especially in modern cropping systems.

This project explores and evaluates the performance of different CNN-based approaches to classify plant diseases using the **PlantVillage dataset**.

---

## 📌 Overview

The project is organized into three main parts:

#### 1. **Custom CNN from Scratch**
- Designed and implemented multiple CNN architectures.
- Performed hyperparameter tuning to improve validation accuracy and generalization.
- Selected and presented the **best-performing architecture** based on evaluation results.

#### 2. **Transfer Learning with ResNet50**
- Tested various pre-trained convolutional networks.
- Selected **ResNet50** as the final choice due to its superior classification performance.
- Achieved significant improvement compared to the custom CNN.

#### 3. **Grad-CAM & Model Interpretability**
- Applied **Gradient-weighted Class Activation Mapping (Grad-CAM)**.
- Visualized important regions in images that influenced the model's predictions.
- Enhanced interpretability and trust in the model's decision-making process.


## 📊 Results Summary

- **Custom CNN:** Achieved strong baseline accuracy after tuning.
- **ResNet50 (Transfer Learning):** Outperformed the custom model significantly.
- **Grad-CAM:** Provided clear visual explanations of model focus areas.


## ✨ Acknowledgments

- **PlantVillage Dataset:** [Kaggle](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)
- TensorFlow/Keras documentation
- Google Colab for free GPU resources
