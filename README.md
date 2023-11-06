# Library Management System
### The Library Management System project is a web application developed using Python with the Django web framework. The purpose of this project is to create an efficient and automated system for managing library operations that focuses mainly on dealing with issuing books and records. Also, the system displays all the available students with their issued books. In addition, the system allows managing books by entering a title, author, ISBN, and category. This project is divided into two categories: Student, and Admin Panel. In an overview of this web application, a student can simply register and start using it. Here, the system displays all the issued books for the student. The system limits other access to the student account. As he/she can only view issued book records that display expiry dates, total fine charges, and others.
### Available Features:
#### Student Panel | Admin Panel | Add Books | List Books | Issue Books | Auto Fine Charge | View Issued Books | View Available Students
### 
![image](https://github.com/samirali-mukhi/Library-Management-System/assets/90303555/d7082453-f74d-4c82-9cd6-4cd721da64f8)
![image](https://github.com/samirali-mukhi/Library-Management-System/assets/90303555/d3502da5-40ea-499c-8aa0-e4d0f0048547)
![image](https://github.com/samirali-mukhi/Library-Management-System/assets/90303555/8f8b5690-7602-4068-8d63-209159ed810b)
![image](https://github.com/samirali-mukhi/Library-Management-System/assets/90303555/fcf0c31e-9691-4d79-a7d9-bfc0069e6a6e)
![image](https://github.com/samirali-mukhi/Library-Management-System/assets/90303555/bc3fca40-cde0-4665-9d5d-c959ffd51fcf)
![image](https://github.com/samirali-mukhi/Library-Management-System/assets/90303555/33931a95-c549-4053-ba93-8ba103e846f5)
![image](https://github.com/samirali-mukhi/Library-Management-System/assets/90303555/ee2e55db-c529-4dff-9657-1335a3a2ff95)
![image](https://github.com/samirali-mukhi/Library-Management-System/assets/90303555/61933a12-e80f-4f1a-bc73-592ff41da7d4)
![image](https://github.com/samirali-mukhi/Library-Management-System/assets/90303555/69034751-4688-41dd-a3a7-08ea68dfef62)
![image](https://github.com/samirali-mukhi/Library-Management-System/assets/90303555/5769cd20-7185-418c-824e-71a86dfe810d)
![image](https://github.com/samirali-mukhi/Library-Management-System/assets/90303555/46c21f2b-2752-450d-a28e-d1af6de01707)
### Instructions: How to Run?
* After you finish downloading the project, unzip the project file and head over to the project root folder.
* You can also create a Virtual Environment and Activate it.
* Open your Terminal/Command Prompt on the project’s root folder.
* Install the Requirements: `pip install -r requirements.txt`
* Then, make database migrations: `python manage.py makemigrations` and `python manage.py migrate`
* And finally, after a successful migration run the application: `python manage.py runserver`
* At last, open up your favorite web browser
* Go to URL `http://127.0.0.1/[ PORT_NUMBER ]/`
* For the Admin Panel credentials, you have to create one with a superuser.
* And there you have it, a full setup of the Library Management System project in Django. At First, all you need to have is Python and Django installed on your local machine whereas the remaining modules are under the requirements.txt file. Still, the versions may vary according to different project requirements, you can make use of it with python virtual environments
