# CrimTrack - AI-Powered Criminal Detection System

## 📌 Project Overview
CrimTrack is a Flask-based web application that leverages AI-driven face recognition to detect criminals in uploaded video footage. The system processes video frames, identifies faces, and matches them against a predefined criminal dataset.

## ✨ Features
- 🔍 Upload a video file for processing
- 🕵️ Detects faces in the video using `face_recognition` and `OpenCV`
- 📜 Matches detected faces against a criminal database
- 📌 Displays details of identified criminals, including name, crime, and age
- 🖼 Saves frames with detected faces and highlights them with bounding boxes
- ⏳ Provides timestamps for when the criminal is first spotted in the video

## 🏗 Tech Stack
- **Flask** - Backend framework
- **OpenCV** - Video processing
- **face_recognition** - Face matching
- **HTML/CSS** - Frontend UI
- **NumPy** - Array and mathematical operations
- **CSV** - Criminal dataset storage

## 🚀 Installation & Setup
### Prerequisites:
Ensure you have Python installed on your system. You can check by running:
```sh
python --version
```

### Step 1: Clone the Repository
```sh
git clone https://github.com/YOUR-USERNAME/CrimTrack.git
cd CrimTrack
```

### Step 2: Create a Virtual Environment & Install Dependencies
```sh
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### Step 3: Run the Application
```sh
python app.py
```
The application will start running at `http://127.0.0.1:5000/`

## 📌 Usage
1. Open the application in your browser.
2. Upload a video file.
3. The system will analyze the video and detect faces.
4. Identified faces will be matched against the criminal database.
5. The system will highlight detected faces and display crime details.

## 🔗 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## 📜 License
This project is licensed under the MIT License.

## 🤝 Connect
For queries or collaborations, connect with me on [LinkedIn](https://www.linkedin.com/in/sneha-k-kamble-48b733267/).
