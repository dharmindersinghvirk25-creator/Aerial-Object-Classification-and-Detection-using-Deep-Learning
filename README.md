# 🚀 Aerial AI PRO MAX  
### Bird 🐦 vs Drone 🚁 Classification + Detection System  

---

## 📌 Project Overview  
Aerial AI PRO MAX is a Deep Learning-based Computer Vision project that can:

- Classify aerial images into **Bird 🐦 or Drone 🚁**
- Detect objects using **YOLOv8 (Object Detection)**
- Provide real-time predictions using a **Streamlit Web Application**

This project is designed for real-world applications like surveillance, wildlife monitoring, and airspace safety.

---

## 🎯 Problem Statement  
The goal of this project is to develop an intelligent system that can:

- Accurately classify aerial images into **Bird** or **Drone**
- Detect and locate objects in images using bounding boxes
- Reduce misclassification in real-time aerial environments

---

## 💼 Business Use Cases  

- 🦅 **Wildlife Protection**  
  Detect birds near wind farms or airports  

- 🛡 **Security & Defense**  
  Identify drones in restricted airspace  

- ✈️ **Airport Safety**  
  Prevent bird strikes  

- 🌍 **Environmental Monitoring**  
  Track bird populations using aerial imagery  

---

## 🧠 Technologies Used  

- Python  
- TensorFlow / Keras  
- PyTorch  
- YOLOv8 (Ultralytics)  
- OpenCV  
- NumPy, Pandas  
- Matplotlib  
- Streamlit  

---

## 📂 Dataset Details  

### 📌 Classification Dataset  
- Classes: **Bird, Drone**  
- Format: `.jpg`  
- Split:
  - Train  
  - Validation  
  - Test  

### 📌 Object Detection Dataset  
- YOLOv8 Format (`.txt` labels)  
- 3319 Images  
- Includes bounding box annotations  

---

## ⚙️ Project Workflow  

1. Data Understanding  
2. Data Preprocessing (Resize, Normalize)  
3. Data Augmentation  
4. Model Building (CNN + Transfer Learning)  
5. Model Training  
6. Model Evaluation  
7. Object Detection using YOLOv8  

---

## 🖥️ Streamlit Application Features  

- Upload Image 📤  
- Predict:
  - Bird 🐦 or Drone 🚁  
  - Confidence Score  
- Object Detection Output with Bounding Boxes  

---

## ▶️ How to Run the Project  

### 1️⃣ Clone Repository  
```bash
git clone https://github.com/your-username/aerial-ai-project.git
cd aerial-ai-project

2️⃣ Install Requirements

- pip install -r requirements.txt

3️⃣ Run Streamlit App

- streamlit run app.py

📊 Output
- Image Classification Result (Bird / Drone)
- Confidence Score
- Object Detection with Bounding Boxes


📁 Project Structure
├── app.py                 # Streamlit Application
├── best_model.h5          # Classification Model
├── best.pt                # YOLOv8 Detection Model
├── data/                  # Dataset Folder
├── notebooks/             # Colab / Jupyter Notebooks
├── requirements.txt       # Dependencies
└── README.md              # Project Documentation

🧾 Deployment
- Developed using Streamlit
- Can be deployed on:
    - Streamlit Cloud
    - Local Machine

🏁 Conclusion

This project successfully demonstrates:

- Image Classification using CNN & Transfer Learning
- Object Detection using YOLOv8
- Real-time prediction using Streamlit

The system can accurately differentiate between birds and drones, making it useful for real-world aerial monitoring applications.

🔮 Future Improvements
- Improve accuracy with larger dataset
- Add real-time video detection 🎥
- Deploy on cloud platforms (AWS / GCP)
- Optimize for mobile devices 📱
- Add multi-class object detection

🙌 Author

Dharminder Singh Virk
Made with ❤️ using Deep Learning & Computer Vision
