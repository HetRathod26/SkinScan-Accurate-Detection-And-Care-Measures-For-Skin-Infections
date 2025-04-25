![image](https://github.com/user-attachments/assets/85c9615e-533c-47aa-b101-c5756f2a52b4)# **🧬 SkinScan – AI-Powered Skin Disease Detection**
SkinScan is an intelligent web application designed to help users detect and understand common skin conditions like Eczema, Psoriasis, and Melanoma using AI. By simply uploading a skin image, users receive fast, reliable predictions, Ayurvedic care suggestions, and even have the option to book appointments with local dermatologists — all in one seamless platform.
---
## 💡 **Key Features**
**🔍 Skin Disease Detection**
-Upload an image and get instant predictions using a trained Vision Transformer (ViT) model.

-Works on images of different body parts (e.g., face, hands, legs, neck).

-Supports three skin diseases initially: Eczema, Psoriasis, and Melanoma.

![image](https://github.com/user-attachments/assets/36239cf1-0c45-4f0b-8108-453f9fab190f)
![image](https://github.com/user-attachments/assets/61c8ebde-5416-4dad-a566-4b10a19fbb62)


**🧪 Advanced Preprocessing**
-Auto-cropping to focus on infected regions.

-Hair removal to reduce prediction noise.

-Texture and edge analysis to improve detection quality.

**📊 AI Model**
Uses ViT (Vision Transformer) for accurate feature learning.

Custom texture feature maps are fed into the ViT model.

Trained and evaluated on a dataset of 11,000 images.

**🌿 Ayurvedic & Clinical Care Suggestions**
Provides Ayurvedic treatment tips tailored to the detected condition.

Suggests clinical care routines and do’s & don’ts.

![image](https://github.com/user-attachments/assets/25fdd222-27e6-4c20-90e9-6794a23401bb)

**Chat Bot for more Care Measures:**
![image](https://github.com/user-attachments/assets/52de1c71-73aa-4f4d-9389-f934bce3d850)
![image](https://github.com/user-attachments/assets/68643534-bf5e-446a-a3cf-a2e28f685c81)
![image](https://github.com/user-attachments/assets/9be7cd43-6fa4-441a-8277-37258e1d1fce)


**🧭 Location-Based Appointment System**
Detects user’s location to show nearby dermatologists.

Simplifies booking process from within the app.

![image](https://github.com/user-attachments/assets/31691a02-b7a9-42dc-8f8f-984e809d78be)


**🧠 Tech Stack**
**Frontend**: HTML, CSS, JavaScript (React.js planned)

**Backend: **Python (Flask)

**AI/ML:** Vision Transformer (ViT), OpenCV, Scikit-learn

**Tools:** Jupyter Notebook, Google Colab, Firebase (for doctor database)

**Dataset**: 11K labeled skin images with custom preprocessing pipeline

