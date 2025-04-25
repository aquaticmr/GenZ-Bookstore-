# 📚 Django Bookstore Application

A web application built with Django for browsing, purchasing, and managing books online. Features user accounts, a shopping cart, order management, and an admin interface, all styled with Bootstrap 5.

---

## 🚀 Project Overview

This project allows users to:

*   Browse book listings & view detailed information about each book.
*   Register for a new account and log in/out.
*   Add/update/remove books from a shopping cart.
*   Proceed through a checkout process to place orders.
*   View their order history.
*   (If applicable) Admins can manage books and orders through a dedicated interface.
*   Experience a modern user interface built with Bootstrap 5 and Bootstrap Icons.

---

## ⚙️ Setup & Run Instructions

### ✅ Prerequisites

*   Python 3.x installed
*   `pip` (Python package installer) installed
*   Git installed

### 📦 Clone the Project
git clone https://github.com/aquaticmr/GenZ-Bookstore-.git
cd your-bookstore-project🛠️ Local Setup
Create and Activate Virtual Environment:
# Windows
python -m venv venv
.\venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
Use code with caution.
Bash

Install Dependencies:
(Ensure you have created a requirements.txt file: pip freeze > requirements.txt)
pip install -r requirements.txt
Use code with caution.
Bash

Apply Database Migrations:
python manage.py migrate
Use code with caution.
Bash

Create Superuser (for Django Admin or initial access):
python manage.py createsuperuser
Use code with caution.
Bash

(Follow the prompts to create an admin account)
Run the Development Server:
python manage.py runserver
Use code with caution.
Bash

Access the Application:
Open your web browser and go to: http://127.0.0.1:8000/
🧰 Tech Stack
Backend: Django (Python Web Framework)
Frontend: HTML, CSS, Bootstrap 5, Bootstrap Icons
Database: SQLite (Default for development, easily swappable with PostgreSQL, MySQL, etc.)
(Optional) DevOps: Docker, Jenkins (if implemented)

🐳 (Optional) Docker Notes
(Include this section if you have Docker configured, otherwise remove it)
Dockerfile: Builds the Django web application image.
docker-compose.yml: Defines the web service (and potentially database service).
Run Command: docker compose up --build
Access: http://localhost:8000 (or as configured in docker-compose.yml)
🔁 (Optional) Jenkins CI/CD
(Include this section if you have Jenkins configured, otherwise remove it)
Jenkinsfile: Defines the pipeline stages (e.g., build, test, deploy).
Typically integrates with source control (like GitHub) for automated builds.
```
📂 Folder Structure
GenzBookstore/
├── bookstore_project/  
├── books/             
├── accounts/           
├── cart/             
├── orders/           
├── admin_panel/        
├── templates/        
│   ├── base/
│   ├── accounts/
│   ├── books/
│   ├── cart/
│   ├── orders/
│   └── admin_panel/   
├── static/            
├── venv/               
├── requirements.txt    
└── manage.py
```       
