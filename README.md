# Intelligent-ANPR-System-YOLOv8-OCR
​End-to-End License Plate Detection &amp; OCR Pipeline using YOLOv8, EasyOCR, and Grad-CAM for Explainable AI.

​🚗 Automatic Number Plate Recognition (ANPR) System
​نظام التعرف الآلي على لوحات السيارات باستخدام Deep Learning

​📝 Project Overview | 
نبذة عن المشروع

​English:

This project is a complete end-to-end pipeline for detecting and recognizing vehicle license plates. It combines the power of YOLOv8 for real-time object detection and EasyOCR for text extraction, with advanced image preprocessing to ensure high accuracy.

​بالعربية:

هذا المشروع عبارة عن نظام متكامل (End-to-End Pipeline) لاكتشاف والتعرف على لوحات تراخيص المركبات. يجمع المشروع بين قوة موديل YOLOv8 للاكتشاف الفوري للأجسام، ومكتبة EasyOCR لاستخراج النصوص، مع تقنيات متقدمة لمعالجة الصور لضمان أعلى دقة ممكنة.

​🚀 Key Features | 
المميزات الرئيسية

​Dual-Stage Pipeline: Detection followed by Recognition.

​Custom YOLOv8 Model: Trained specifically to locate license plates in various conditions.

​Advanced Preprocessing: Includes Grayscale, Resizing, and Otsu’s Thresholding to boost OCR accuracy.

​Model Explainability (Grad-CAM): Visualizing where the model focuses its attention during detection.

​Performance Analysis: Visualized confidence scores and error analysis using Histograms.

​🛠️ Built With | 
الأدوات المستخدمة

​Python | YOLOv8 (Ultralytics) | EasyOCR | OpenCV | Matplotlib & Seaborn

​📉 Project Stages | مراحل العمل (10-Step Pipeline)

​Data Collection & Annotation: gathering and labeling plates in YOLO format.

​Model Training: Training YOLOv8 on custom dataset.

​Plate Detection: Locating the bounding box of the plate.

​Grad-CAM Visualization: Explaining model decisions.

​Cropping: Extracting the plate region.

​Image Preprocessing: Grayscale, Resizing, and Thresholding.

​OCR Execution: Passing the "cleaned" plate to EasyOCR.

​Post-processing: Cleaning the predicted text.

​Accuracy Analysis: Generating confidence distribution histograms.

​Inference: Testing the full system on random unseen images.

​📊 Results & Performance | 
النتائج والأداء

​English:

After applying advanced preprocessing techniques, the system achieved a 76.3% success rate across the entire dataset, with a high confidence score of 90%+ on clear images.
​بالعربية:

بعد تطبيق تقنيات المعالجة المتقدمة، حقق النظام نسبة نجاح 76.3% على كامل مجموعة البيانات، مع درجة ثقة تتجاوز 90% في الصور الواضحة


## 📊 Model Performance & Visual Results | نتائج الأداء والمعاينة البصرية

### 1️⃣ Evaluation Metrics (التقييم الرقمي)
Below are the training results and confusion matrix, demonstrating the model's high precision in detecting license plates.

<p align="center">
  <img src="results.png" width="45%" alt="Training Results" />
  <img src="confusion_matrix.png" width="45%" alt="Confusion Matrix" />
</p>

---

### 2️⃣ Detection & OCR In Action (المعاينة العملية)
Real-world examples showing the successful localization of the plate and text extraction.

<p align="center">
  <img src="val_batch0_labels.jpg" width="45%" alt="Ground Truth" />
  <img src="val_batch0_pred.jpg" width="45%" alt="Model Predictions" />
</p>

---

### 3️⃣ Model Interpretation with Grad-CAM (تفسير قرارات الموديل)
Using Grad-CAM to ensure the model focuses on the plate features for decision making.

<p align="center">
  <img src="gradcam_result.png" width="60%" alt="Grad-CAM Heatmap" />
</p>

​👨‍💻 Author | 
صاحب المشروع

​Mohamed Belal

Data Science & AI Professional Diploma Graduate

Specialized in Computer Vision & Deep Learning
