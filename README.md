# 🛡️ User Activity Monitoring & Analysis Tool

A Python-based user activity monitoring and analysis tool designed for cybersecurity learning, digital investigation research, and security awareness. The project demonstrates how user activity data can be collected, logged, and analyzed in a controlled and authorized environment.

---

## 📌 Features

✅ Records keyboard activity with timestamps

✅ Captures periodic screenshots for activity monitoring

✅ Collects system information (IP address, hostname, OS details, username)

✅ Records microphone audio samples

✅ Automatically sends activity reports via email

✅ Maintains activity logs for security analysis

✅ Demonstrates monitoring and logging techniques used in cybersecurity investigations

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries & Modules

* **pynput** → Keyboard activity monitoring
* **Pillow (PIL)** → Screenshot capture
* **sounddevice** → Audio recording
* **scipy.io.wavfile** → Audio file processing
* **smtplib & email** → Automated email reporting
* **requests** → IP information retrieval
* **platform** → Operating system information
* **getpass** → User information collection
* **datetime** → Timestamp generation

---

## 📦 Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Bhavdiprathwa/User-Activity-Monitoring-And-Analysis-Tool.git
cd User-Activity-Monitoring-And-Analysis-Tool
```

### 2️⃣ Install Dependencies

```bash
pip install pynput Pillow sounddevice scipy requests
```

### 3️⃣ Configure Email Settings

Update your sender email and app password inside the script.

For Gmail:

* Enable Two-Factor Authentication (2FA)
* Generate an App Password
* Use the generated App Password in the script

### 4️⃣ Run the Application

```bash
python main.py
```

---

## 🎯 Project Objective

This project was developed to understand and demonstrate:

* User activity monitoring concepts
* Security logging mechanisms
* Digital investigation techniques
* Data collection and reporting workflows
* Python automation in cybersecurity

---

## ⚠️ Disclaimer

This project is intended strictly for educational, research, and authorized security testing purposes only.

The author does not encourage or support unauthorized monitoring of systems, devices, or individuals. Users are solely responsible for ensuring compliance with applicable laws, regulations, and organizational policies.

---

## 👨‍💻 Author

**Bhavdip Rathwa**

📧 Email: [bhavdiprathwa728@gmail.com](mailto:bhavdiprathwa728@gmail.com)

🔗 GitHub: https://github.com/Bhavdiprathwa

🔗 LinkedIn: Add Your LinkedIn Profile

---

⭐ If you found this project useful, consider giving it a star.
