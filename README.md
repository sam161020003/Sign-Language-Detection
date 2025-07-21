🚗 Car Number Plate Detection using OpenCV & Python
A real-time vehicle license plate detection system using image processing and computer vision techniques. This project detects car number plates from images or video streams using Haar cascades and OpenCV.

📌 Objective
To automate the detection and extraction of car number plates from visual input (images or webcam feed), enabling future applications such as traffic monitoring, automated tolling, and law enforcement.

🧠 Key Features
🚘 Detects car number plates using Haar Cascade Classifier.

🎥 Works in real-time via webcam or accepts image input.

🧾 Extracts and displays the number plate region.

💾 Saves detected number plates as cropped image files.

✅ Lightweight and runs on CPU (no need for GPU/Deep Learning).

🛠️ Technologies Used
Tool/Library	Purpose
Python	Core language
OpenCV	Image processing, object detection
Haarcascade	Pre-trained classifier for number plate detection

📁 Project Structure

Car-Number-Plate-detection/
│
├── haarcascade_russian_plate_number.xml   # Pre-trained classifier
├── main.py                                # Main detection script
├── images/                                # Input images
├── output/                                # Saved cropped number plates
└── README.md                              # Documentation
🚀 How to Run
🔧 Requirements

pip install opencv-python
▶️ Running the Script

python main.py
The webcam will start. Show a vehicle number plate in front of the camera and the system will detect and save the cropped image automatically.
