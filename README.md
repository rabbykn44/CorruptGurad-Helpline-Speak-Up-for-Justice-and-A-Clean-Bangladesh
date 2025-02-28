# CorruptGurad-Helpline-Speak-Up-for-Justice-and-A-Clean-Bangladesh


# CorruptGuard Helpline

## Speak Up for Justice and a Clean Bangladesh

CorruptGuard Helpline is a web-based platform designed to empower individuals to report corruption anonymously and securely. Built using Django, the platform ensures transparency and accountability while maintaining user privacy.

---

## Features

- **User Authentication & Authorization**: Secure login and role-based access control.
- **Anonymous Reporting**: Users can report corruption cases without revealing their identity.
- **Report Management**: Admins can review, categorize, and track reports.
- **Search & Filtering**: Use Elasticsearch for fast and efficient report retrieval.
- **Secure Payments**: Integrated payment system for donations/support.
- **API Management**: REST API endpoints verified using Postman.

---

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Django, Django REST Framework
- **Database**: PostgreSQL / SQLite
- **Search Engine**: Elasticsearch
- **Payment Integration**: Stripe/PayPal
- **Version Control**: Git & GitHub

---

## Installation & Setup

### 1. Clone the Repository
```bash
 git clone https://github.com/your-username/CorruptGuard.git
 cd CorruptGuard
```

### 2. Create & Activate Virtual Environment
```bash
 python -m venv venv
 source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
 pip install -r requirements.txt
```

### 4. Apply Migrations & Start Server
```bash
 python manage.py makemigrations
 python manage.py migrate
 python manage.py runserver
```

The project will be accessible at: **http://127.0.0.1:8000/**

---

## Project Structure
```
CorruptGuard/
│── corruptguard/           # Django project settings
│── reports/                # Reports app (Models, Views, Admin)
│── templates/reports/      # HTML Templates
│── static/                 # CSS, JS, Images
│── requirements.txt        # Project Dependencies
│── manage.py               # Django management commands
```

---

## Contribution Guidelines
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Commit changes: `git commit -m 'Added new feature'`
4. Push to branch: `git push origin feature-branch`
5. Open a Pull Request (PR).

---

## License
This project is licensed under the **MIT License**.

---

## Contact
For any inquiries or contributions, reach out to **Md. Jubayerul Hasan Mahin**.
