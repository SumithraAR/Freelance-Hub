# Freelancers Hub

## Overview

Freelancers Hub is a web-based freelancing platform that connects employers and employees (freelancers). Employers can post projects with budgets and requirements, while employees can bid on projects based on their skills and expected payment. The platform also provides project tracking, payment monitoring, and skill development resources managed by the administrator.

## Features

### Employer Module
- Register and login securely
- Create and manage profile
- Post projects with:
  - Title
  - Description
  - Required skills
  - Budget
  - Deadline
  - Project attachments
- View bids submitted by employees
- Compare bids and freelancer profiles
- Assign projects to suitable employees
- Track project progress and payments

### Employee Module
- Register and login securely
- Manage profile information
- Browse available projects
- Search projects based on skills and keywords
- Submit bids for projects
- View assigned tasks
- Update project progress
- Track project status and earnings

### Admin Module
- Manage employers and employees
- Monitor platform activities
- Upload learning resources and training materials
- Share skill development videos
- Manage project-related resources
- View platform statistics and reports

## System Workflow

1. Employer posts a project with budget and requirements.
2. Employees browse projects and submit bids.
3. Employer reviews bids and freelancer profiles.
4. Employer assigns the project to the most suitable employee.
5. Employee updates project progress regularly.
6. Employer monitors project completion.
7. Admin manages users and provides learning resources.

## Technology Stack

### Frontend
- HTML
- CSS
- Bootstrap

### Backend
- Python
- Flask

### Database
- MySQL

### Additional Libraries
- Flask-MySQLdb

## Project Structure

```text
freelancer/
│
├── app.py
├── config.py
├── requirements.txt
│
├── routes/
│   ├── auth.py
│   ├── employer.py
│   ├── employee.py
│   ├── admin.py
│   └── shared.py
│
├── templates/
│
├── static/
│   ├── css/
│   └── uploads/
│
└── database/
```

## Installation

### Clone Repository

```bash
git clone https://github.com/SumithraAR/Freelance-Hub.git
cd freelance-Hub
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Database

Create a MySQL database:

```sql
CREATE DATABASE freelancers;
```

Update database credentials in `config.py`.

### Run Application

```bash
python app.py
```

Open:

```text
http://127.0.0.1:5000
```

## Future Enhancements

- Integrated online payment gateway
- Real-time chat system
- AI-based freelancer recommendation
- Project rating and review system
- Email notifications
- Mobile application support
- Advanced analytics dashboard

## Learning Outcome

This project demonstrates the implementation of a complete freelancing marketplace using Flask and MySQL, covering user authentication, project management, bidding systems, task tracking, and resource management.

## Authors

**Sumithra A R**
Master of Computer Applications (MCA)
The National Institute of Engineering, Mysuru

## License

This project is developed for educational and academic purposes.
