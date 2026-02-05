**Deepfake Image Detection Using Deep Learning**
**Overview**

Deepfake media has become increasingly realistic due to advances in generative models, posing serious threats to digital trust, privacy, and security. This project presents a deep learning–based system for detecting deepfake images using the EfficientNetV2 architecture, which offers high accuracy with optimized computational efficiency.

The system classifies facial images as Real or Fake by learning subtle visual artifacts and inconsistencies that are difficult to detect using traditional methods.

**Key Features**

Deepfake image classification (Real / Fake)

EfficientNetV2-based deep learning model

High detection accuracy (~94%)

Robust preprocessing and data augmentation

Web-based interface for real-time image verification

Scalable and deployable architecture

**Technology Stack**

Programming Language: Python

Deep Learning Framework: TensorFlow / Keras

Model Architecture: EfficientNetV2

Frontend: HTML, CSS

Backend: Django

**Datasets:**

FaceForensics++

DeepFake Detection Challenge (DFDC)

**System Workflow**

Image upload by the user

Image preprocessing (resize, normalization, face alignment)

Feature extraction using EfficientNetV2

Deepfake classification (Real / Fake)

Result display with confidence score

**Dataset**

The model is trained and evaluated on publicly available datasets containing real and manipulated facial images:

FaceForensics++

DeepFake Detection Challenge (DFDC)

These datasets include multiple manipulation techniques, lighting conditions, and resolutions to ensure strong generalization.

**Model Performance**

Accuracy: ~94.3%

Metrics Used: Accuracy, Precision, Recall, F1-score, Confusion Matrix

Outperforms traditional CNN-based approaches

**Installation & Setup**

# Install dependencies
pip install -r requirements.txt

# Run the Django server
python manage.py runserver

Usage

Open the web application in your browser

Upload a facial image (JPG/PNG)

View the prediction result (Real or Fake) with confidence score

Applications

Digital media verification

Cybersecurity and forensics

Social media content moderation

Journalism and misinformation detection

Future Enhancements

Video deepfake detection

Explainable AI (Grad-CAM visualization)

Mobile application support

Continuous learning with new datasets

**License**

This project is developed for academic and research purposes.

**Output**
**Screen 1: Home Page **
<img width="490" height="373" alt="image" src="https://github.com/user-attachments/assets/eca9b770-6355-40ff-ad64-c14ba4c0556d" />

**Screen 2: Input Page**
<img width="490" height="373" alt="image" src="https://github.com/user-attachments/assets/6ef984fa-57f5-4d3a-8000-10791cc5a1b2" />

**Screen 3: Output Page**
<img width="490" height="373" alt="image" src="https://github.com/user-attachments/assets/f81a9c7f-d99b-477e-8505-f101a0c54ba9" />


