# 📧 Secure Email Sender (PyQt5 GUI)

A user-friendly, secure email client built using Python and PyQt5. This application allows users to log in with their email credentials, compose and send emails (with optional attachments), and ensures validation, encryption (TLS), and input sanitization for safer communication.
---
✨ Features
- 🔐 Secure Login: Login dialog with regex validation for email and masked password input.
- 📥 Compose Emails: Send rich-text emails with subject, body, and optional file attachments.
- 🔄 SMTP Integration: Supports custom SMTP server and port configuration.
- 🛡 Input Validation: Sanitizes subject/body and checks email formatting to avoid malicious input.
- 🧾 Attachment Support: Easily attach and send files.
- ⚠️ SMTP Error Handling: Includes proper exception handling for login, connection, and SMTP errors.
---
🖼 GUI Preview
Login ➝ Compose ➝ Attach ➝ Send
---
🛠 Technologies Used
```bash
Python 3
PyQt5 (GUI)
smtplib, email (for sending emails securely)
socket (SMTP server check)
re (input validation)
```
---
🚀 How to Run
Install Requirements:
```bash
pip install PyQt5
```
Run the App:
```bash
python app.py
```
Login, Compose, and Send Emails:

Use your SMTP-enabled email (e.g., Gmail with App Password or Outlook).
---
🛡 Security Notes
Passwords are masked and not stored.

Unsafe characters in subject/body are rejected.

Uses STARTTLS for encryption over SMTP.

