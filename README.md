# Human Detection in Disaster Scenarios Using UAV Images

## About
In disaster scenarios such as earthquakes, floods, fires, and building collapses, rapid human detection is critical for efficient rescue operations. This project leverages UAV technology combined with advanced deep learning models to detect humans in real-time from aerial imagery. The system employs the YOLOv11 object detection architecture, fine-tuned using the C2A dataset, to accurately identify humans even in challenging environments with debris, smoke, or low visibility.

## Features
- **Real-Time Detection**: Quick and efficient detection of humans in disaster scenarios.
- **Pose-Aware Recognition**: Detects humans in diverse postures such as sitting, lying, or kneeling.
- **Multi-Scale Detection**: Identifies humans at both close and long ranges.
- **Highly Scalable**: Can be deployed on edge devices for real-time processing.
- **Improved Accuracy**: Enhanced detection precision in cluttered and complex environments using the C2A dataset.

## Requirements
- **Operating System**: 64-bit OS (Windows 10/11 or Ubuntu) recommended for compatibility with deep learning libraries.
- **Programming Language**: Python 3.7 or later.
- **Deep Learning Frameworks**: TensorFlow and PyTorch for training and deploying YOLOv11 models.
- **Image Processing Libraries**: OpenCV for preprocessing UAV images.
- **Development Environment**: JupyterLab for training, evaluation, and model visualization.
- **Additional Dependencies**:
  - scikit-learn
  - TensorFlow GPU (for accelerated training)
  - OpenCV
  - matplotlib

## System Architecture
<!-- Add your architecture diagram image to the repository and update the link below -->
![System Architecture](https://github.com/<<yourusername>>/UAV-Human-Detection-System/assets/yourimagepath)

## Output

#### Output 1 - Aerial Image with Human Detection
![image](https://github.com/user-attachments/assets/0b2a130e-408a-483e-b0a7-602006f5da02)


#### Output 2 - Detection Under Low Visibility
![image](https://github.com/user-attachments/assets/e6411cf7-e3f0-45aa-856d-4e86dd26be74)


Detection Accuracy: 90%  
Precision: 83%  
Recall: 82%

## Results and Impact
The UAV-based human detection system significantly improves the speed and accuracy of identifying survivors in disaster-affected areas. It reduces the dependency on manual ground-based searches and enables real-time alerts to rescue teams, ensuring timely and effective response.

The integration of cutting-edge computer vision and UAV technologies highlights the potential of AI in humanitarian efforts, contributing to life-saving operations and disaster management.

## Articles Published / References
1. Yibo Zhao, Chao Huang, and Hailong Huang, *“UAV Aerial Surveillance for Search and Rescue,”* Journal of Emergency Technologies, 2023.
2. Pei-Fen Tsai, Chia-Hung Liao, and Shyan-Ming Yuan, *“Thermal Imaging Combined with Deep Learning for Low-Visibility Detection,”* Advances in AI Research, 2022.



