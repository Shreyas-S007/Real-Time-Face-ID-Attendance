# Face Recognition Attendance System 📷📝

A real-time attendance management system using face recognition technology to automate attendance tracking.

## Features ✨

- **Real-Time Face Recognition**: Uses OpenCV and dlib for accurate face detection and recognition
- **User-Friendly Interface**: Clean GUI built with Tkinter
- **Database Integration**: Connects to Firebase for efficient attendance management
- **Automated Logging**: Updates attendance records instantly upon successful recognition

## Prerequisites 🛠️

- Python 3.x
- OpenCV
- dlib
- NumPy
- Tkinter
- Firebase Admin SDK

## Installation 🏗️

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/face-recognition-attendance-system.git
   cd face-recognition-attendance-system
   ```

2. **Set Up Virtual Environment**:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Firebase**:
   - Create a Firebase project and download the service account key
   - Initialize Firebase Admin SDK in your project
   - Configure database permissions for read/write operations

