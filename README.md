# NextShot - AI Powered Cricket Batting Coach

An intelligent Android application that uses **AI-powered pose estimation** to analyze a batsman's technique in real-time and provide actionable feedback to improve batting skills.

### Upload Mode
<img src="screenshots/demo.gif" width="400" alt="Demo">

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

### Thumbnail
<img src="screenshots/thumbnail" width="200" alt="Thumbnail">

### Main Page
<img src="screenshots/main page.jpeg" width="200" alt="Main Page">

### Practice Session
<img src="screenshots/practice session.jpeg" width="200" alt="Practice Session">

### Performance Tracking
<img src="screenshots/performance tracking.jpeg" width="200" alt="Performance Tracking">

### LLM Feedback
<img src="screenshots/LLM feedback.jpeg" width="200" alt="LLM Feedback">

### Video Links
<img src="screenshots/video links.jpeg" width="200" alt="Video Links">
---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/nimraasla/nextshot.git
