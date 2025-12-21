# USafe Forum

ZEN-U is a web forum built for students to discuss mental health topics in a structured and respectful way.  
The goal was to allow both anonymous and non-anonymous participation while maintaining moderation and safety.

This project was developed with 4 classmates as part of a university course and later cleaned up and published for portfolio purposes.

---

## Demo
Here’s a short video showing how the application works, including posting, commenting, reactions, and moderation:

👉 https://www.youtube.com/watch?v=YOUR_VIDEO_ID_HERE

---

## What it does
- User accounts with different roles
- Anonymous and non-anonymous posts
- Comments and reactions without page reloads
- Topic-based discussions
- Basic moderation and reporting tools
- Appointment booking with availability checks

---

## Tech used
- Python / Flask
- MySQL
- HTML, CSS, JavaScript
- AJAX (Fetch API)

---

## Database
The database uses a relational design with constraints and triggers to keep counts (comments, reactions) in sync and to prevent invalid bookings.

Configuration files and credentials are not included.

---

## Running locally
The project relies on environment variables and a local database setup, which are intentionally not part of this repository.

Basic setup:
```bash
python -m venv venv
pip install -r requirements.txt
python app.py
