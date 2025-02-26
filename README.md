# Hand-Sign Language Translation Modeling

In today's society, individuals with hearing impairments face significant communication challenges, especially when interacting with those who do not understand sign language. Traditional methods of communication, such as writing or lip-reading, often fail to capture the nuances and speed of sign language. 

This project is a system designed to recognize and translate text into sign language, as well as sign language into text and speech. Additionally, it provides learning resources for sign language. It aims to enhance communication for individuals with speech and hearing impairments.

## 🎯 Why we made it?
Traditional sign language recognition requires costly sensors and devices. Our approach leverages artificial intelligence to provide an affordable, efficient solution using computer vision and deep learning techniques.

## 🏗️ Phases of Development
1. **Data Collection** - Used the Indian Sign Language dataset from Kaggle with 13,000 images.
2. **Preprocessing** - Images resized to 299x299 pixels and augmented for better training.
3. **Model Training** - Implemented CNN and YOLO models for sign recognition.
4. **Testing** - Evaluated model accuracy and performance on validation datasets.
5. **Deployment** - Integrated the trained model into the "MaunMitra" app for real-world use.

## 🛠️ Techniques Used
- **Convolutional Neural Network (CNN)** - Achieved 98.8% accuracy.
- **YOLOv8 & YOLOv5** - Explored for real-time sign detection.
- **Computer Vision (OpenCV, MediaPipe)** - For image processing.

## 🚀 How to Create the Model?
1. Collect the dataset (Indian Sign Language).
2. Preprocess images by resizing and augmenting.
3. Train using CNN and YOLO models.
4. Optimize accuracy with techniques like learning rate adjustment and data augmentation.

## 🧪 Testing & Deployment
- **Testing**: Validated accuracy using accuracy-loss plots and inference on unseen data.
- **Deployment**: The model is integrated into the "MaunMitra" app for real-time sign
