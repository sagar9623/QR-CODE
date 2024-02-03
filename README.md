# QR Code (Quick Attendance)

## Introduction
- Simplifies attendance taking for teachers/professors in the ISE department.
- Replaces time-consuming traditional attendance methods with a quick, digital solution.
- Utilizes QR codes for efficient student attendance marking.

## Features
- **Quick Attendance:** Students can mark their attendance in seconds by scanning a QR code.
- **Secure Login:** Attendance marking requires students to scan the QR code using their college ID logged in their mobiles.
- **Real-Time Updates:** Attendance data is instantly updated and displayed on a Google Sheet on the teacher's/professor's laptop.
- **Detailed Records:** The data includes Student Name, USN (University Serial Number), and Time of attendance.

## How It Works
1. **QR Code Display:** Teachers/professors display a unique QR code at the start of the class.
2. **Student Scan:** Students scan the QR code using their mobile cameras while logged in with their college IDs.
3. **Attendance Marking:** Upon scanning, students' attendance is marked.
4. **Data Sync:** Attendance records are immediately updated on a designated Google Sheet.

## Technology Stack
- **QR Code Generation:** Python scripts for creating unique QR codes for each session.
- **Data Management:** Google Sheets for storing and displaying attendance data in real-time.
- **Security:** College ID-based login system for verifying student identities during attendance marking.

## Getting Started
(Here, provide instructions on how to set up and run the project, including any requirements, installation steps, and usage guidelines.)

### Prerequisites
- Python installed on the system for QR code generation.
- Access to Google Sheets API for data integration.

### Usage
- Run the QR code generation script: `python generate_qr.py`
- Display the generated QR code to students for attendance.
- Monitor the Google Sheet for real-time attendance data.
