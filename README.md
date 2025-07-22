# 🧑‍🏫 Face Recognition-Based Attendance System

An automated attendance system developed using **Python**, **OpenCV**, and the **face_recognition** library. It captures live webcam video, detects and recognizes faces in real-time, and logs attendance with timestamps in a CSV file — ensuring contactless and efficient tracking.

🗓️ **Project Duration**: March 2025  
👨‍💻 **Type**: Self-Initiated Project

---

## 🔍 Features

- 🎥 **Real-Time Face Detection & Recognition**
  - Utilizes webcam feed to detect and match faces against a pre-trained dataset.
- 🗂️ **Automatic Attendance Logging**
  - Saves attendance with a name and timestamp to a CSV file.
- 👥 **Multiple Faces Support**
  - Can detect and mark attendance for multiple individuals at once.
- 💡 **User Feedback**
  - Displays real-time feedback on recognized and unrecognized faces.

---

## 🛠️ Technologies Used

| Technology           | Purpose                                      |
|----------------------|----------------------------------------------|
| Python               | Core programming language                    |
| OpenCV               | Real-time video and image processing         |
| face_recognition     | Face encoding, matching, and detection       |
| NumPy                | Efficient array processing                   |
| Pillow               | Image loading and display                    |
| CMake + dlib         | Backend for facial recognition engine        |
| CSV File Handling    | Attendance log storage                       |

---

## 💻 How It Works

1. Load known faces from the dataset (images of registered individuals).
2. Access webcam feed and continuously read frames.
3. Detect and encode faces in real-time.
4. Match against known encodings.
5. If matched, mark attendance in a CSV file with timestamp.
6. Display results live on the screen.

---

## 📦 Directory Structure

