# 📋 Ultimate Checklist Automation (Google Sheets + Apps Script)

## 🚀 Overview

Ultimate Checklist Automation is a powerful Google Sheets–based system that simplifies task management, scheduling, and automatic email reminders.

This tool helps teams to:

* Tasks assign karne me
* Daily / Weekly / Monthly planning me
* Pending tasks ke reminders bhejne me
* Performance track karne me

---

## 🎯 Features

✅ Task Assignment System
✅ Automated Task Scheduling (Daily / Weekly / Monthly / Quarterly)
✅ Email Reminder System (Auto Gmail Integration)
✅ Dashboard & MIS Reporting
✅ Archive System (Weekly Data Storage)
✅ Import Old Data from Another Sheet
✅ Custom Working Day Calendar Support

---

## 🧩 Project Structure

### 📄 Sheets Used:

| Sheet Name               | Purpose                          |
| ------------------------ | -------------------------------- |
| **Task List**            | Task define karne ke liye        |
| **Master**               | Auto-generated scheduled tasks   |
| **Doer List**            | Employee Name, Department, Email |
| **Dashboard**            | MIS Report & Summary             |
| **Archive**              | Weekly data storage              |
| **Setup Sheet**          | Configuration (time, settings)   |
| **Working Day Calendar** | Working days define              |
| **Send Tasks To Doer**   | Email format sheet               |

---

## ⚙️ How It Works

1️⃣ Task List me task add karo
2️⃣ Script automatically schedule create karta hai
3️⃣ Tasks "Master Sheet" me generate hote hain
4️⃣ System daily check karta hai pending tasks
5️⃣ Reminder emails automatically send hote hain
6️⃣ Dashboard performance track karta hai

---

## 📧 Email Automation

* Automatic reminder for **next day pending tasks**
* Task-wise email notification
* HTML table format me task sharing

---

## 🛠️ Setup Instructions

### Step 1: Google Sheet Setup

* Sab required sheets create karo (as per structure)
* "Doer List" me Name, Department, Email fill karo

### Step 2: Apps Script Setup

1. Google Sheet open karo
2. Extensions → Apps Script
3. Code paste karo
4. Save karo

---

### Step 3: Trigger Setup

Run karo:

```javascript
setupSheet()
```

👉 Ye automatic daily email trigger set karega

---

### Step 4: Permissions

* First run me Google permissions allow karo
* Gmail access required hai

---

## 🔑 Important Functions

| Function            | Purpose                    |
| ------------------- | -------------------------- |
| `createChecklist()` | Task schedule generate     |
| `sendReminder()`    | Email reminder send        |
| `fetchEmail()`      | Email fetch from Doer List |
| `archive()`         | Weekly data store          |
| `sendToDoer()`      | Task email send            |

---

## 📊 Use Cases

* Office Task Management
* MIS Reporting
* Daily Checklist Tracking
* Team Productivity Monitoring
* Operations Management

---

## ⚠️ Important Notes

* Ensure sheet names exactly same ho
* Email IDs correct hone chahiye
* Triggers properly set hone chahiye
* Script timezone match kare

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
- Name: Ashish Ranjan 
- 📧 Email: ashishranjan11211@gmail.com  
- 🔗 LinkedIn: linkedin.com/in/ashishranjanji09

---

⭐ If you like this project, give it a star!
