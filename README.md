# 📋 Ultimate Checklist Automation (Google Sheets + Apps Script)

## 🚀 Overview

Ultimate Checklist Automation is a powerful Google Sheets–based system that simplifies task management, scheduling, and automatic email reminders.

This tool helps teams to:

* Assign tasks efficiently
* Plan daily, weekly, and monthly activities
* Send reminders for pending tasks
* Track performance and productivity

---

## 🎯 Features

✅ Task Assignment System
✅ Automated Task Scheduling (Daily / Weekly / Monthly / Quarterly)
✅ Email Reminder System (Auto Gmail Integration)
✅ Dashboard & MIS Reporting
✅ Archive System (Weekly Data Storage)
✅ Import Data from Another Sheet
✅ Custom Working Day Calendar Support

---

## 🧩 Project Structure

### 📄 Sheets Used:

| Sheet Name               | Purpose                          |
| ------------------------ | -------------------------------- |
| **Task List**            | Define tasks                     |
| **Master**               | Auto-generated scheduled tasks   |
| **Doer List**            | Employee Name, Department, Email |
| **Dashboard**            | MIS Report & Summary             |
| **Archive**              | Weekly data storage              |
| **Setup Sheet**          | Configuration (time, settings)   |
| **Working Day Calendar** | Define working days              |
| **Send Tasks To Doer**   | Email formatting sheet           |

---

## ⚙️ How It Works

1️⃣ Add tasks in the Task List sheet
2️⃣ The script automatically generates schedules
3️⃣ Tasks are created in the "Master" sheet
4️⃣ The system checks pending tasks daily
5️⃣ Reminder emails are sent automatically
6️⃣ The dashboard tracks performance

---

## 📧 Email Automation

* Automatic reminders for **next-day pending tasks**
* Task-wise email notifications
* Tasks shared in HTML table format

---

## 🛠️ Setup Instructions

### Step 1: Google Sheet Setup

* Create all required sheets (as per structure)
* Fill in Name, Department, and Email in the "Doer List"

---

### Step 2: Apps Script Setup

1. Open your Google Sheet
2. Go to Extensions → Apps Script
3. Paste the code
4. Save the project

---

### Step 3: Trigger Setup

Run the following function:

```javascript
setupSheet()
```

👉 This will set up the daily email trigger automatically

---

### Step 4: Permissions

* Allow Google permissions on first run
* Gmail access is required

---

## 🔑 Important Functions

| Function            | Purpose                     |
| ------------------- | --------------------------- |
| `createChecklist()` | Generate task schedules     |
| `sendReminder()`    | Send email reminders        |
| `fetchEmail()`      | Fetch email from Doer List  |
| `archive()`         | Store weekly data           |
| `sendToDoer()`      | Send task details via email |

---

## 📊 Use Cases

* Office Task Management
* MIS Reporting
* Daily Checklist Tracking
* Team Productivity Monitoring
* Operations Management

---

## ⚠️ Important Notes

* Ensure sheet names match exactly
* Email IDs must be correct
* Triggers must be properly set
* Script timezone should match your region

---

## 🧠 Future Improvements

* WhatsApp Integration
* Mobile Dashboard
* Role-based access
* UI Buttons & Automation Panel

---

## 📷 Screenshot

<img width="1575" height="911" alt="image" src="https://github.com/user-attachments/assets/31d44b50-1436-4635-a2b0-7d14df8c87af" />

---

## ⚠️ Note

This project uses **dummy/modified data** for portfolio purposes. No confidential company data is shared.

---

## 📫 Contact

* Name: Ashish Ranjan
* 📧 Email: [ashishranjan11211@gmail.com](mailto:ashishranjan11211@gmail.com)
* 🔗 LinkedIn: linkedin.com/in/ashishranjanji09

---

⭐ If you like this project, please give it a star!
