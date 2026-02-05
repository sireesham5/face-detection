# Real-Time Face, Eye & Smile Detection System 🚀

A high-performance Computer Vision pipeline built with **OpenCV** to detect and track facial landmarks in real-time. This project demonstrates the implementation of **Haar Cascade Classifiers** and optimized image processing for live biometric feedback.

## 📌 Project Overview
This system processes live video streams to identify and localize:
- **Face Detection:** Real-time tracking of human faces using multi-scale detection.
- **Eye Localization:** Precise tracking of eyes within the face region.
- **Expression Analysis:** Detection of smiles using intensity-based classification.

## 🛠️ Technical Stack
- **Language:** Python 3.12 (Anaconda Environment)
- **Core Library:** OpenCV (`cv2`)
- **Data Handling:** NumPy
- **Algorithm:** Haar Cascade Classifiers

## 📂 Project Structure
- `detect.py`: Main execution script for live camera feed.
- `haarcascades/`: Folder containing XML files for pre-trained models.
- `README.md`: Project documentation and setup guide.
- `.gitignore`: Configured to exclude `__pycache__` and local system files.

## 🚀 Getting Started
1. **Initialize Environment:**
   ```bash
   conda create -n vision_env python=3.12
   conda activate vision_env
   pip install opencv-python

2. python detect.py

Note: Ensure your webcam is connected. Press 'q' to quit the stream.




👤 Author

MIDDE SIREESHA


