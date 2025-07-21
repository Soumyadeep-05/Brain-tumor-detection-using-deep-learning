# Brain-tumor-detection-using-deep-learning
This project uses deep learning (VAGG Model) to detect brain tumors from MRI images, assisting early diagnosis and reducing manual errors. The system classifies MRI scans with high accuracy, supports healthcare workflows, and can be deployed as a web or mobile tool for real-time analysis.
Brain Tumor Detection using Deep Learning

**🔍 Overview:**

Brain tumors can be life-threatening if not diagnosed in time. Manual diagnosis from MRI scans is prone to human error and often time-consuming. To tackle this, we developed an AI-powered tool that can automatically identify and classify brain tumors with high reliability using deep learning techniques.

This project leverages a custom CNN architecture (VAGG) trained on MRI datasets, incorporating key steps such as data preprocessing, augmentation, and evaluation metrics for robust classification performance.

**✨ Features:**

VAGG-based CNN model for accurate brain tumor classification.

Data preprocessing and augmentation for better generalization.

Model evaluation using:

Accuracy score

Confusion matrix

Grad-CAM (visual explanation of predictions)

🌐 Ready for deployment as a web or mobile-based diagnostic tool.

🏷️ Extendable for multi-class tumor detection (e.g., glioma, meningioma, pituitary tumors).

**🧪 Tech Stack:**

Programming Language: Python

Libraries/Frameworks:

TensorFlow / Keras

NumPy

OpenCV

Matplotlib

**📊 Results:**

The model achieved high classification accuracy during evaluation, with Grad-CAM visualizations confirming that the model focuses on the correct tumor regions in the MRI scans.

**🚀 Future Improvements:**

Integration with real-time MRI scanners via APIs.

Multi-class and subtype tumor classification.

Deployment using Flask/Django (Web) or TensorFlow Lite (Mobile).

Integration with electronic medical records (EMR) systems.

**👨‍💻 Contributors:**

This project was developed by:

Soumyadeep Roy

Aryan Walia

Lav Singh
