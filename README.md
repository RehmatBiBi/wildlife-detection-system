**Wildlife Detection System
 Overview**
The Wildlife Detection System is a mobile application designed to detect farm and harmful animals using images and videos. The application uses AI and deep learning models to identify animals from camera input and generates alerts for harmful animals.
This project is aimed at improving safety by alerting individuals to potential threats in wildlife. It will be implemented on a mobile app, which ensures accessibility even in offline environments.
**Features**
•	Animal Detection: Detects whether an animal is a farm animal or a harmful animal.
•	Real-time Alerts: Generates an alert if a harmful animal is detected.
•	Image/Video Processing: Uses deep learning to analyze image/video inputs for animal recognition.
•	Mobile Platform: Designed for offline accessibility, ensuring it works even without an internet connection.
**Technologies Used**
**•	Frontend:** React Native (Expo and VS Code for development)
**•	Backend:** Google Colab for model training
**•	AI/ML Frameworks:** TensorFlow, PyTorch (for deep learning models)
**•	Cloud Storage:** Google Cloud for storing datasets and model outputs
**•	Deep Learning Models:** Trained models for object detection to identify farm and harmful animals
**Installation Instructions**
**1. Clone the repository:**
   git clone https://github.com/RehmatBiBi/wildlife-detection-system.git
**Install dependencies (React Native/Expo):**
npm install
**Start the app:**
expo start
**Usage**
•	Launch the app on your mobile device.
•	Use the camera to capture images or videos of animals.
•	The app will analyze the input and display an alert if a harmful animal is detected.
**•	Note:** You can use the Expo Go app on your mobile device to scan the QR code generated by the Expo development server for testing, or use an emulator for local testing.
**Dataset**
The dataset used for training the model contains approximately 3940 images. The images have been processed to resize, normalize, and augment for model training. The project is now working on completing the video dataset for further training.
**Current Status**
The project is currently in the testing and proof-of-concept phase, with image processing completed. The next steps include:
•	Finalizing and labeling the video dataset.
•	Dataset splitting for the video data.
•	Model training for both images and videos.
**Future Work**
•	Model optimization for real-time detection.
•	Integration with specific camera hardware for deployment.
•	Enhancement of the app’s user interface and experience.
**Contributing**
We welcome contributions! Please feel free to open issues or submit pull requests for improvements.
**License**
This project is licensed under the MIT License - see the LICENSE file for details.
**Acknowledgments**
•	Special thanks to Google Colab for providing an easy-to-use platform for model training.
•	Thanks to the open-source community for providing valuable tools and frameworks.

