# Face Recognition Attendance System

An intelligent face recognition-based attendance system built using DeepFace (Facenet model). The system identifies individuals from images and records their attendance with date and time.

## Features
- Real-time face recognition using DeepFace
- Attendance logging into a CSV file
- Duplicate prevention (only one entry per person per day)
- Dataset visualization using Matplotlib

## How to Use (Google Colab)
1. Upload `dataset.zip` containing person image folders.
2. Upload a test face image (e.g., `test.jpg`).
3. Run the notebook cells step by step.
4. Attendance is saved to `attendance.csv`.

## Requirements
- Python 3.x
- DeepFace
- OpenCV
- Pandas
- Matplotlib

## License
MIT

