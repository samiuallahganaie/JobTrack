# JobTrack — Job Portal & Application Tracker

A full-stack web application built with Flask, SQLite, HTML, CSS, and JavaScript to help job seekers organize and track their job applications.

## Features

- Dashboard with application statistics
- Add, edit, and delete job applications
- Track Applied, Interview, Offer, Rejected, and Withdrawn statuses
- Search applications by company, role, and location
- Filter applications by status
- Store application details in an SQLite database
- Record salary, job links, interview dates, and notes
- Responsive dashboard design
- Form validation and success/error messages

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** Python, Flask
- **Database:** SQLite
- **Deployment:** Gunicorn-compatible

## Project Structure

```text
job-portal/
├── app.py
├── requirements.txt
├── jobs.db
├── README.md
├── templates/
│   └── index.html
└── static/
    ├── style.css
    └── script.js
```

The `jobs.db` file is generated automatically when the application starts. It should generally not be committed to GitHub because it may contain personal application data.

## Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/samiuallahganaie/CodeNest.git
```

### 2. Open the project directory

```bash
cd CodeNest/job-portal
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Start the application

```bash
python app.py
```

Open `http://127.0.0.1:5000` in your browser.

## Future Improvements

- User registration and login
- Resume upload and management
- Interview reminders
- Export application data to CSV
- Persistent cloud database
- Automated tests

## Author

**Samiuallah Ganaie**

Computer Science Engineering Student

GitHub: https://github.com/samiuallahganaie

---

This project was developed for learning full-stack web development and demonstrating practical Python and Flask skills.