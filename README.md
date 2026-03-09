<!-- 🌌 Header -->
<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=220&section=header&text=AI%20Gesture%20Control%20System&fontSize=45&fontColor=ffffff&animation=fadeIn"/>
</p>

<!-- ⌨ Typing Animation -->
<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&width=600&lines=Control+Computer+Using+Hand+Gestures;Computer+Vision+Project;OpenCV+%2B+MediaPipe+%2B+Python"/>
</p>

---

# 🏆 Tech Stack

![Python](https://img.shields.io/badge/Python-3670A0?logo=python&logoColor=ffdd54)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-FF6F00?logo=google&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)

---

# 📌 Project Overview

This project allows you to control your computer using **hand gestures detected through a webcam**.

Using **MediaPipe Hand Tracking** and **OpenCV**, the system recognizes gestures and performs actions such as:

- Moving the mouse cursor
- Left click / Right click
- Drag and drop
- Adjusting system volume
- Changing screen brightness
- Vertical and horizontal scrolling

The goal of this project is to demonstrate how **computer vision can be used to build touchless human-computer interaction systems**.

---

# 🧠 How It Works

1. Webcam captures real-time video feed  
2. Frames are processed using **OpenCV**  
3. **MediaPipe** detects hand landmarks  
4. Gesture recognition algorithm identifies finger positions  
5. Each gesture is mapped to a system command  
6. Commands are executed using **PyAutoGUI**, **Pycaw**, and **Brightness Control APIs**

Example gestures:

| Gesture | Action |
|------|------|
| V Gesture | Move Cursor |
| Fist | Drag Mouse |
| Two Fingers | Double Click |
| Index Finger | Right Click |
| Pinch Gesture | Volume / Brightness Control |

---

# 📦 Required Python Packages

- opencv-python
- mediapipe
- numpy
- pyautogui
- screen-brightness-control
- pycaw
- comtypes
- protobuf

---

# ⚙ Installation

## 🪟 Windows

### 1️. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/ai-gesture-control-system.git
```

### 2️. Go to the project folder

```bash
cd ai-gesture-control-system
```

### 3️. Install required packages

```bash
pip install opencv-python mediapipe numpy pyautogui screen-brightness-control pycaw comtypes protobuf
```

### 4️. Run the program

```bash
python gesture_controller.py
```

---

## 🐧 Linux

### 1️. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/ai-gesture-control-system.git
```

### 2️. Go to the project folder

```bash
cd ai-gesture-control-system
```

### 3️. Install dependencies

```bash
pip3 install opencv-python mediapipe numpy pyautogui screen-brightness-control pycaw comtypes protobuf
```

### 4️. Run program

```bash
python3 gesture_controller.py
```

---

# 🎮 Gesture Control Chart

| Gesture | Action |
|-------|-------|
| V Gesture | Move Cursor |
| Fist | Drag / Hold Mouse |
| Index Finger | Right Click |
| Two Fingers | Double Click |
| Pinch Gesture | Adjust Volume / Brightness |
| Pinch Minor | Scroll |

# 🧑‍💻 Usage

1. Run the script  
2. Show your hand in front of the webcam  
3. Perform gestures to control your computer  

Examples:

- Move cursor using **V gesture**
- Drag objects using **fist**
- Right click using **index finger**
- Adjust brightness or volume using **pinch gesture**
- Scroll pages using **pinch gestures**

Press **ENTER key** to exit the program.

---

# 🚀 Future Improvements

- Gesture customization system  
- Machine learning based gesture recognition  
- GUI control panel  
- Cross-platform gesture control  
- Support for additional gestures

---

# ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub.

---

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=170&section=footer&text=Thanks%20for%20Visiting%20My%20Profile!&fontSize=28&fontColor=ffffff&animation=twinkling&fontAlignY=65"/>
</p>
