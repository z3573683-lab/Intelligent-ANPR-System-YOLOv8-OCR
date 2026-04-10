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


### 🔍 Project Results and Visualizations

1. **End-to-End Inference Example**

![End-to-End Inference Example](End_to_End_Inference_Example.jpg)

2. **License Plate Detection with Grad-CAM**

![License Plate Detection with Grad-CAM](License_Plate_Detection_with_GradCAM.jpg)

3. **Validation Batch Labels Sample**

![Validation Batch Labels Sample](Validation_Batch_Labels_Sample.jpg)

4. **OCR Extraction Results Sample**

![OCR Extraction Results Sample](OCR_Extraction_Results_Sample.jpg)

---

### 📈 Metrics and Analysis Curves

5. **Model Training Summary Metrics**

![Model Training Summary Metrics](Model_Training_Summary_Metrics.jpg)

6. **Overall System Performance Metrics**

![Overall System Performance Metrics](Overall_System_Performance_Metrics.jpg)

7. **Confusion Matrix Precision**

![Confusion Matrix Precision](Confusion_Matrix_Precision.jpg)

8. **Precision Confidence Curve**

![Precision Confidence Curve](Precision_Confidence_Curve.jpg)

​👨‍💻 Author | 
صاحب المشروع

​Mohamed Belal

Data Science & AI Professional Diploma Graduate

Specialized in Computer Vision & Deep Learning
