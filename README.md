# 🤖Face Recognition and Attendance System

This project is a Face Recognition and Attendance System built using Python and OpenCV. It captures faces from a webcam, trains a recognition model, and uses it to mark attendance. Additionally, it provides a simple web interface to display attendance data.  
#
  
## 📑Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
  - [Training the System](#training-the-system)
  - [Recognizing Faces and Taking Attendance](#recognizing-faces-and-taking-attendance)
  - [Viewing Attendance Data](#viewing-attendance-data)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

#
## 🧩Features

- Capture face data using a webcam.
- Train a face recognition model with the captured data.
- Recognize faces and mark attendance.
- Display attendance data through a web interface.
#  
## 🥋Prerequisites

- Python 3.x
- OpenCV
- NumPy
- scikit-learn
- pandas
- streamlit
- pywin32 (for Windows text-to-speech functionality)
#  
## 🪄Installation

**1. Clone the repository:**

```bash
git clone https://github.com/SinethB/face-recognition-and-attendance-system.git
cd face-recognition-and-attendance-system
```
#  
**2. Install the required packages:**
   
```bash
pip install opencv-python-headless numpy scikit-learn pandas streamlit pywin32
```
#  
**3. Ensure you have a haarcascade file for face detection. You can download it from here and place it in a data directory:**

```bash

mkdir data
wget -P data/ https://github.com/opencv/opencv/raw/master/data/haarcascades/haarcascade_frontalface_default.xml
```
#  
## 🧮Usage

### **🤺Training the System**  


1. Run the add_face.py script to capture and store face data:
   
```bash
python add_face.py
```

2. Enter your name when prompted and allow the system to capture 100 images of your face.  

#
### **🪪Recognizing Faces and Taking Attendance**  

  
1. Run the test.py script to recognize faces and take attendance:
   
```bash
python test.py
```

2. Press 'o' to take attendance and save it to a CSV file.
3. Press 'q' to quit the application.

#
### **📋Viewing Attendance Data**  

1. Run the app.py script to view the attendance data:

```bash
streamlit run app.py
```

2. Open the provided URL in a web browser to see the attendance records.

#
## 📊Project Structure
```sql
face-recognition-and-attendance-system/
│
├── data/
│   ├── haarcascade_frontalface_default.xml
│   ├── faces.pkl
│   └── names.pkl
│
├── Attendance/
│   └── Attendance_<date>.csv
│
├── add_face.py
├── test.py
├── app.py
├── background.jpg
└── README.md
```
#
## 🤝Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.  

 # 
*Feel free to adjust the sections as necessary. If you have any additional details or modifications, let me know!* 😃😃


