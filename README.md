# NextShot - AI Powered Cricket Batting Coach

An intelligent Android application that uses **AI-powered pose estimation** to analyze a batsman's technique in real-time and provide actionable feedback to improve batting skills.

![NextShot Banner](screenshots/demo.gif)  
*(Replace with actual screenshot or demo GIF)*

## 🎯 Purpose

The main goal of **NextShot** is to help individual cricket batsmen improve their **batting technique** by tracking key body movements such as:
- Footwork
- Head position & stability
- Weight transfer
- Arm movement
- Stance and balance

It provides **real-time visual feedback** (skeleton overlay) along with performance metrics and coaching tips.

---

## ✨ Key Features

- Live camera batting analysis with real-time pose skeleton
- Video upload & offline analysis
- Keypoint detection using YOLOv8 Pose model
- Head stability scoring
- Weight transfer visualization
- Shot type using keypoints
- Session history & progress tracking
- Personalized coaching feedback (LLM integration)
- Clean and intuitive Android UI

---

## 🛠 Technologies Used

- **Language**: Kotlin
- **IDE**: Android Studio
- **Camera & Video**: CameraX, VideoView, MediaMetadataRetriever
- **AI/ML**: Roboflow (YOLOv8x-pose-1280 model), Mediapipe
- **Networking**: OkHttp
- **Database**: Firebase Firestore + Room (Local)
- **Authentication**: Firebase Auth
- **Architecture**: MVVM
- **Other**: Coroutines, Material Design, JSON parsing

---

## 📱 Screenshots

*(Add 4-6 screenshots here - Live Camera, Video Analysis, Skeleton Overlay, Session History, Progress Screen, etc.)*

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/nimraasla/nextshot.git
