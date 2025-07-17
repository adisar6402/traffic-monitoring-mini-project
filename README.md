# 🚦 Intelligent Traffic Monitoring and Analysis System

This project was built as part of the **3MTT AI/ML Cohort 3 Track**. It is a mini-project focused on using **computer vision and machine learning** to automate traffic monitoring and analysis using real video footage and deep learning models.

---

## 📌 Project Overview

Traffic congestion is a major urban problem, and manual monitoring is not scalable. This project solves that by implementing an **AI-powered traffic monitoring system** using **YOLOv8**, **OpenCV**, and **scikit-learn** to detect vehicles, estimate traffic density, and predict congestion levels in real-time.

---

## 🎯 Objectives

- Detect vehicles using YOLOv8 in traffic videos.
- Preprocess and analyze video data for vehicle detection.
- Estimate traffic density across frames.
- Train a simple machine learning model (logistic regression) to classify traffic congestion as low, medium, or high.
- Visualize and display results using OpenCV in real-time.

---

## 🧠 Learning Outcomes

Through this project, I gained practical experience in:

- Computer vision techniques using OpenCV.
- Using YOLOv8 for object (vehicle) detection.
- Preprocessing video frames and grayscale conversion.
- Training a logistic regression model with scikit-learn.
- Real-time visualization and model inference on video data.

---

## 🛠️ Tools & Technologies

- Python 3
- OpenCV
- Ultralytics YOLOv8
- Scikit-learn
- Matplotlib
- Google Colab

---

## 📁 Project Structure

```
traffic-monitoring-mini-project/
│
├── module_5_mini_project.ipynb     # Main Jupyter Notebook
├── traffic_video.mp4               # Traffic footage used
├── README.md                       # Documentation file
```

---

## 🚀 Project Steps

### ✅ Step 1: Define the Problem  
Wrote a short paragraph explaining how computer vision improves traffic systems.

### ✅ Step 2: Data Collection  
Downloaded and loaded traffic video data (`traffic_video.mp4`) using OpenCV.

### ✅ Step 3: Exploratory Data Analysis  
(Planned vehicle count analysis logic, placeholder in code).

### ✅ Step 4: Video Preprocessing  
Extracted and resized the first 10 frames, converting them to grayscale.

### ✅ Step 5: Feature Engineering  
Used **YOLOv8** (`yolov8n.pt`) to detect vehicles on sample frames.

### ✅ Step 6: Model Training  
Trained a logistic regression model to classify traffic density from counts.

### ✅ Step 7: Deployment & Visualization  
Displayed real-time frame analysis and annotated detections with OpenCV.

---

## 💡 How to Run

> Run on Google Colab (Recommended)

### Install Dependencies:
```bash
!pip install -q ultralytics opencv-python matplotlib scikit-learn
```

### Video Requirements:
Ensure the video file `traffic_video.mp4` is in the working directory, or update the path accordingly.

---

## 📝 Submission Notes

- ✅ Submitted as part of **Module 5 mini-project** for **3MTT AI/ML Track**.
- ✅ Includes Jupyter notebook with step-by-step code and markdown explanations.
- ✅ Project uploaded to GitHub and backed up on Google Drive.
- ✅ Feedback requested on model training and density classification accuracy.

---

## 🔗 Links

- 📂 [Google Drive Submission](https://drive.google.com/file/d/1Rc62TtLtxqgtCdOR1uz8n3Nlb8QyEEP6/view?usp=sharing)
- 🔗 [GitHub Repository](https://github.com/adisar6402)
- 🧠 [LinkedIn (Rahman)](https://www.linkedin.com/in/abdulrahman--engineering-ai-ml/)
- 🐦 [Twitter / X](https://x.com/RahmanAdis42469)

---

## 👤 Author

**Abdulrahman Adisa Amuda**  
Machine Learning Enthusiast | AI Innovator | 3MTT Cohort 3 Trainee

---

## 📜 License

This project is open-source under the [MIT License](https://opensource.org/licenses/MIT).  
Feel free to use, fork, or improve — just give credit where it's due!

