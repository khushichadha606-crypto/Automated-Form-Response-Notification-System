# Automated-Form-Response-Notification-System
Project Overview
This project demonstrates an end-to-end automation workflow that collects user responses from a Google Form, stores them in Google Sheets, and automatically sends a confirmation message via Gmail using n8n automation tool.

Workflow Explanation
1️. Data Collection – Google Forms

Users submit their details through a Google Form including: Name Email Address Phone Number

2️. Data Storage – Google Sheets

All responses are automatically stored in a connected Google Sheet with columns like:

Timestamp Email Address Name Email Phone Number 3. Automation – n8n Workflow

Using n8n, an automated workflow is created:

Trigger: Google Sheets Trigger activates when a new row is added Action: Sends an email using Gmail 4️. Email Notification – Gmail

Through Gmail, users receive an automated message like:

"Hi [Name], Thank you for your feedback. Would you like to get notifications at this number [Phone Number]"

Tools & Technologies Used
Google Forms Google Sheets n8n Gmail

Key Features
-Real-time data capture -Automated workflow execution -Instant email response system -No manual intervention required -Easy to scale and customize

Use Cases
Feedback collection systems HR onboarding automation Event registrations Customer engagement workflows

Learning Outcome
Understanding workflow automation Integration of multiple tools Real-time trigger-based systems Practical use of no-code/low-code platforms

Future Enhancements
Add WhatsApp notifications Use AI tools for personalized responses Dashboard for analytics Data filtering & segmentationAuthor

Author
KHUSHI CHADHA
