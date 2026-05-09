Driver Drowsiness Detection System

📌 Project Description

This project detects whether a driver is drowsy, sleepy, or active using a webcam.
It uses computer vision techniques to track eye movements and alert when the driver is tired.

---

🛠️ Technologies Used

- Python
- OpenCV
- Dlib
- NumPy
- Imutils

---

⚙️ How It Works

- Detects face using dlib
- Finds facial landmarks (eyes)
- Calculates eye blink ratio
- Classifies state:
  - Active 😊
  - Drowsy 😴
  - Sleeping 🚨

---

🚀 How to Run the Project

1. Install dependencies

pip install opencv-python numpy imutils dlib-bin

2. Download required file

Download:
shape_predictor_68_face_landmarks.dat

3. Place file

Keep it in the same folder as:
driver_drowsiness.py

4. Run the program

python driver_drowsiness.py

---

⚠️ Important Note

The ".dat" file is not included in this repository due to large size.
You need to download it manually.
Download Required File

This project requires the facial landmark model file:

👉 Download here:
http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2

Steps:

1. Download the file from the above link
2. Extract the ".bz2" file
3. Place "shape_predictor_68_face_landmarks.dat" inside the project folder

⚠️ Note: This file is not included in the repository due to its large size.

---

🙏 Credits

This project is inspired by an existing GitHub project.
The implementation and setup were done by me.

---

📷 Output

- Detects face and eyes
- Displays status:
  - Active
  - Drowsy
  - Sleeping

---

💡 Future Improvements

- Add alarm sound when drowsy
- Improve accuracy using deep learning
- Deploy as mobile/web application
