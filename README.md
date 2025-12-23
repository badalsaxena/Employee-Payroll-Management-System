🧾 Employee Payroll Management System

A complete Employee Payroll Management System developed using Python, Streamlit, and MySQL, designed to manage employees, payroll, attendance, and applications with secure Admin & Employee dashboards.

This project demonstrates real-world backend logic, database integration, and a clean interactive UI, making it suitable for academic use as well as resume showcasing.

🚀 Features
👨‍💼 Admin Module

Admin authentication & registration

Add, update, delete employees

View all employees

Calculate employee salary (HRA, DA, Tax, Net Salary)

View salary reports

View employee leave/applications

Approve or reject applications with remarks

Secure role-based access

👨‍🔧 Employee Module

Employee login with ID & password

View personal details

View salary breakdown

Change password

Apply for leave or other applications

View application status

Mark daily attendance

View attendance history

🧠 Salary Calculation Logic

HRA: 20% of base salary

DA: 10% of base salary

Tax: 10% of gross salary

Net Salary calculated dynamically

🛠️ Tech Stack
Technology	Usage
Python	Core logic & backend
Streamlit	UI & dashboard
MySQL	Database
Pandas	Data display
SQL	Data management

📂 Project Structure
├── Epms.py
├── README.md
├── requirements.txt
└── Database (MySQL)

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/badalsaxena/Employee-Payroll-Management-System.git
cd Employee-Payroll-Management-System

2️⃣ Install Dependencies
pip install streamlit mysql-connector-python pandas

3️⃣ Setup MySQL Database
CREATE DATABASE Employee_Payroll_System;


Update database credentials inside the code:

host="localhost"
user="root"
password="your_password"
database="Employee_Payroll_System"

4️⃣ Run the Application
streamlit run Epms.py

🔐 Default Roles

Admin: Can manage employees & payroll

Employee: Can view salary, apply for leave, mark attendance

📸 Screenshots (Optional but Recommended)

Add screenshots of:

Home screen

Admin panel

Employee dashboard
(This increases recruiter trust by 2x)

📌 Resume Highlights (You Can Copy This)

Developed a full-stack Employee Payroll Management System using Python, Streamlit, and MySQL with role-based authentication, salary computation, attendance tracking, and leave management.

🧩 Future Enhancements

Password hashing

Export salary reports to PDF

Cloud database integration

Email notifications

Role-based permissions upgrade

🤝 Author

Badal Saxena
Engineering Student | Python & Backend Enthusiast

⭐ If you like this project

Give it a ⭐ on GitHub — it motivates me to build more!
