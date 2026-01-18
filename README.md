# Email-to-Calendar Automation

## Overview

Email-to-Calendar Automation is a prototype project designed to help students avoid missing important internship and placement deadlines sent through email by the Training and Placement Cell (TPC).

Students often receive a large number of emails every day, which makes it easy to overlook important placement-related messages. This project automatically converts such emails into Google Calendar events with reminders, ensuring deadlines are not missed.

---

## Problem Statement

- Placement and internship updates are shared via email  
- Important deadlines are often missed due to inbox overload  
- Students forget to manually add deadlines to calendars  
- Missing deadlines can lead to lost opportunities  

---

## Solution

This automation system:
- Reads emails sent by the Training and Placement Cell  
- Filters internship and placement-related emails  
- Extracts deadline information from the email content  
- Automatically adds deadlines to Google Calendar  
- Sets a reminder 30 minutes before each deadline  

Once configured, the system runs automatically with minimal user intervention.

---

## Tools and Technologies Used

MobileRun  
Used to create and manage the automation workflow, including email reading, processing, and calendar integration.

DroidRun APK  
Runs the MobileRun automation on an Android device and acts as the execution environment.

Email (TPC Emails)  
The source of placement and internship notifications scanned by the automation.

Google Calendar  
Stores the extracted deadlines and sends reminder notifications.

---

## Workflow Explanation

1. The user provides an input date from which emails should be scanned.
2. The automation scans the inbox for emails sent by the Training and Placement Cell.
3. Relevant placement and internship emails are identified.
4. The email content is read to find deadline information.
5. A Google Calendar event is created for the detected deadline.
6. A reminder notification is set 30 minutes before the deadline.
7. The user receives a calendar alert before the deadline.

---

## Prototype Details

- This project is a prototype implementation.
- For demonstration purposes, a limited dataset is used.
- Example: Emails sent by TPC on 15th January 2026 are scanned.
- The prototype demonstrates the core logic and workflow of the system.
- The same logic can be extended for continuous monitoring and real-time use.

---

## Future Enhancements

- Continuous real-time email monitoring  
- Support for multiple email sources  
- Improved deadline extraction  
- Custom reminder timings  
- Scalable deployment beyond mobile execution  

---

## Contributors

- Vamsi  
- Tanvi  

---

## Conclusion

This project demonstrates how automation can simplify deadline management for students. By converting important emails into calendar events with reminders, it reduces manual effort and helps ensure that important placement and internship opportunities are not missed.
