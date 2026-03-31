🚗 Road Lane Detection in Adverse Weather Conditions
📌 Overview

This project focuses on developing a robust lane detection system capable of accurately identifying road lane markings under adverse weather conditions such as rain, fog, shadows, and low-light environments. It enhances traditional lane detection methods using advanced image processing and machine learning techniques to improve reliability and performance.

🎯 Features
🌧️ Detects lanes in rain, fog, and low-light conditions
🎥 Supports real-time video processing
🔍 Edge detection using Canny Algorithm
📏 Lane detection using Hough Transform
⚡ Improved accuracy with adaptive filtering techniques
🧠 Optional integration with machine learning models
🛠️ Tech Stack
Language: Python
Libraries: OpenCV, NumPy, Matplotlib
Concepts: Image Processing, Computer Vision
⚙️ Working
Capture input from image/video
Apply preprocessing (grayscale, blur, contrast enhancement)
Detect edges using Canny Edge Detection
Apply Region of Interest (ROI)
Detect lanes using Hough Transform
Overlay lanes on original frame
🧪 Challenges Addressed
Low visibility in fog and rain
Noise due to water droplets
Poor lighting in night conditions
Faded or unclear lane markings
🚀 Future Enhancements
Integration with Deep Learning (CNN / YOLO)
Add Lane Departure Warning System
Improve real-time performance using GPU
Deploy in autonomous driving systems
📸 Output

Add screenshots or demo video here

📂 Project Structure
lane-detection/
│── data/
│── output/
│── src/
│   └── main.py
│── requirements.txt
│── README.md
▶️ Installation & Usage
# Clone the repository
git clone https://github.com/yourusername/lane-detection.git

# Navigate to folder
cd lane-detection

# Install dependencies
pip install -r requirements.txt

# Run the project
python main.py
📌 Applications
🚘 Autonomous Vehicles
🛣️ Driver Assistance Systems (ADAS)
🚦 Smart Traffic Monitoring
👨‍💻 Author

Vaishnav Rao

📄 License

This project is licensed under the MIT License

⭐ Support

If you like this project, give it a ⭐ on GitHub!
