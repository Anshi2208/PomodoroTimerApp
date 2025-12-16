# 🍅 Pomodoro Timer App
A simple Pomodoro timer application built with **Qt** to help you manage focused work and break intervals using the **Pomodoro Technique** ⏱️.  

---

## ✨ Features
- **Intro Window** explaining the Pomodoro Technique and guiding the user 📖  
- **25-minute work timer** with **5-minute break timer** 🕒  
- **Progress bar** showing the remaining time visually 📊  
- Start, Stop, and Break buttons for full control ▶️⏸️🍵  
- Automatic enabling/disabling of buttons to prevent overlapping sessions ⚡  
- Simple and responsive UI design 🎨  

---

## 🚀 Usage
1. Launch the app — the **Intro Window** displays the Pomodoro technique and author information 🖥️  
2. Click **Start Timer** to begin a 25-minute work session ⏳  
3. When the work session ends, the **Break button** is enabled — click it to start a 5-minute break ☕  
4. Once the break finishes, the **Start button** is re-enabled for a new session 🔁  
5. Use the **Stop** button to pause the timer at any time ⏸️  
6. Repeat as needed for multiple work sessions 🔄  

---

## 🛠️ Tools & Technologies
- **Qt 5/6** – GUI framework for C++ 💻  
- **C++** – Core language for application logic 🧩  
- **QTimer** – Handles countdown functionality ⏱️  
- **QProgressBar** – Visual progress indicator 📊  
- **QPushButton/QLabel** – Interactive UI components 🔘  

---

## 📁 Project Structure
```bash
/headers
    IntroWindow.h
    PomodoroWindow.h
/src
    main.cpp
    IntroWindow.cpp
    PomodoroWindow.cpp
/Forms
    IntroWindow.ui
    PomodoroWindow.ui
PomodoroApp.pro
```

## Screenshots

**Intro Window:**  
<img width="858" height="640" alt="IntroWindow" src="https://github.com/user-attachments/assets/772e8084-f2bb-4201-b15a-2c7258c0735c" />

**Pomodoro Timer Window:**  
<img width="886" height="497" alt="Pomodoro Timer Window" src="https://github.com/user-attachments/assets/468e6e46-6e86-43ca-a52c-66ba5fd204b9" />

---
