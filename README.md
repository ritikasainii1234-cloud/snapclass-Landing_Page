# 🎓 SnapClass — AI-Powered Attendance System

### Modern, Responsive Landing Page for an AI-Based Attendance Management Platform

SnapClass is an AI-powered attendance management system designed to simplify classroom attendance using **Face Recognition, Voice Identification, and QR-Based Enrollment**.

This repository contains the **official landing page** of SnapClass, built using Flask, HTML, CSS, and JavaScript and deployed on Vercel.

## 🌐 Live Demo

🚀 **Landing Page:** https://snapclass-landing-page-pink.vercel.app/

🤖 **AI Attendance Application:** https://snapclass-maiin-6pri6vnhnd2usdb9cvbph2.streamlit.app/

💻 **Main Project Repository:** https://github.com/ritikasainii1234-cloud/SNAPCLASS-01

## ✨ Features

- **Modern UI:** Clean, professional landing page with a responsive design.
- **AI Face Recognition:** Introduces SnapClass's facial recognition attendance functionality.
- **Voice Identification:** Highlights voice-based attendance capabilities.
- **QR-Based Enrollment:** Explains the student enrollment workflow.
- **Teacher Journey:** Step-by-step visualization of the teacher dashboard and attendance process.
- **Student Journey:** Overview of enrollment and student-facing features.
- **Live Application Integration:** Direct navigation to the deployed Streamlit application.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling and responsive layouts |
| JavaScript | Frontend interactions |
| Python | Backend programming |
| Flask | Web application framework |
| Vercel | Hosting and deployment |
| GitHub | Version control |

## 📁 Project Structure

```text
SnapClass-Landing_Page/
│
├── app.py
├── requirements.txt
├── vercel.json
├── .gitignore
│
├── templates/
│   └── index.html
│
└── static/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── script.js
    └── img/
        └── ...
```

## ⚙️ Installation and Setup

**1. Clone the repository**

```bash
git clone https://github.com/ritikasainii1234-cloud/snapclass-Landing_Page.git
```

**2. Navigate to the project directory**

```bash
cd snapclass-Landing_Page
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Run the Flask application**

```bash
python app.py
```

**5. Open in your browser**

```text
http://127.0.0.1:5002
```

## 🚀 Deployment

The landing page is deployed on **Vercel** using its Python runtime.

The application uses `vercel.json` for deployment configuration and is connected to GitHub for automatic deployment when new changes are pushed.

## 🔗 Project Architecture

```text
             SnapClass Landing Page
                 (Vercel)
                    |
                    |
             Start AI Attendance
                    |
                    v
             SnapClass AI App
             (Streamlit Cloud)
                    |
          +---------+---------+
          |                   |
          v                   v
    Face Recognition    Voice Identification
          |                   |
          +---------+---------+
                    |
                    v
              Supabase Cloud
               (PostgreSQL)
```

## 🎯 Project Objective

To provide an accessible, visually engaging entry point to SnapClass, allowing educators and students to explore the platform's capabilities before accessing the AI-powered attendance application.

## 👩‍💻 Development

Developed as the frontend landing page for the **SnapClass AI-Powered Attendance Management System**.

---

⭐ If you find this project interesting, consider starring the repository!
