# Library Management
## CREATED BY GROUP-7
- ANIKEIT SETHI (190001003)
- HRITIKESH BOYAPATI (190002014)
- MUKESH MEENA (190001039)
- SAPAVATH SHASHIKUMAR (190001055)

---
# CREATED USING
- Django
- SQlite
- HTML
- CSS
- Python

---
## Functions
### Admin
- Create Admin account and Login.
- Can Add, View, Book
- Can Issue Book (added by Admin) to registered student.
- Can view Issued book with issued date and expiry date.
- Can view Fine (10 rupees for each day after expiry date).
- Can View Students that are registered into system.

### Student
- Create account and Login.
- Can view their issued book only with expiry date and fine(if there any otherwise 0)
---

## HOW TO RUN THIS PROJECT
- Install Python(3.9.4)
- Download This Project Zip Folder and Extract it
- Open Terminal and Execute Following Commands 
- Move to project folder in Terminal
- Then Move to project_dbms folder in Terminal
- Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

# TO NOTICE
- Html code in templates folder

## TO IGNORE
- ignore __pycache__ files in the Folder

---
# THANK YOU FOR READING #
