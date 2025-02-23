Django Student Management System
A simple Student Management System built using Python (Django) for educational purposes.

Features
A. Admin Users Can:
View summary charts of student and staff performance, courses, subjects, and attendance.
Manage Staff (Add, Update, Delete).
Manage Students (Add, Update, Delete).
Manage Courses (Add, Update, Delete).
Manage Subjects (Add, Update, Delete).
Manage Sessions (Add, Update, Delete).
View Student Attendance.
Review and reply to Student/Staff Feedback.
Approve or Reject Student/Staff Leave.
B. Staff/Teachers Can:
View summary charts related to their students, subjects, and leave status.
Take/Update Student Attendance.
Add/Update Student Results.
Apply for Leave.
Send Feedback to Admin.
C. Students Can:
View attendance reports.
View exam results.
Apply for Leave.
Send Feedback to Admin.
Installation & Setup
Pre-requisites:
Install Git → Download Git
Install Python (latest version) → Download Python
Install Pip (Python Package Manager) → Install Pip
1. Clone the Repository
sh
Copy
Edit
git clone <your-repo-url>
cd student-management-system
2. Create a Virtual Environment
Install virtualenv:

sh
Copy
Edit
pip install virtualenv
Create and activate the virtual environment:

For Windows:

sh
Copy
Edit
python -m venv venv
venv\Scripts\activate
For Mac/Linux:

sh
Copy
Edit
python3 -m venv venv
source venv/bin/activate
3. Install Dependencies
sh
Copy
Edit
pip install -r requirements.txt
4. Configure Allowed Hosts
In settings.py, update the ALLOWED_HOSTS list:

python
Copy
Edit
ALLOWED_HOSTS = ['*']
5. Run Migrations & Start Server
sh
Copy
Edit
python manage.py migrate
python manage.py runserver
6. Create Super User
sh
Copy
Edit
python manage.py createsuperuser
Enter the required details (email, username, password).

Default Login Credentials
User Role	Email	Password
Admin (HOD)	admin@gmail.com	admin
Staff	staff@gmail.com	staff
Student	student@gmail.com	student
License
This project is open-source and free to use for educational purposes.

