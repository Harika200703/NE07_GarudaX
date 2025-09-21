# NE07_GarudaX
Develop an AI-powered smart attendance system: where a single classroom image can be used to automatically mark attendance for all students present. The system should accurately recognize faces, handle multiple students in one frame, and generate attendance reports.

smart_attendance/
│
├── app.py                  # Main Flask code
├── attendance_history.json # Auto-generated
├── teachers.json           # Auto-generated
├── ImagesAttendance/       # CSV images folder
│
├── templates/
│   ├── login.html
│   ├── signup.html
│   ├── index.html           # Teacher dashboard (existing)
│   └── student_dashboard.html
│
└── static/
    ├── style.css
    ├── script.js
    └── AttendanceGraphs/
