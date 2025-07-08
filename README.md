## Real-Time-SignL-Recognition-Using-LSTM-Based-Action-Recognition-In-Video-Sequences
This project implements a real-time sign language recognition system that uses an LSTM-based neural network architecture for dynamic gesture recognition. By extracting keypoints from video input and modeling temporal dependencies, the system classifies hand gestures corresponding to sign language in real-time.

#### Key Features
- Real-time recognition of American Sign Language (ASL) gestures
- LSTM-based sequential modeling to handle temporal dependencies
- Pose and hand landmark detection using MediaPipe
- Modular pipeline for dataset creation, model training, and inference
- Scalable and extensible architecture for supporting additional signs and languages

#### Technologies Used
- Programming Language: Python
- Deep Learning Framework: TensorFlow / Keras
- Computer Vision: OpenCV, MediaPipe
- Model Type: LSTM (Long Short-Term Memory)
- Others: NumPy, Pandas, Matplotlib, Scikit-learn

#### How to Run
1. Clone the Repository
$git clone https://github.com/your-username/your-repo-name.git
$cd your-repo-name
2. Install Dependencies $pip install -r requirements.txt
3. Run the Application $python run_real_time.py
4. Usage Notes,
   - Ensure your webcam is connected and accessible.
   - Perform a trained gesture in front of the camera.
   - Predictions will appear in real time on the video feed.

#### Output
The system captures real-time sign language gestures from webcam input, detects keypoints using MediaPipe, and displays the corresponding text prediction on-screen as the gesture is recognized.

#### Potential Applications
- Real-time translation tools for the deaf and hard of hearing
- Integration with video conferencing platforms for accessibility
- Educational tools for learning sign language
- Gesture-controlled interfaces and assistive technologies

#### Future Work
- Expand sign vocabulary and support continuous sentence recognition
- Improve model generalization with larger and more diverse datasets
- Incorporate attention mechanisms or Transformer-based architectures for enhanced temporal understanding

#### Conclusion
This project demonstrates how real-time sign language recognition can be achieved using LSTM-based action recognition and keypoint extraction from live webcam input. By combining spatial and temporal modeling, the system offers an effective and extensible approach to gesture recognition. It lays the groundwork for developing assistive technologies and accessibility solutions that are practical, scalable, and adaptable to various real-world use cases.

#### AI Assistance Statement
ChatGPT was used selectively for debugging, troubleshooting issues, and improving clarity in written explanations. All final code and documentation were independently reviewed.
