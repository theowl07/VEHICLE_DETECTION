# Vehicle Detection Using OpenCV

## 📌 Project Overview

Vehicle Detection is a computer vision project developed using **Python and OpenCV**. The system processes a video and detects vehicles moving on the road using image processing techniques.

The project can detect vehicles, track their movement, count vehicles, on their movement between video frames.

## 🎯 Objectives

* Detect vehicles from a road traffic video.
* Track detected vehicles.
* Count the number of vehicles.
* Display detected vehicles using bounding boxes.
* Process traffic video using OpenCV.

## 🛠️ Technologies Used

* **Python**
* **OpenCV**
* **NumPy**
* **Visual Studio Code**

## ✨ Features

* Vehicle detection
* Vehicle tracking
* Vehicle counting
* Bounding box detection
* Video processing
* Real-time display of detection results

## 📂 Project Structure

```text
Vehicle-Detection-OpenCV/
│
├── vehicle.py
├── README.md
├── .gitignore
│
├── input/
│   └──video.mp4
│
├── output/
│   └── Output.mp4
│
└── screenshots/
    ├── code.png
    └── vechicle_detection.png
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project folder

```bash
cd Vehicle-Detection-OpenCV
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

## ▶️ How to Run

Run the Python program:

```bash
python vehicle.py
```

The program will open the input traffic video and process it for vehicle detection.

### ⌨️ Keyboard Control

Press **Enter** to stop the video.

```python
if cv2.waitKey(50) == 13:
    break
```

## 🔄 Working Process

```text
Input Traffic Video
        ↓
Read Video Frames
        ↓
Image Processing
        ↓
Vehicle Detection
        ↓
Vehicle Tracking
        ↓
Vehicle Counting
        ↓
Display Detection Result
```

## 📊 Output

The system displays detected vehicles with bounding boxes and provides information such as vehicle count.

Add your project screenshots in the `screenshots` folder and display them here.

```markdown
![Vehicle Detection Result](code.png)
```

```markdown
![Speed Detection Result](screenshots/speed_detection.png)
```

## 📌 Applications

* Traffic monitoring
* Vehicle counting
* Highway surveillance
* Traffic management
* Road safety monitoring
* Smart transportation systems

## 🚀 Future Scope

* Automatic number plate recognition
* Vehicle type classification
* Multiple-lane vehicle detection
* Real-time CCTV integration
* AI/YOLO-based vehicle detection
* Traffic violation detection

## 👨‍💻 Author

**theowl07**

### Project Information

**Project:** Vehicle Detection using OpenCV
**Technology:** Python + OpenCV
**IDE:** Visual Studio Code

## 📄 License

This project is created for educational and academic purposes.
