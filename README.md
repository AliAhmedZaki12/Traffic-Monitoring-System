# 🚦 Traffic Monitoring System 

This project implements a real-time **traffic monitoring system** using **YOLOv8**, capable of detecting vehicles, tracking them across frames, counting them, and estimating their speed based on line-crossing logic.

The system is designed for applications such as traffic analytics, road safety automation, and intelligent transportation systems.

---

## 📌 **Features**

* Vehicle detection using **YOLOv8m**
* Tracking with persistent object IDs
* Automatic recognition of: **car, bus, truck**
* Speed estimation between two horizontal reference lines
* Overspeed detection with on-frame alerts
* Total vehicle counting
* Output saved as a processed video file
* Real-time visualization when running in Jupyter Notebook

---

## 🛠️ **Tech Stack**

* Python
* OpenCV
* NumPy
* PyTorch (CPU build)
* Ultralytics YOLOv8
* SciPy & Scikit-Learn (compatibility dependencies)

---

## 📁 **Project Workflow**

1. Install all required libraries automatically.
2. Load and initialize the YOLOv8 model.
3. Configure detection targets (car, bus, truck).
4. Load an input video (`traffictrim.mp4`).
5. Track vehicles and assign unique IDs.
6. Measure time taken to cross two fixed lines.
7. Estimate speed and detect overspeeding.
8. Display results and save the output video (`output.avi`).

---

## 📊 **Output**

* Processed video with:

  * Bounding boxes
  * Object IDs
  * Calculated speed
  * Overspeed warnings
  * Vehicle counter

---

## ▶️ **How to Run**

Place your video file (`traffictrim.mp4`) in the working directory, then run the notebook or Python script.
The system will automatically generate `output.avi`.

---

## 📦 **Dependencies Installation**

All required libraries are installed automatically at the start of the script:
---

## 📌 **Use Cases**

* Smart city traffic monitoring
* Overspeed detection systems
* Automated traffic data analytics
* Transportation research projects

---
