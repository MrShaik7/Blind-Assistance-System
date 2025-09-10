# 👁️🔊 YOLO Voice Assistant – Real-Time Object Detection with Speech

This project combines **YOLOv3 object detection** with **text-to-speech (TTS)** to describe what the camera sees.
It’s like giving your webcam a voice — turning visual inputs into spoken words in real time.

---

## ✨ Features

* 🎥 **Real-time Object Detection** using YOLOv3 + OpenCV
* 🧠 **Trained on COCO dataset** (80 common object classes)
* 🗣️ **Voice Feedback** with pyttsx3 – announces detected objects
* 🎯 **Spatial Awareness** – describes objects by position (e.g., “top left person” or “mid center chair”)
* 💻 **Works with Webcam Feed** out-of-the-box

---

## 🎯 Use Cases

* 👓 **Assistive Technology** → Helping visually impaired individuals understand surroundings
* 🏠 **Smart Home** → Real-time monitoring and object narration
* 🤖 **Robotics** → Enable robots/drones to “speak” what they detect
* 🎓 **Learning Projects** → Great for exploring **Computer Vision + Speech Synthesis**

---

## 🛠️ Tech Stack

* **YOLOv3** – Pretrained on COCO dataset (object detection)
* **OpenCV (cv2)** – Capturing webcam frames + running YOLO inference
* **pyttsx3** – Offline text-to-speech engine
* **NumPy** – Fast matrix computations

---

## 🚀 How It Works

1. Capture frames from the webcam
2. Process frames through YOLOv3 for object detection
3. Identify objects + their positions (left/center/right, top/mid/bottom)
4. Convert detections into spoken descriptions using pyttsx3

---

👉 Do you want me to also suggest a **catchy repo name** for this (something beyond “YOLO + speech”), like what we did for the PDF/Web RAG projects?
