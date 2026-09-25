# 🚒 Smart Fire-Fighting Robot (ATmega32A & ESP)

Welcome to the official repository for our graduation/team engineering project! This project implements an automated fire-fighting robot controlled by an **ATmega32A** microcontroller and integrated with an **ESP** module for Wi-Fi communication and monitoring.

---

## 📂 Project Structure

```text
Fire-Fighting-Robot/
├── firmware/
│   ├── atmega32a/          # Main microcontroller source code (AVR C)
│   └── esp_module/         # ESP Wi-Fi module code (IoT / Notifications)
├── hardware/
│   ├── schematics/         # Proteus simulation files (.pdsprj) & PCB layouts
│   └── wiring_diagram/     # Connection diagrams and pinouts
├── docs/                   # Datasheets and technical reports
└── README.md               # Project documentation

```
1. Clone the Repository (First Time Only)
Open your terminal/command prompt and clone the project:
git clone [https://github.com/mo-wesam-mecha2006/Fire-Fighting-Robot.git](https://github.com/mo-wesam-mecha2006/Fire-Fighting-Robot.git)
cd Fire-Fighting-Robot

2. Always Pull the Latest Changes Before Starting
Before writing any new code, make sure your local copy is up to date with main:
git checkout main
git pull origin main

3. Create a New Branch for Your Task
Create and switch to a new branch named after you or the feature you are working on (e.g., feature/sensors, feature/motor-control, Ali-code):
git checkout -b feature/your-name-task

4. Save and Push Your Work to Your Branch
After making changes or adding your code:
git add .
git commit -m "Brief description of what you did (e.g., added flame sensor driver)"
git push -u origin feature/your-name-task

