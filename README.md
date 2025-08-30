# Building Image Classification with ViT

Street view buildings are classified using different models: **Basic CNN**, **ResNet**, and **Vision Transformer (ViT)**. Finally, the ViT model is fine-tuned to improve accuracy.

**Dataset Details:**

* Number of training samples: 2,264
* Number of validation samples: 252
* Number of test samples: 478

## Model Performance

1. **Basic CNN (Grayscale Images)**

   * Accuracy: 42.86%
   * Observations: The model is **overfitting**.

2. **Basic CNN with Augmentation, Dropout, and Batch Normalization**

   * Accuracy: 43.65%
   * Observations: The model is **underfitting**.

Class imbalance is noticed in the dataset. With augmentation, the class imbalance is removed.

3. **ResNet50 (RGB Images) with Augmentation**

   * Accuracy: 56.35%
   * Observations: The model is **overfitting**.

4. **ViT Base Model**

   * Accuracy: 66.47%
   * Observations: The model is **overfitting**.

5. **Fine-tuned ViT Model (with 0.5 Dropout)**

   * Accuracy: 85.60%
   * Observations: **Overfitting reduced significantly**.

---

