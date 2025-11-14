# Lane Line Detection Project

This project implements **Lane Line Detection** using Python, OpenCV, and Jupyter Notebook. It identifies lane boundaries in road images or video frames by applying image-processing techniques.

---

## 🚗 **Project Overview**

Lane detection is a crucial component of Advanced Driver Assistance Systems (ADAS). This project focuses on detecting lane lines in a robust and efficient manner using:

* Image preprocessing
* Edge detection (Canny)
* Region of Interest (ROI) masking
* Hough Line Transform for lane extraction

---

## 🧠 **Tech Stack / Tools Used**

* **Python**
* **Jupyter Notebook**
* **OpenCV (cv2)**
* **NumPy**

---

## 📂 **Project Structure**

```
Lane-Line-Detection/
│── lane_line_detection.ipynb
│── test_images/
│── output_images/
│── README.md
```

---

## ⚙️ **Methods & Pipeline**

1. **Grayscale Conversion** – reduces complexity
2. **Gaussian Blur** – removes noise
3. **Canny Edge Detection** – highlights edges
4. **Region of Interest (ROI)** – focuses on the road area
5. **Hough Transform** – extracts lane line segments
6. **Overlays detected lines on the original image**

---

## ▶️ **How to Run**

1. Install dependencies:

```bash
pip install opencv-python numpy matplotlib
```

2. Open Jupyter Notebook:

```bash
jupyter notebook
```

3. Run `lane_line_detection.ipynb`

---

## 📈 **Results**

* Outputs lane-line–highlighted images
* Works on most daylight road images and simple videos

---

## 📝 **Future Improvements**

* Support for curved lane detection
* Better robustness in low-light/night scenes
* Deep-learning–based lane detection (e.g., SCNN, LaneNet)

---

## 👨‍💻 **Author**

Urooj Fatima
