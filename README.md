# 🎓 AI Attendance System (Face + Voice Recognition)

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![Flask](https://img.shields.io/badge/Flask-Landing-black)
![Supabase](https://img.shields.io/badge/Database-Supabase-green)
![AI](https://img.shields.io/badge/AI-Face%20%2B%20Voice-purple)
![License](https://img.shields.io/badge/License-MIT-yellow)

A **modern AI-powered attendance system** that uses **Face Recognition and Voice Recognition** to automate classroom attendance.

The project consists of two parts:

1️⃣ **Landing Website** – Project introduction and demo showcase
2️⃣ **Main AI App** – Streamlit application for teachers and students

---

# 🚀 Features

### 🎓 Teacher Features

- Create subjects/courses
- Share enrollment link or QR code
- View attendance records
- Start **face recognition attendance**
- Start **voice recognition attendance**
- Manage enrolled students

### 👨‍🎓 Student Features

- Join subjects using QR code or link
- Upload face photo
- Enroll voice profile
- Mark attendance using face or voice

### 🤖 AI Features

- **Face Recognition** using `dlib`
- **Voice Recognition** using `Resemblyzer`
- Real-time processing pipelines
- Embedding based identity matching

### 📊 Database

- Cloud database powered by **Supabase**
- Stores:
  - Students
  - Subjects
  - Attendance logs
  - Face embeddings
  - Voice embeddings

---

# 🏗️ Project Architecture

```
Project Codebase
│
├── ai-attendance-project-app-main
│   ├── src
│   │   ├── components
│   │   ├── database
│   │   ├── pipelines
│   │   ├── screens
│   │   └── ui
│   ├── app.py
│   └── requirements.txt
│
└── ai-attendance-project-landing-main
    ├── templates
    ├── static
    ├── app.py
    └── requirements.txt
```

# File Tree: Project Intelligent AI Attendance - Face & Voice: Codebase

**Generated:** 4/19/2026, 5:35:25 PM
**Root Path:** `e:\AI Projects Module - Apna Collage\Intelligent AI Attendance - Face & Voice\Project Codebase`

```
├── 📁 ai-attendance-project-app-main
│   ├── 📁 src
│   │   ├── 📁 components
│   │   │   ├── 🐍 dialog_add_photo.py
│   │   │   ├── 🐍 dialog_attendance_results.py
│   │   │   ├── 🐍 dialog_auto_enroll.py
│   │   │   ├── 🐍 dialog_create_subject.py
│   │   │   ├── 🐍 dialog_enroll.py
│   │   │   ├── 🐍 dialog_share_subject.py
│   │   │   ├── 🐍 dialog_voice_attendance.py
│   │   │   ├── 🐍 footer.py
│   │   │   ├── 🐍 header.py
│   │   │   └── 🐍 subject_card.py
│   │   ├── 📁 database
│   │   │   ├── 🐍 config.py
│   │   │   └── 🐍 db.py
│   │   ├── 📁 pipelines
│   │   │   ├── 🐍 face_pipeline.py
│   │   │   └── 🐍 voice_pipeline.py
│   │   ├── 📁 screens
│   │   │   ├── 🐍 home_screen.py
│   │   │   ├── 🐍 student_screen.py
│   │   │   └── 🐍 teacher_screen.py
│   │   └── 📁 ui
│   │       └── 🐍 base_layout.py
│   ├── 📝 README.md
│   ├── 🐍 app.py
│   └── 📄 requirements.txt
└── 📁 ai-attendance-project-landing-main
    ├── 📁 static
    │   ├── 📁 css
    │   │   └── 🎨 style.css
    │   ├── 📁 fonts
    │   │   └── 📄 chison.ttf
    │   ├── 📁 img
    │   │   ├── 📁 demo
    │   │   │   ├── 🖼️ snap-landing.png
    │   │   │   ├── 🖼️ snap-student-flow-1-login.png
    │   │   │   ├── 🖼️ snap-student-flow-2-enroll.png
    │   │   │   ├── 🖼️ snap-student-flow-3-dashboard.png
    │   │   │   ├── 🖼️ snap-student.png
    │   │   │   ├── 🖼️ snap-teacher-flow-1-login.png
    │   │   │   ├── 🖼️ snap-teacher-flow-2-dashboard.png
    │   │   │   ├── 🖼️ snap-teacher-flow-3-create-course.png
    │   │   │   ├── 🖼️ snap-teacher-flow-4-share-qr-or-link.png
    │   │   │   ├── 🖼️ snap-teacher-flow-5-see-stored-records.png
    │   │   │   ├── 🖼️ snap-teacher-flow-5.1-voice-attendance.png
    │   │   │   ├── 🖼️ snap-teacher-flow-5.2-photo-attendance.png
    │   │   │   └── 🖼️ snap-teacher.png
    │   │   ├── 🖼️ apna_college.png
    │   │   ├── 🖼️ apnacollege.png
    │   │   ├── 🖼️ app_logo.png
    │   │   └── 🖼️ logo.png
    │   └── 📁 js
    │       └── 📄 script.js
    ├── 📁 templates
    │   └── 🌐 index.html
    ├── 📝 README.md
    ├── 🐍 app.py
    ├── 📄 requirements.txt
    └── ⚙️ vercel.json
```

---

_Generated by FileTree Pro Extension_

---

# 🧠 System Flow

```
Landing Page
      │
      ▼
User enters AI Attendance App
      │
      ▼
Choose Login Type
  ├── Teacher
  └── Student
      │
      ▼
Database (Supabase)
      │
      ▼
AI Pipelines
  ├── Face Recognition
  └── Voice Recognition
      │
      ▼
Attendance Recorded
```

---

# 🖥️ Tech Stack

### Frontend / UI

- Streamlit
- HTML
- CSS
- JavaScript

### Backend

- Python
- Flask
- Gunicorn

### AI / Machine Learning

- dlib
- scikit-learn
- Resemblyzer
- Librosa

### Image & Audio Processing

- Pillow
- NumPy
- Pandas

### Database

- Supabase

### Utilities

- bcrypt
- segno (QR generation)

---

# 📦 Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/ai-attendance-system.git

cd ai-attendance-system
```

---

# 🖥️ Run the Landing Website

Navigate to the landing folder:

```bash
cd ai-attendance-project-landing-main
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the server:

```bash
flask run
```

The landing page will run at:

```
http://localhost:5000
```

---

# 🤖 Run the AI Attendance App

Navigate to the app folder:

```bash
cd ai-attendance-project-app-main
```

Create virtual environment:

```bash
python -m venv venv
```

Activate environment:

### Windows

```bash
venv\Scripts\activate
```

### Mac/Linux

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the app:

```bash
streamlit run app.py
```

The app will open at:

```
http://localhost:8501
```

---

# 🧩 Main Components

### Components

Reusable UI elements

```
components/
├── header.py
├── footer.py
├── subject_card.py
└── dialog_*.py
```

### Screens

Main application pages

```
screens/
├── home_screen.py
├── teacher_screen.py
└── student_screen.py
```

### Pipelines

AI recognition pipelines

```
pipelines/
├── face_pipeline.py
└── voice_pipeline.py
```

### Database

Supabase configuration and queries

```
database/
├── config.py
└── db.py
```

---

# 📸 Face Recognition Pipeline

Steps:

1️⃣ Capture face image
2️⃣ Detect face using **dlib**
3️⃣ Generate **face embeddings**
4️⃣ Compare with stored embeddings
5️⃣ Identify student
6️⃣ Mark attendance

---

# 🎙️ Voice Recognition Pipeline

Steps:

1️⃣ Record voice sample
2️⃣ Extract voice features with **Librosa**
3️⃣ Generate **voice embeddings** using **Resemblyzer**
4️⃣ Compare embeddings with stored profiles
5️⃣ Identify student
6️⃣ Mark attendance

---

# 🔐 Environment Variables

Create `.env` file in the app folder:

```
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
```

---

# 📷 Demo Screens

Teacher Dashboard
Student Dashboard
Face Attendance
Voice Attendance

(See images in `/static/img/demo`)
Will update soon.

---

# 🚀 Deployment

Possible deployment architecture:

```
Landing Website → Vercel
AI App → Streamlit Cloud
Database → Supabase
```

---

# 🛠️ Future Improvements

- Mobile support
- Liveness detection
- Face anti-spoofing
- Voice noise reduction
- Multi-classroom support
- Admin dashboard
- Attendance analytics

---

# 🤝 Contributing

Pull requests are welcome.

For major changes, please open an issue first to discuss the proposed changes.

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

Satinder Singh Sall
AI / ML
Full-Stack Web & Mobile Engineer

Developed as part of the **AI Projects Module**

---

# ⭐ If you like this project

Give it a ⭐ on GitHub and share it with others!

---

# 🎓 AI Attendance System

### Face Recognition & Voice Biometrics for Automated Classroom Attendance

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Streamlit](https://img.shields.io/badge/UI-Streamlit-red)
![Flask](https://img.shields.io/badge/Landing-Flask-black)
![Supabase](https://img.shields.io/badge/Database-Supabase-green)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Face%20%2B%20Voice-purple)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Active-success)

---

# 📑 Table of Contents

1. Overview
2. Motivation
3. System Architecture
4. Technology Stack
5. AI Models and Pipelines
6. Project Structure
7. Installation Guide
8. Running the Applications
9. Database Architecture
10. Research Methodology
11. Deployment Architecture
12. Future Work
13. License
14. Author

---

# 1️⃣ Overview

The **AI Attendance System** is a modern intelligent classroom attendance platform that leverages **biometric AI technologies** to automate student attendance.

The system uses:

- **Face Recognition**
- **Voice Recognition**
- **QR-based enrollment**
- **Cloud database integration**

to create a **secure, scalable, and automated attendance management system**.

The project is divided into two major components:

| Component                 | Description                                         |
| ------------------------- | --------------------------------------------------- |
| Landing Website           | Informational webpage for project showcase          |
| AI Attendance Application | Core attendance system using biometric verification |

---

# 2️⃣ Motivation

Traditional attendance systems suffer from several issues:

- Manual record keeping
- Proxy attendance
- Time-consuming processes
- Lack of automation

Biometric recognition provides a **secure and efficient alternative**.

This project aims to demonstrate how **AI-based biometric verification** can be integrated into a modern cloud-based attendance platform.

---

# 3️⃣ System Architecture

```
                       ┌─────────────────────┐
                       │     Landing Page     │
                       │      (Flask)         │
                       └──────────┬───────────┘
                                  │
                                  ▼
                       ┌─────────────────────┐
                       │   Streamlit App      │
                       │  (AI Attendance UI)  │
                       └──────────┬───────────┘
                                  │
             ┌────────────────────┼───────────────────┐
             ▼                    ▼                   ▼
      ┌──────────────┐   ┌──────────────┐   ┌──────────────┐
      │ Face Pipeline│   │Voice Pipeline│   │ QR Enrollment│
      └──────┬───────┘   └──────┬───────┘   └──────┬───────┘
             │                  │                  │
             ▼                  ▼                  ▼
        ┌─────────────────────────────────────────────┐
        │             Supabase Database                │
        │  Students | Subjects | Attendance Records    │
        └─────────────────────────────────────────────┘
```

---

# 4️⃣ Technology Stack

### Frontend / UI

- Streamlit
- HTML
- CSS
- JavaScript

### Backend

- Python
- Flask
- Gunicorn

### Machine Learning

| Technology   | Purpose                    |
| ------------ | -------------------------- |
| dlib         | Face recognition           |
| scikit-learn | similarity computation     |
| Resemblyzer  | voice embedding generation |
| Librosa      | audio feature extraction   |

### Data Processing

- NumPy
- Pandas
- Pillow

### Database

- Supabase

### Security & Utilities

- bcrypt
- segno (QR code generation)

---

# 5️⃣ AI Models and Pipelines

## Face Recognition Pipeline

The face recognition system operates using embedding-based biometric identification.

### Process

1. Capture image from camera
2. Detect face using **dlib**
3. Generate **face embedding**
4. Compare embedding with stored embeddings
5. Identify student
6. Record attendance

```
Camera Input
      │
      ▼
Face Detection
      │
      ▼
Embedding Generation
      │
      ▼
Similarity Matching
      │
      ▼
Student Identification
      │
      ▼
Attendance Record
```

---

## Voice Recognition Pipeline

Voice identification is implemented using **speaker embeddings**.

### Process

1. Record voice sample
2. Extract audio features using **Librosa**
3. Generate speaker embedding using **Resemblyzer**
4. Compare with stored embeddings
5. Identify student
6. Record attendance

```
Audio Input
     │
     ▼
Feature Extraction
     │
     ▼
Speaker Embedding
     │
     ▼
Similarity Comparison
     │
     ▼
Identity Verification
     │
     ▼
Attendance Logged
```

---

# 6️⃣ Project Structure

```
Project Codebase
│
├── ai-attendance-project-app-main
│   ├── src
│   │   ├── components
│   │   │   ├── dialog_*.py
│   │   │   ├── header.py
│   │   │   └── footer.py
│   │   │
│   │   ├── database
│   │   │   ├── config.py
│   │   │   └── db.py
│   │   │
│   │   ├── pipelines
│   │   │   ├── face_pipeline.py
│   │   │   └── voice_pipeline.py
│   │   │
│   │   ├── screens
│   │   │   ├── home_screen.py
│   │   │   ├── teacher_screen.py
│   │   │   └── student_screen.py
│   │   │
│   │   └── ui
│   │       └── base_layout.py
│   │
│   ├── app.py
│   └── requirements.txt
│
└── ai-attendance-project-landing-main
    ├── templates
    ├── static
    ├── app.py
    └── requirements.txt
```

# File Tree: Project Intelligent AI Attendance - Face & Voice: Codebase

**Generated:** 4/19/2026, 5:35:25 PM
**Root Path:** `e:\AI Projects Module - Apna Collage\Intelligent AI Attendance - Face & Voice\Project Codebase`

```
├── 📁 ai-attendance-project-app-main
│   ├── 📁 src
│   │   ├── 📁 components
│   │   │   ├── 🐍 dialog_add_photo.py
│   │   │   ├── 🐍 dialog_attendance_results.py
│   │   │   ├── 🐍 dialog_auto_enroll.py
│   │   │   ├── 🐍 dialog_create_subject.py
│   │   │   ├── 🐍 dialog_enroll.py
│   │   │   ├── 🐍 dialog_share_subject.py
│   │   │   ├── 🐍 dialog_voice_attendance.py
│   │   │   ├── 🐍 footer.py
│   │   │   ├── 🐍 header.py
│   │   │   └── 🐍 subject_card.py
│   │   ├── 📁 database
│   │   │   ├── 🐍 config.py
│   │   │   └── 🐍 db.py
│   │   ├── 📁 pipelines
│   │   │   ├── 🐍 face_pipeline.py
│   │   │   └── 🐍 voice_pipeline.py
│   │   ├── 📁 screens
│   │   │   ├── 🐍 home_screen.py
│   │   │   ├── 🐍 student_screen.py
│   │   │   └── 🐍 teacher_screen.py
│   │   └── 📁 ui
│   │       └── 🐍 base_layout.py
│   ├── 📝 README.md
│   ├── 🐍 app.py
│   └── 📄 requirements.txt
└── 📁 ai-attendance-project-landing-main
    ├── 📁 static
    │   ├── 📁 css
    │   │   └── 🎨 style.css
    │   ├── 📁 fonts
    │   │   └── 📄 chison.ttf
    │   ├── 📁 img
    │   │   ├── 📁 demo
    │   │   │   ├── 🖼️ snap-landing.png
    │   │   │   ├── 🖼️ snap-student-flow-1-login.png
    │   │   │   ├── 🖼️ snap-student-flow-2-enroll.png
    │   │   │   ├── 🖼️ snap-student-flow-3-dashboard.png
    │   │   │   ├── 🖼️ snap-student.png
    │   │   │   ├── 🖼️ snap-teacher-flow-1-login.png
    │   │   │   ├── 🖼️ snap-teacher-flow-2-dashboard.png
    │   │   │   ├── 🖼️ snap-teacher-flow-3-create-course.png
    │   │   │   ├── 🖼️ snap-teacher-flow-4-share-qr-or-link.png
    │   │   │   ├── 🖼️ snap-teacher-flow-5-see-stored-records.png
    │   │   │   ├── 🖼️ snap-teacher-flow-5.1-voice-attendance.png
    │   │   │   ├── 🖼️ snap-teacher-flow-5.2-photo-attendance.png
    │   │   │   └── 🖼️ snap-teacher.png
    │   │   ├── 🖼️ apna_college.png
    │   │   ├── 🖼️ apnacollege.png
    │   │   ├── 🖼️ app_logo.png
    │   │   └── 🖼️ logo.png
    │   └── 📁 js
    │       └── 📄 script.js
    ├── 📁 templates
    │   └── 🌐 index.html
    ├── 📝 README.md
    ├── 🐍 app.py
    ├── 📄 requirements.txt
    └── ⚙️ vercel.json
```

---

_Generated by FileTree Pro Extension_

---

# 7️⃣ Installation Guide

Clone the repository:

```bash
git clone https://github.com/yourusername/ai-attendance-system.git
cd ai-attendance-system
```

---

# 8️⃣ Running the Applications

## Run Landing Website

```
cd ai-attendance-project-landing-main
pip install -r requirements.txt
flask run
```

Access:

```
http://localhost:5000
```

---

## Run AI Attendance App

```
cd ai-attendance-project-app-main
```

Create environment

```
python -m venv venv
```

Activate environment

Windows

```
venv\Scripts\activate
```

Install dependencies

```
pip install -r requirements.txt
```

Run application

```
streamlit run app.py
```

Access:

```
http://localhost:8501
```

---

# 9️⃣ Database Architecture

The system uses **Supabase** as the cloud database.

### Core Tables

| Table       | Purpose                     |
| ----------- | --------------------------- |
| students    | registered student profiles |
| subjects    | courses created by teachers |
| enrollments | student course enrollments  |
| attendance  | attendance records          |
| embeddings  | face & voice embeddings     |

---

# 🔬 10️⃣ Research Methodology

The system follows a **biometric verification pipeline** based on embedding similarity.

Key methodology components:

- Deep feature extraction
- Embedding representation
- Cosine similarity comparison
- Threshold-based identity verification

This approach ensures:

- High recognition accuracy
- Fast inference time
- Scalable biometric matching

---

# ☁️ 11️⃣ Deployment Architecture

Recommended deployment stack:

```
Landing Website → Vercel
AI Attendance App → Streamlit Cloud
Database → Supabase
```

---

# 🚀 12️⃣ Future Work

Potential improvements include:

- Face **liveness detection**
- Anti-spoofing protection
- Multi-classroom attendance
- Attendance analytics dashboard
- Mobile application
- Edge AI inference

---

# 📜 13️⃣ License

This project is licensed under the **MIT License**.

---

# 👨‍💻 14️⃣ Author

Satinder Singh Sall
AI / ML
Full-Stack Web & Mobile Engineer

Developed as part of the **AI Projects Module**

---

⭐ If you found this project useful, please consider giving it a star on GitHub.

---
