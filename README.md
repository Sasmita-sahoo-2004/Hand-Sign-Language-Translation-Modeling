# Hand-Sign Language Translation Modeling

In today's society, individuals with hearing impairments face significant communication challenges, especially when interacting with those who do not understand sign language. Traditional methods of communication, such as writing or lip-reading, often fail to capture the nuances and speed of sign language. 

This project is a system designed to recognize and translate text into sign language, as well as sign language into text and speech. Additionally, it provides learning resources for sign language. It aims to enhance communication for individuals with speech and hearing impairments.

##  Phases of Development
1. **Data Collection** - Used the Indian Sign Language dataset from Kaggle with 13,000 images.
2. **Preprocessing** - Images resized to 299x299 pixels and augmented for better training.
3. **Model Training** - Implemented CNN and YOLO models for sign recognition.
4. **Testing** - Evaluated model accuracy and performance on validation datasets.
5. **Deployment** - Integrated the trained model into the "MaunMitra" app for real-world use.

## Techniques Used
- **Convolutional Neural Network (CNN)** - Achieved 98.8% accuracy.
- **YOLOv8 & YOLOv5** - Explored for real-time sign detection.
- **Computer Vision (OpenCV, MediaPipe)** - For image processing.

## Methodology
1. Collect the dataset (Indian Sign Language).
   
   ![Screenshot 2024-04-21 171200](https://github.com/user-attachments/assets/1934bc67-5b0e-4068-ba7d-c6cdfbf51708)

2. Preprocess images by resizing and augmenting.
 
   ![image](https://github.com/user-attachments/assets/1cf1fab6-b336-4a9f-b976-226e4f24be9a)

3. Train using CNN and YOLO models.
 
   ![image](https://github.com/user-attachments/assets/b39456c7-efc4-4958-b29f-3f89aa7fff3e)

4. Optimize accuracy with techniques like learning rate adjustment and data augmentation.
   
   ![image](https://github.com/user-attachments/assets/5fe70649-94aa-49d7-8766-b2d6bcaa9c0f)
   
   ![image](https://github.com/user-attachments/assets/2e38d912-7b99-46ab-81a4-1fc4babc7f96)



## 🧪 Testing & Deployment
- **Testing**
  
  ![Screenshot 2024-04-22 162454](https://github.com/user-attachments/assets/392bb146-1aec-42e1-89a2-55e184975dae)

  ![Screenshot 2024-04-22 200837](https://github.com/user-attachments/assets/5655cf77-0824-4887-a783-595809ddc466)

  

- **Deployment**: The model is integrated into the "MaunMitra" app for real-time sign

<p align="center">
  <img src="https://github.com/user-attachments/assets/ceab8d5d-3960-41c8-8c2b-8ad9566cdb67" width="24%" />
  <img src="https://github.com/user-attachments/assets/6de44240-ace5-4ea2-852c-4d4a943ad21e" width="24%" />
  <img src="https://github.com/user-attachments/assets/bec30064-c282-4c03-803d-4752d9dcc995" width="24%" />
  <img src="https://github.com/user-attachments/assets/36622a33-0481-4ee3-b6df-06081d3f0982" width = "24%" />

</p>

  
