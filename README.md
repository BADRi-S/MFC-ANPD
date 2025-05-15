# Automatic Number Plate Detection with MFC and Python

## 📌 Overview

This project combines a C++ MFC (Microsoft Foundation Class) GUI with a Python Flask backend to perform automatic number plate recognition (ANPR). Users can interact with a user-friendly Windows desktop interface that sends images or video frames to a Python-based machine learning model for number plate detection and OCR (Optical Character Recognition).

## ⚙️ Features

- 📷 Upload images via MFC GUI (videos are in future updates)
- 🔍 Automatic number plate detection using OpenCV and machine learning
- 🧠 OCR to extract text from detected plates (using Tesseract or EasyOCR)
- 🔁 Real-time communication between MFC and Flask backend
- 💬 Displays results on the GUI

## 🖥️ Technologies Used

### Frontend (MFC)
- C++ with Microsoft Foundation Classes
- HTTP communication (e.g., `WinInet` or `CURL`)

### Backend (Python)
- Flask (API server)
- OpenCV (image processing)
- Tesseract / EasyOCR (OCR engine)
- NumPy, Pillow

## 🚀 Getting Started

### Backend Setup (Python)

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/number-plate-detection-mfc-python.git
    cd number-plate-detection-mfc-python/backend
    Drive: https://drive.google.com/file/d/1s8HUQIi2Z5MA2NloON2LtB9v1uGhaPZt/view?usp=sharing
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Flask server:**
    ```bash
    python app.py
    ```

### Frontend Setup (MFC)

1. Open the MFC project in Visual Studio.
2. Build and run the application.
3. Use the GUI to select an image/video and send to the Python backend.

## 📂 Project Structure



