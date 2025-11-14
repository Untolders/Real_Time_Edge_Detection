# 📱 Real-Time Edge Detection Viewer

A fast Android-based real-time camera processing application built using **Java**, **OpenCV (C++)**, and **OpenGL ES**.  
The app provides two modes when launched:

- **Open Camera** → Default camera preview  
- **Show Processed Output** → Real-time **Canny Edge Detection** display

---

## 🚀 Features

### 🎥 Camera & Rendering
- Real-time camera feed using **Camera2 API**
- Smooth rendering with **OpenGL ES 2.0**
- One-click toggle between **Raw View** and **Processed View**

### 🧠 Image Processing (C++ / OpenCV)
- High-speed **Canny Edge Detection**
- Grayscale processing
- YUV → Mat → RGBA conversion pipeline
- FPS & frame timing logs

### 🔗 Architecture Highlights
- **Java/Kotlin Layer** → Captures frames & UI handling  
- **JNI Bridge** → Sends frames to native code (C++)  
- **OpenCV C++ Layer** → Performs edge detection  
- **OpenGL ES** → Renders processed images as textures

---

## 🖼️ Screenshots

| Home Page | Raw Image | Processed Image |
|-----------|-----------|-----------------|
| <img src="images/Main.jpg" height="450"/> | <img src="images/Pro.jpg" height="450"/> | <img src="images/Edge.jpg" height="450"/> |

---

## ⚙️ Setup & Installation

### 1️⃣ Prerequisites
- Android Studio Arctic Fox or newer  
- Android NDK (r21+)  
- OpenCV Android SDK (v4.x recommended)  

---

### 2️⃣ Clone This Repository
```bash
git clone https://github.com/namanrox/Real-Time-Edge-Detection-Viewer.git
cd Real-Time-Edge-Detection-Viewer
