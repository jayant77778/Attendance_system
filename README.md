
---

```markdown
# 🎓 Face Recognition Attendance System

<img src="https://img.shields.io/badge/python-3.8+-blue.svg" />
<img src="https://img.shields.io/badge/OpenCV-Face%20Detection-orange.svg" />
<img src="https://img.shields.io/badge/DeepFace-Face%20Recognition-green.svg" />
<img src="https://img.shields.io/badge/Status-Working-brightgreen" />

---

## 📸 Overview

This project is a real-time **face recognition-based attendance system** built using:
- `OpenCV` for face detection
- `DeepFace` for high-accuracy face recognition
- `Pandas` and `CSV` for logging attendance
- `Live webcam feed` as the input

Recognized students are automatically logged into an `attendance.csv` file, and unknown faces are saved separately for review.

---

## 🧰 Features

- ✅ Real-time face detection
- ✅ Accurate face recognition using DeepFace (`VGG-Face`)
- 📂 Unknown faces saved for later analysis
- 🕒 Logs time and date of each attendance
- 📄 Attendance saved in `CSV` format
- 🛡️ Ignores multiple faces and prevents duplicates

---

## 🖼️ Screenshots

| Recognized Face | Unknown Person |
|-----------------|----------------|
| ![Recognized](https://via.placeholder.com/300x200.png?text=Recognized) | ![Unknown](https://via.placeholder.com/300x200.png?text=Unknown) |

---

## 🗂️ Folder Structure

```

📦AttendanceSystem/
┣ 📁images/              # Known face images (e.g., john.jpg)
┣ 📁unknown\_faces/       # Saved images of unrecognized people
┣ 📄attendance.csv       # Automatically created attendance log
┣ 📄main.py              # Main Python script
┗ 📄README.md            # This file

````

---

## 🚀 Setup & Installation

### 1️⃣ Clone the Repo
```bash
git clone https://github.com/your-username/face-attendance-system.git
cd face-attendance-system
````

### 2️⃣ Install Dependencies

Make sure you have Python 3.8+ installed.

```bash
pip install opencv-python deepface pandas
```

### 3️⃣ Add Face Images

Put reference images of known students in the `images/` folder:

```
images/
┣ hitesh.jpg
┣ jayant.jpg
┣ lucky sain.jpg
```

### 4️⃣ Run the Program

```bash
python main.py
```

---

## 📝 CSV Output Format

| Student Name | Time     | Date       | Program       |
| ------------ | -------- | ---------- | ------------- |
| jayant       | 11:05:23 | 2025-06-06 | The Creator   |
| unknown\_1   | 11:06:42 | 2025-06-06 | Unknown Entry |

---

## ⚠️ Troubleshooting

### ❌ Permission Denied Error

If you see:

```
⚠️ Detection error: [Errno 13] Permission denied: 'attendance.csv'
```

✅ Fix:

* Close the file if open in Excel or Notepad
* Make sure it's not read-only
* Run script with admin rights

---

## 👨‍💻 Author

**Jayant Bhati**
🔗 [GitHub](https://github.com/jayant77778)
📧 [jai77bhati@gmail.com](mailto:jayant@gmail.com) 

---

## 📃 License

This project is licensed under the MIT License.

---

> 🔒 Face data never leaves your device. Everything is processed locally for privacy.

```

---

Would you like this saved directly as a `README.md` file or should I create a `.zip` version with the whole folder structure?
```
