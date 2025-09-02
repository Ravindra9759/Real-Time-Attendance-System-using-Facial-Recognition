## 🎯 Real-Time-Attendance-System-using-Facial-Recognition
A project aimed at creating a facial recognition attendance system
The Real-Time Attendance System using Facial Recognition is an automated solution designed to replace traditional manual or biometric attendance methods. The system leverages computer vision and deep learning algorithms to detect and recognize faces in real time through a camera feed. Once a registered face is identified, the system automatically marks attendance with the exact date and time, ensuring accuracy and efficiency. It also maintains a secure database for storing attendance records, which can be easily accessed for reporting and analysis. This approach minimizes proxy attendance, enhances security, and saves time in organizational and educational environments.

## 📸 Feature
- Real-time face detection and recognition using OpenCV and deep learning
- Automatic attendance logging with timestamps
- GUI interface for ease of use
- Secure database integration for storing attendance records
- Admin panel for managing student/employee profiles
- Git-integrated project structure for clean version control

## 🛠️ Technoloy Stack
_________________________________________________
| Component        | Technology Used            |
|------------------|--------------------------  |
| Programming      | Python                     |
| Face Detection   | OpenCV, HaarCascades / DNN |
| Face Recognition | LBPH / Deep Learning       |
| GUI              | Tkinter                    |
| Database         | MySQL                      |
| Version Control  | Git & GitHub               |
_________________________________________________

## 📂 Project Structur
__________________________________________________________________________________________________
| ├── Images                # Stores face images for training                                     |
| |-- __pycache__           #                                                                     |
| ├── data                  # Trained model files                                                 |
| ├── Attendance.csv        # CSV logs of attendance                                              |
| ├── main.py               # GUI interface                                                       |
| ├── Student.py            # fill the student deatails files                                     |
| ├── attendance.py         # Real-time recognition and logging                                   |
| ├── classifier.xml        # Genrate the a classifier                                            |
| ├── developer.py          # create a developer page                                             |   
| ├── face_recognition.py   # Real-time recognition and logging                                   |
| ├── haarcascade_fratalface_default.xml
| ├── help.py               # Provides user guidance, error explanations, and usage instructions  |
| ├── login.py              # Handles user authentication and access control                      |
| ├── train.py              # Script to train face recognizer                                     |
| └── README.md             # Project documentation                                               |
|_________________________________________________________________________________________________|
