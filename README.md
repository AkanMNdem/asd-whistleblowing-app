# ASD Whistleblowing App

## **Overview**

ASD Whistleblowing App is a web application developed using Django, designed to empower healthcare professionals to report misconduct, safety breaches, and unethical practices anonymously and securely. The application ensures that reports are handled with the utmost confidentiality and provides tools for both users and administrators to manage the reporting process efficiently.

## **Features**

- **User Roles**:
  - **Admin**: Manage all reports, update their statuses, and provide resolution feedback.
  - **Regular User**: Submit reports and track the status of their submissions.

- **Reporting**:
  - Users can submit reports both anonymously and while logged in.
  - Admins have the ability to update report statuses and offer feedback.

- **Dashboard**:
  - **Admin Dashboard**: View all submitted reports, organized by status (New, In Progress, Resolved).
  - **User Dashboard**: Manage and track the progress of personal reports.

- **Authentication**: Integrated with Django Allauth to manage user authentication and login processes.

## **Technologies Used**

- **Django**: The primary web framework used for building the application.
- **Django Allauth**: Handles user authentication and social login.
- **Gunicorn**: Used as the application server.
- **Boto3**: Manages AWS integrations, such as S3 for file storage.
- **PostgreSQL**: Database used for storing application data.

## **Getting Started**

### To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AkanMNdem/asd-whistleblowing-app.git
   cd asd-whistleblowing-app
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver


