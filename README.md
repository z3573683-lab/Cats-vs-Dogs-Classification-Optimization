# Cats-vs-Dogs-Classification-Optimization
A high-performance custom CNN for Cats vs Dogs classification, achieving 94.81% accuracy with model interpretability using Grad-CAM

# 🐾 Cats vs Dogs Classification from Scratch: The Optimization Journey (95% Accuracy)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)](https://www.tensorflow.org/)
[![Accuracy](https://img.shields.io/badge/Accuracy-94.81%25-green)](https://github.com/)

---

## 📝 Project Overview | نظرة عامة على المشروع

### **English**
This project focuses on building a robust Convolutional Neural Network (CNN) from scratch to classify images of cats and dogs. The main goal was to demonstrate the power of **Model Optimization** and **Explainable AI (XAI)**. I managed to push the model's performance from an initial **83%** baseline to a highly reliable **94.81%** accuracy without using Transfer Learning.

### **بالعربي**
يركز هذا المشروع على بناء شبكة عصبية تلافيفية (CNN) قوية من الصفر لتصنيف صور القطط والكلاب. الهدف الأساسي كان إثبات قوة **تحسين النماذج (Optimization)** و **الذكاء الاصطناعي القابل للتفسير (XAI)**. نجحت في تطوير أداء النموذج من دقة مبدئية **83%** إلى دقة عالية تصل إلى **94.81%** دون الاعتماد على نماذج جاهزة (Transfer Learning).

---

## 🚀 Optimization Strategy | استراتيجية التحسين

To achieve the 12% accuracy boost, the following techniques were implemented:
لتحقيق قفزة بنسبة 12% في الدقة، تم تنفيذ التقنيات التالية:

1.  **Architecture Tuning:** Added **Batch Normalization** for faster convergence and **Dropout** layers (0.5) to combat overfitting.
2.  **Advanced Data Augmentation:** Implemented a real-time augmentation pipeline (rotation, zoom, horizontal flips) using `ImageDataGenerator`.
3.  **Hyperparameter Optimization:** Switched to the **Adam** optimizer with a fine-tuned learning rate.

---

## 📊 Evaluation Metrics | مقاييس الأداء

The model was evaluated on a test set of **2,023 unseen images**:

* **Final Test Accuracy:** 94.81%.
* **Final Test Loss:** 0.1403.
* **Precision/Recall:** Balanced scores (~0.95) for both classes.

| Metric | Score |
| :--- | :--- |
| **Accuracy** | 94.81% |
| **F1-Score (Cats)** | 0.95 |
| **F1-Score (Dogs)** | 0.95 |

---

## 🔍 Explainable AI (Grad-CAM) | تفسير النموذج

### **English**
Beyond accuracy, I integrated **Grad-CAM** (Gradient-weighted Class Activation Mapping) to visualize where the model looks. This ensures the model identifies specific features like ears, eyes, and fur textures.

### **بالعربي**
بعيداً عن الأرقام، قمت بدمج تقنية **Grad-CAM** لرؤية المناطق التي يركز عليها النموذج لاتخاذ قراره. هذا يضمن أن الموديل يتعرف على ملامح حقيقية مثل الأذنين، العينين، وفرو الحيوان.

---

## 🛠️ Tech Stack | الأدوات المستخدمة

* **Language:** Python.
* **Frameworks:** TensorFlow / Keras.
* **Libraries:** NumPy, Matplotlib, OpenCV, Scikit-learn.
* **Platform:** Google Colab.

---

## 📈 Visualizations | الرسوم البيانية

*(Tip: Upload your screenshots to your GitHub repo and link them here)*
* **Training History:** Stable curves for accuracy and loss.
* **Confusion Matrix:** High true positive/negative rates.
* **Grad-CAM Heatmaps:** Visual proof of model intelligence.

---

## 📈 Visualizations & Results | النتائج والرسوم البيانية

### 1. Model Training History (Accuracy & Loss)
![Training History](graph_accuracy_and_Loss.png)

**Description**

These learning curves demonstrate the stability and performance of the CNN model over 10 epochs.
​**Accuracy Curve:** Shows a consistent upward trend for both training and validation accuracy, peaking at ~95%, with no significant gap, indicating a well-generalized model.
**Loss Curve:** Displays a smooth decline in both training and validation loss, confirming that the model effectively minimized errors without suffering from overfitting.

​العربية:

​توضح هذه المنحنيات البيانية استقرار وأداء نموذج الـ CNN خلال 10 دورات تدريبية (Epochs):
**​منحنى الدقة (Accuracy):** يظهر اتجاهاً تصاعدياً مستمراً لكل من دقة التدريب والاختبار، حيث وصلت الدقة إلى حوالي 95% مع تقارب واضح بين المنحنيين، مما يدل على قدرة النموذج على التعميم بشكل ممتاز.
**​منحنى الخسارة (Loss):** يظهر انخفاضاً تدريجياً وسلساً في قيم الخسارة، مما يؤكد نجاح النموذج في تقليل الأخطاء بكفاءة عالية دون الوقوع في مشكلة الـ Overfitting

### 2. Confusion Matrix
![Confusion Matrix](Confution_Matrix.png)

**Description**

This Confusion Matrix shows the high performance of the model on the test set. Out of 2,000+ images, the model correctly identified 972 Dogs and 946 Cats, achieving a balanced and high accuracy across both classes.

​العربية:

​توضح مصفوفة الارتباك (Confusion Matrix) الأداء العالي للنموذج على بيانات الاختبار. من بين أكثر من 2000 صورة، نجح النموذج في تحديد 972 كلب و946 قطة بشكل صحيح، مما يعكس دقة متوازنة وقوية لكلا الفئتين

### 3. Classification Report
![Classification Report](Classification_Report.png)

### 4. Final Evaluation Results
![Final Evaluation](model_Evaluation.png)

### 5. Explainable AI (Grad-CAM Visualizations)
| Sample 1 | Sample 2 | Sample 3 |
| :---: | :---: | :---: |
| ![Grad-CAM 1](Grade_CAM_1.png) | ![Grad-CAM 2](Grade_CAM_2.png) | ![Grad-CAM 3](Grade_CAM_3.png) |

---

## 👨‍💻 Author
**Mohamed Belal**
* Data Science & AI Diploma (AMIT Learning)
![LinkedIn Profile](https://www.linkedin.com/in/mohamed-belal-3591b03bb?utm_source=share_via&utm_content=profile&utm_medium=member_android)

* 
*
