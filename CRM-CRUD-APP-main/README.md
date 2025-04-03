# CRUD CRM Application

## Overview
This is a **CRUD-based CRM (Customer Relationship Management) application** built using **Django** for the backend and **HTML, CSS, and JavaScript** for the frontend. The application allows users to manage customer records, including creating, reading, updating, and deleting (CRUD) customer information. It also includes a dashboard with a search filter for efficient record retrieval.

## Features
- User authentication (login/logout system)
- Create, Read, Update, and Delete (CRUD) customer records
- Dashboard with a search filter to find specific records
- Responsive UI with HTML, CSS, and JavaScript
- Django-powered backend with database integration
- Data validation and error handling

## Technologies Used
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (default) or PostgreSQL/MySQL (optional)
- **Styling**: CSS (Bootstrap/Custom styles)
- **Authentication**: Django's built-in authentication system

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- Python (>= 3.8)
- Django (>= 4.0)
- pip (Python package manager)

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/crud-crm.git
   cd crud-crm
   ```
2. **Create and Activate a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Apply Migrations**
   ```bash
   python manage.py migrate
   ```
5. **Create a Superuser** (for admin access)
   ```bash
   python manage.py createsuperuser
   ```
6. **Run the Development Server**
   ```bash
   python manage.py runserver
   ```
   Access the application at: [http://127.0.0.1:8000](http://127.0.0.1:8000)

## Usage
1. Register/Login as a user.
2. Add, view, update, or delete customer records.
3. Use the search filter to find specific customers.
4. Access the admin panel at [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin) (Superuser credentials required).

## Project Structure
```
crud-crm/
│── crm_app/               # Main Django app
│   ├── migrations/        # Database migrations
│   ├── static/            # CSS, JS, Images
│   ├── templates/         # HTML templates
│   ├── views.py           # Application logic
│   ├── models.py          # Database models
│   ├── urls.py            # URL routing
│   ├── forms.py           # Django forms
│── manage.py              # Django management script
│── db.sqlite3             # Database (SQLite default)
│── requirements.txt       # Dependencies
│── README.md              # Project documentation
```

## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes.
4. Push to your fork and create a pull request.

## License
This project is licensed under the **MIT License**.

## Contact
For any queries or issues, reach out to:
- **Abhay Prasad **: [workwithabhay247@gmail.com]
- **GitHub**: [[https://github.com/your-username](https://github.com/Abhay-codehub)]

