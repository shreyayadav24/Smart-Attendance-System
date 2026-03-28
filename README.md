# 🎯 Smart Attendance & Face Recognition System

An intelligent real-time attendance tracking system built using Python, OpenCV, and face recognition techniques. This project automatically detects faces through a webcam, identifies individuals, and logs attendance with timestamps for further analysis.

---

## ✨ Key Features

🎥 Real-Time Face Recognition  
Detects and identifies faces instantly using a webcam feed.

📝 Automatic Attendance Logging  
Marks attendance with name, date, and time in a CSV file.

⚡ Efficient Encoding System  
Uses precomputed face encodings for faster recognition and reduced processing time.

📊 Attendance Analytics  
Analyzes attendance data and generates visual insights using Python.

📂 Structured Face Database  
Organizes known faces in a folder-based system for easy scalability.

---

## 💻 Technology Stack

- Python  
- OpenCV (cv2)  
- face_recognition  
- NumPy  
- Pandas  
- Matplotlib  
- CSV (data storage)

---

## 📁 Project Structure

```
Smart-Attendance-System/
│
├── app.py
├── encode_faces.py
├── analysis.py
├── attendance.csv
├── requirements.txt
├── face_encodings.pkl
│
├── known_faces/
│   ├── Person1/
│   ├── Person2/
│
└── README.md
```

---

## ⚙️ Installation & Setup

Clone the repository:

```bash
git clone https://github.com/shreyayadav24/Smart-Attendance-System.git
cd Smart-Attendance-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 📂 Prepare Face Dataset

Create a folder:

```
known_faces/
```

Inside it, add subfolders for each person:

```
known_faces/
 ├── Shreya/
 │   ├── img1.jpg
 │   ├── img2.jpg
 ├── Friend/
 │   ├── img1.jpg
```

---

## ▶️ How to Run

### Step 1: Encode Faces

```bash
python encode_faces.py
```

This creates:

```
face_encodings.pkl
```

---

### Step 2: Start Attendance System

```bash
python app.py
```

- Webcam will open  
- Faces will be detected  
- Attendance will be recorded automatically  

Press **Q** to exit.

---

### Step 3: Analyze Attendance

```bash
python analysis.py
```

This generates attendance insights and visualizations.

---

## 📊 Sample Output

### 📈 Attendance Analysis
![Attendance Analysis](attendance_analysis.png)

---

## 📊 Key Insights

- Tracks daily attendance patterns  
- Identifies frequently present individuals  
- Provides simple visualization of attendance distribution  

---

## 🚀 Future Improvements

- Add GUI dashboard using Streamlit  
- Integrate with SQL database  
- Improve recognition accuracy with deep learning  
- Deploy as a web-based application  

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!
