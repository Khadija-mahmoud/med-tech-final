# MEDTech Future

**MEDTech Future** is an innovative web application designed to monitor heart rate data, provide health insights, and ensure nighttime safety. The application allows users (patients and doctors) to schedule appointments, view heart rate statistics, play an interactive CPR game, and manage their profiles.

## Features

### 1. **User Authentication**
- Secure user registration and login functionality.
- Email verification for account activation.

### 2. **Schedule Management**
- Interactive calendar to manage appointments.
- Time-based scheduling.
- Automatic email reminders for upcoming appointments.

### 3. **Heart Rate Monitoring**
- Integration with Arduino ECG Heart Rate Monitor AD8232.
- Real-time heart rate data processing and storage.
- Alert system for irregular heart rate detection.

### 4. **Interactive CPR Game**
- Learn CPR timing through a fun, interactive game.
- Feedback on the click pace to ensure proper CPR timing.
- Multiple songs with BPM for practice.

### 5. **Health Insights Dashboard**
- Visual representation of daily and weekly heart rate trends.
- Alerts for abnormal heart rate readings.
- Patient-specific health insights.

### 6. **Admin Tools**
- Patient profile management.
- Access to patient records and schedules.
- Easy-to-use patient database management.

---

## Tech Stack

### **Frontend**
- HTML5, CSS3 (using Bootstrap for responsiveness).
- JavaScript (for interactive calendar and CPR game).
- Undraw illustrations and Animate.css for a modern look.

### **Backend**
- Flask (Python) for web application development.
- Flask-Mail for sending email alerts and notifications.

### **Database**
- MySQL for storing user, appointment, and heart rate data.
- SQLAlchemy ORM for database operations.

### **Hardware**
- Arduino ECG Heart Rate Monitor AD8232 for real-time heart rate monitoring.

---

## Installation Guide

### **Prerequisites**
- Python 3.9+
- MySQL
- Arduino ECG Heart Rate Monitor AD8232 (optional for heart rate monitoring features).

### **Steps**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/MEDTech-Future.git
   cd MEDTech-Future
