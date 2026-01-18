# ⚙️ Setup Guide

This guide explains how to set up and run the **Email-to-Calendar Automation** prototype.

---

## 📱 Required Apps and Tools

Ensure the following requirements are met before setup:

- Android smartphone
- MobileRun
- DroidRun APK (installed on the Android device)
- Gmail account (used to receive TPC emails)
- Google Calendar (used to store deadlines)

---

## 🛠️ Configuring MobileRun

1. Open **MobileRun** on your system.
2. Connect the Android device running **DroidRun APK**.
3. Create a new automation workflow.
4. Configure the workflow to:
   - Read emails from the Training and Placement Cell (TPC)
   - Filter emails based on a given input date
   - Identify placement or internship-related deadlines
   - Add deadlines to Google Calendar
5. Set a reminder **30 minutes before each deadline**.

---

## 🔐 Required Permissions

The following permissions must be granted:

### Outlook
- Read email content
- Access sender and subject details

### Google Calendar
- Create calendar events
- Set reminders and notifications

### Device Permissions
- Internet access
- Background execution
- Notification access (recommended)

---

## ▶️ Running the Automation

1. Ensure the Android device is connected and **DroidRun** is active.
2. Start the automation from **MobileRun**.
3. Emails from the specified input date will be scanned.
4. Relevant deadlines will be automatically added to Google Calendar.

---

## ⚠️ Note

This project is a **prototype** demonstrated using a limited dataset (for example, TPC emails from a specific date).  
The same setup can be extended to support continuous monitoring and real-time automation.

---
