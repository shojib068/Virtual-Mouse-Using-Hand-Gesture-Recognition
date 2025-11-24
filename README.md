# ✋ AI Mouse Controller Using Hand Gestures  

Control your **mouse cursor** using **hand gestures** through real-time webcam tracking.  
Built using **OpenCV**, **MediaPipe**, **PyAutoGUI**, and **Pynput**.

---

## 🧰 Tools Used
- Python 3.10  
- OpenCV  
- MediaPipe  
- PyAutoGUI  
- Pynput  
- NumPy  

---

## 📦 Dependencies

---

## ⭐ Features
- Real-time hand tracking with 21 landmarks  
- Index-finger-based mouse movement  
- Left click, right click & double click gestures  
- Screenshot gesture  
- Smooth and responsive control  

---

## ✋ Gesture Controls

| Gesture | Description | Action |
|--------|-------------|--------|
| 👉 Index finger forward | Finger straight | Move mouse |
| 👍 + 👉 (open) | Angle-based detection | Left click |
| ✌️ Middle finger gesture | Angle-based detection | Right click |
| ✌️ Both fingers bent | Angles small | Double click |
| 🤏 Thumb + index close | Distance < threshold | Screenshot |

---

## 📤 Output
- Cursor moves based on finger tip position  
- Click actions triggered by gestures  
- Screenshots saved as: my_screenshot_<random>.png

