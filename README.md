# TELCMock_BSLEU_Akademie
A secure web-based TELC exam system with timed modules, audio-enabled listening, drag-and-drop reading tasks, writing interface, autosave, and API integration. Designed for smooth, reliable, and distraction-free digital examinations.

BSLEU–TELC Computer-Based Exam System

A secure, modern, and fully interactive web-based examination platform designed to deliver TELC-style computer-based assessments. Developed by Sovir Technologies LLP, this system ensures smooth, reliable, and distraction-free digital exams for candidates.

Key Features

Secure Access Flow
Code-based entry with a virtual numeric keyboard for controlled exam-hall access.

Multi-Module Exam Delivery

📖 Reading: MCQ, drag-and-drop, fill-in-the-blank
🎧 Listening: Audio-synced questions with fixed bottom audio bar
✍️ Writing: Clean editor with autosave

⏱ Timed Sessions & Auto-Submit
Each module includes countdown timers with enforced submission.

💾 Smart Autosave Engine
Every answer is saved in real time with a safe queue system to prevent data loss.

📡 Backend Integration
Works with Google Apps Script or any REST API for login, question fetch, autosave, and submission.

📱 Responsive, Exam-Safe Interface
Minimal distractions, no external navigation, optimized for desktops & exam labs.

📁 Project Structure
/project-root
│── index.html      # Secure access screen (code-based login)
│── exam.html       # Full multi-module exam engine
│── README.md       # Documentation file
│── assets/         # Branding, images, icons (optional)

🔧 Setup & Configuration
1️⃣ Set Your API Endpoint
Open exam.html and replace:
const BASE_API = "YOUR_API_ENDPOINT";

2️⃣ Deploy Backend
Use Google Apps Script or any custom backend to support:
/auth/login
/assignment/get
/papers/get
/response/save
/module/submit
/scores/get

3️⃣ Run Locally or Host Online
Host using:
GitHub Pages
Netlify
Vercel
Custom server
The platform automatically enters demo mode if no API is provided.

🧪 Demo Login (Test Mode)
Email: demo@bsleu.test
Password: demo

📸 Recommended Screenshots (Optional)
You can add:
Access screen (index.html)
Login / Code modal
Reading module
Listening audio bar
Writing interface

👨‍💻 Author
Sohan Dsouza
Sovir Technologies LLP

📄 License
Proprietary software © Sovir Technologies LLP.
For licensing or customization, contact the development team.
