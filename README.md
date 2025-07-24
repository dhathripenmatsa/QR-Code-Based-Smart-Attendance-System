# QR Code-Based Smart Attendance System
## 🚀 Demo

👉 [Click here to launch the Streamlit demo](https://dhathripenmatsa-qr-code-attendance-system-streamlit-app-qvrslt.streamlit.app/)

A Python-based smart attendance system that uses QR code scanning via webcam to automate attendance tracking. This project is ideal for schools, colleges, and organizations looking for a simple and efficient attendance solution.

---

## 📌 Features

- 🎥 Real-time webcam detection using OpenCV
- 🔍 Scans QR codes assigned to individuals (e.g., students/employees)
- 📝 Records attendance in `attendance.csv`
- 🔁 Ignores duplicate scans
- 📅 Auto-generates daily summary report
- 📤 Exports summary in both `.csv` and `.txt` formats
- ✅ Simple interface, easy to extend

---

## 🧰 Technologies Used

- Python 3.x
- OpenCV
- Pandas
- CSV file handling

---

🚀 How to Run
- Step 1: Generate QR Codes
- Run this script to generate unique QR codes for each individual:
- python qr_generator.py
- Step 2: Start Attendance Scanner
- Use the webcam to scan QR codes and record attendance:
- python scanner.py
- Step 3: Check Attendance Logs
- Attendance data will be saved in Attendance/ folder with the current date.

## 📁 Project Structure

📂 QR_Attendance_System/  
├── scanner.py               → Main QR code scanner  
├── summary_report.py        → Script to generate daily summary  
├── attendance.csv           → Logs scanned names & timestamps  
├── summary_report.txt       → Plain text report of daily attendance  
├── summary_report.csv       → CSV version of the report  
├── qrcodes/                 → Folder containing student QR codes  
└── README.md                → Project documentation  


---

## 👩‍💻 Author

**dhathripenmatsa**  
[GitHub Profile](https://github.com/dhathripenmatsa)
