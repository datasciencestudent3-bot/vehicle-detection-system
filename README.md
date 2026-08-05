# 🚗 Vehicle Detection System using YOLOv8

An AI-powered **Vehicle Detection System** developed using **Python**, **YOLOv8**, and **Computer Vision** techniques. This project automatically detects and counts different types of vehicles from traffic images, making traffic monitoring faster, more accurate, and efficient.

---

# 📖 Project Overview

This project was developed as part of the **Introduction to Data Science** course at **Dawood University of Engineering & Technology (DUET)**.

The system uses the **YOLOv8x pretrained object detection model** to detect vehicles such as **cars, buses, trucks, and motorcycles** from traffic images. Before detection, the input image is enhanced using preprocessing techniques to improve image quality and detection accuracy. Duplicate detections are removed using **Intersection over Union (IoU)** and **Non-Maximum Suppression (NMS)** to ensure accurate vehicle counting.

---

# ✨ Features

* 🚘 Detects multiple vehicles from traffic images
* 🚌 Classifies vehicles into different categories
* 📊 Counts the total number of detected vehicles
* 📦 Draws bounding boxes around detected vehicles
* 🎯 Displays confidence scores
* 🔍 Removes duplicate detections using IoU and NMS
* ⚡ Fast and efficient image-based vehicle detection

---

# 🛠️ Technologies Used

* Python
* YOLOv8
* OpenCV
* NumPy
* Google Colab

---

# 🚀 Workflow

1. Upload a traffic image.
2. Preprocess the image.
3. Detect vehicles using YOLOv8.
4. Generate bounding boxes.
5. Remove duplicate detections using IoU + NMS.
6. Count the detected vehicles.
7. Display the final output with vehicle statistics.

---

# 🚗 Vehicle Categories

The system can detect the following vehicle types:

* 🚗 Car
* 🚌 Bus
* 🚛 Truck
* 🏍️ Motorcycle

---

# 📂 Project Structure

```text
Vehicle-Detection-System/
│── Karachi_Revises_Speed_Limit_on_Major_Road[1].jfif
│── PROJECT_REPORT_FINAL[1].pdf
│── README.md
│── WhatsApp_Image_2026-05-10_at_5.13.19_PM[1].jpeg
│── untitled2_(1)[1].py
```

---

# 📈 Results

The system successfully:

* Detects multiple vehicles in a single image.
* Correctly classifies vehicle types.
* Generates accurate vehicle counts.
* Produces output images with labeled bounding boxes.
* Improves traffic monitoring efficiency.

---

# ⚠️ Limitations

* Performance decreases in low-light conditions.
* Small or distant vehicles may not be detected.
* Overlapping vehicles can reduce detection accuracy.

---

# 🔮 Future Enhancements

* Real-time CCTV integration
* Vehicle speed detection
* Traffic density prediction
* Smart city traffic management
* Upgrade to advanced models such as YOLOv9 or DeepSORT

---

# 📸 Project Preview

### Original Traffic Image

*(Add your original traffic image here.)*

### Vehicle Detection Output

*(Add the output image showing detected vehicles here.)*

### Vehicle Counting Result

*(Add the final vehicle counting result here.)*

---

# 👥 Team Members

* **Eman Haroon**
* **Saalim Shaikh**

---

# 🎓 Institution

**Dawood University of Engineering & Technology (DUET)**

**Department of Data Science**

---

# 📚 Course

**Introduction to Data Science**

Instructor: **Sir Jamal Shams Khanzada**

---

# 📄 Project Report

The complete project documentation is available in:

**PROJECT_REPORT_FINAL[1].pdf**

---

# 📜 License

This project was developed for **educational and learning purposes** as part of an academic course.
