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

📸 Screenshots
(Add screenshots of your application here by replacing the placeholders below with markdown image syntax:
)
Book List Page:
![Screenshot 2025-04-25 101831](https://github.com/user-attachments/assets/61d25269-95d6-4ac3-a28b-b1563e5a6dc0)
Book Detail Page:
![Screenshot 2025-04-25 101903](https://github.com/user-attachments/assets/b1f02b1c-bf03-4586-9f2d-643ad1d48449)
Shopping Cart:
![Screenshot 2025-04-25 102206](https://github.com/user-attachments/assets/dd1ea032-f230-410a-909c-c20bddb89bd9)
Login/Signup Page:
![Screenshot 2025-04-25 101931](https://github.com/user-attachments/assets/8f6deca0-7618-4bea-8c48-0b4fc02184a6)
![Screenshot 2025-04-25 102000](https://github.com/user-attachments/assets/06522a34-8d8c-428c-9247-f3764b6dd782)


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
