# Human Activity Recognition and Alert System

![Project Banner](https://your-image-url.com/banner.png)

## 🚀 Overview

This project is an AI-powered **Human Activity Recognition and Alert System** designed to detect and respond to various human activities and emergency situations. It utilizes **computer vision, deep learning, and real-time video analysis** to identify events such as:

- 🏃 **Human Activity Recognition** (Standing, Sitting, Walking, etc.)
- 🔥 **Fire Detection**
- 🚗 **Vehicle Crash Detection**
- 🤕 **Fall Detection**
- 👫 **Social Distance Monitoring**

When a hazardous activity is detected, the system **sends automated alerts** via email, including an image of the detected event.

## 🛠 Features

✅ **Real-time monitoring** via Streamlit web app  
✅ **Automated email alerts** with detected event images  
✅ **Multiple AI-powered modules** for detecting different incidents  
✅ **YOLOv3 and TensorFlow-based object detection**  
✅ **User-friendly UI with live video stream support**  

## 📁 Project Structure

```
📂 Human Activity Recognition and Alert System  
│── app.py                     # Main Streamlit dashboard  
│── app1_social_detector.py     # Social Distance Detection module  
│── app2_fire_detector.py       # Fire Detection module  
│── app3_crash_detector.py      # Vehicle Crash Detection module  
│── app3_crash_detector_video.py # Crash Detector using video input  
│── app4_fall_alert.py          # Fall Detection module  
│── app5_human_activity.py      # Human Activity Recognition module  
│── constants.py                # Configuration file for YOLO paths and settings  
│── accidents.pbtxt             # Label map for crash detection  
│── fallInfo1.txt               # Log file containing detected falls  
│── 📂 yolov3                   # YOLO model files (cfg, weights, and labels)  
│── 📂 videos                   # Sample video input files  
│── 📂 output                    # Output directory for detected images  
```

## 📌 Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/human-activity-recognition.git
cd human-activity-recognition
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Download YOLO Weights
Download YOLOv3 weights and place them in the `yolov3/` directory:
```
yolov3.weights
yolov3.cfg
coco.names
```

### 4️⃣ Run the Application
```bash
streamlit run app.py
```

## 🖥️ Usage

1️⃣ **Launch the Streamlit dashboard**  
2️⃣ **Select a module from the sidebar** (Social Distance, Fire Detection, etc.)  
3️⃣ **Start the camera or upload an image/video**  
4️⃣ **Receive automated alerts** in case of hazards  

## 📧 Alert System
The system **automatically sends email notifications** when an emergency is detected. Each alert includes:

- **An image of the detected event**
- **The detected category (fire, crash, fall, etc.)**
- **Timestamp of the event**

## 🛠 Technologies Used

- **OpenCV** - Image and video processing  
- **YOLOv3** - Object detection  
- **TensorFlow** - Deep learning for crash detection  
- **MediaPipe** - Human pose estimation  
- **Streamlit** - Web-based interface  
- **NumPy, Matplotlib** - Data processing and visualization  

## 🤝 Contributing

Contributions are welcome! To contribute:

1. **Fork** the repository  
2. **Create a feature branch** (`git checkout -b new-feature`)  
3. **Commit your changes** (`git commit -m 'Add new feature'`)  
4. **Push to the branch** (`git push origin new-feature`)  
5. **Open a Pull Request**  

## 🔒 License

This project is open-source and available under the **MIT License**.  

---

### 📢 Connect with Me!
💻 **GitHub**: [Your GitHub](https://github.com/your-username)  
📧 **Email**: your-email@example.com  
🌍 **Website**: [Your Website](https://yourwebsite.com)  

