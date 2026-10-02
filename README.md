# 🔥 FireGuard — Smart Industrial Fire Detection System

FireGuard is a smart fire detection and monitoring system designed to help detect potential fire and smoke situations in industrial environments.

The project combines **Python, computer vision, web technologies, and database management** to provide a monitoring interface and record fire-related detection data.

## 🚀 Features

* 🔥 Fire detection
* 💨 Smoke detection
* 🌡️ Temperature monitoring
* 🚨 Fire and smoke alerts
* 📊 Web-based monitoring dashboard
* 💾 Database storage for detection-related data
* 🖥️ Real-time monitoring interface

## 🛠️ Technologies Used

* **Python**
* **OpenCV**
* **HTML**
* **CSS**
* **JavaScript**
* **SQLite**
* **ESP32**
* **Computer Vision**

## 🧠 Detection Approach

FireGuard uses computer vision techniques to analyze camera input and identify visual patterns associated with fire and smoke.

The project includes:

* **MOG2 background subtraction** for detecting movement and changes in the camera feed.
* **HSV-based color detection** for identifying fire-like orange/yellow regions.
* **Temperature monitoring** for detecting high-temperature conditions.
* **ESP32 integration** for sensor-related data.

## 🌐 Web Interface

The project includes a web-based interface built using:

* `index.html` — webpage structure
* `style.css` — interface styling
* `app.js` — frontend JavaScript functionality

The backend is handled by `server.py`.

## 🗄️ Database

FireGuard uses a database to store project-related information.

### Database files

* `fire.db` — SQLite database
* `schema.sql` — database schema

## 📁 Project Structure

```text
FireGuard-Smart-Industrial-Fire-Detection-System/
│
├── fire.db
├── schema.sql
├── server.py
├── app.js
├── index.html
├── style.css
└── README.md
```

## 🎯 Project Objective

The main objective of FireGuard is to develop a practical system for **early fire detection and monitoring** by combining computer vision, sensor data, and a web-based interface.

The project explores how software and hardware components can work together to monitor potentially dangerous conditions.

## 🔮 Future Improvements

* Improve smoke detection accuracy
* Reduce false alerts caused by normal movement
* Improve detection under different lighting conditions
* Add more sensor inputs
* Improve notification and alert mechanisms
* Enhance the monitoring dashboard
* Deploy the system for continuous industrial monitoring

## 👩‍💻 Author

**Drishti Verma**

BTech CSE
