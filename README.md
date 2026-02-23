# Eye Disease Classification using EfficientNet-B2 with SEBlock Attention

This repository features a high-performance Deep Learning solution for classifying retinal images into four diagnostic categories. By combining the **EfficientNet-B2** architecture with a custom **Squeeze-and-Excitation (SE) Block**, the model achieves state-of-the-art accuracy in detecting critical eye conditions.

---

## 🚀 Key Features
* **Backbone:** Pre-trained **EfficientNet-B2** for robust feature extraction.
* **Attention Mechanism:** Integrated **SEBlock** to recalibrate channel-wise features, focusing the model on diseased regions of the retina.
* **High Accuracy:** Achieved a verified test accuracy of **99.53%**.
* **Optimization:** Utilizes **AdamW** and **Early Stopping** to ensure peak performance without overfitting.

---

## 📊 Dataset Classification
The model is trained to identify:
1.  **Cataract**
2.  **Diabetic Retinopathy**
3.  **Glaucoma**
4.  **Normal** (Healthy Retina)



---

## 🛠️ Technical Specs & Training
* **Framework:** PyTorch
* **Input Size:** $224 \times 224$ pixels
* **Augmentation:** Horizontal flips, rotation ($15^{\circ}$), and color jittering.
* **Optimizer:** AdamW (Learning Rate: $1 \times 10^{-4}$)
* **Hardware:** Trained on Google Colab using a **Tesla T4 GPU**.

---

