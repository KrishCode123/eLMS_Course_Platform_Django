# eLMS_Course_Platform_Django

An e-platform for academic institutions that combines learning management and online assessment serves as a robust solution for modern education. It integrates essential functionalities like course management, student-teacher interaction, and digital assessments into a single platform, enhancing the learning experience for both educators and students. The Learning Management System (LMS) aspect allows educators to create and organize courses, upload resources such as videos, documents, and presentations, and deliver lectures through live or recorded sessions. It facilitates seamless communication through discussion forums, messaging, and announcements, enabling students to engage actively in their learning process. Progress tracking features allow instructors to monitor student performance through assignments, quizzes, and engagement metrics.

## Features

- Admin can add courses, teachers, and students, and assign courses to them.
- Teachers can create course content, announcements, assignments, quizzes, and take attendance. They can also view details and analysis of the assessments.
- Students can enroll in courses using an access key, view the content of their enrolled courses, participate in assessments, and see their detailed results.
- There is a discussion section available for both teachers and students.

## Run Locally

1. Clone the project

```bash
git clone https://github.com/KrishCode123/eLMS_Course_Platform_Django.git
```

2. Go to the project directory

```bash
cd eLMS_Course_Platform_Django
```

3. Create a virtual environment and activate it (Windows)

```bash
python -m venv env
```

```bash
env\Scripts\activate
```

4. Install dependencies

```bash
pip install -r requirements.txt --use-deprecated=legacy-resolver
```

5. Make migrations and migrate

```bash
python manage.py makemigrations
```

```bash
python manage.py migrate
```

6. Create admin/superuser

```bash
python manage.py createsuperuser
```

7. Finally run the project

```bash
python manage.py runserver
```

# Images 
![image](https://github.com/user-attachments/assets/3a10437c-d476-48cf-9004-b421dee61b3c)
![image](https://github.com/user-attachments/assets/569d9720-01df-4de8-85a3-b744a2003cb8)
![image](https://github.com/user-attachments/assets/9fbb3374-c8f0-4cf2-b865-3d1603eba2e1)
![image](https://github.com/user-attachments/assets/0ae7fbdc-925d-4615-a87d-33b2c072b749)
![image](https://github.com/user-attachments/assets/8c127e09-07cc-4a5a-9846-6ceb870e302d)
![image](https://github.com/user-attachments/assets/479cc12f-2b22-4bad-811b-984b00a66830)
![image](https://github.com/user-attachments/assets/2e7eb735-6128-4b88-bfc2-7ec117f1b71d)
![image](https://github.com/user-attachments/assets/09e92364-b0f8-4b20-820a-ef1c77cbb799)
![image](https://github.com/user-attachments/assets/3e2ec7f5-614a-4400-8e4c-19dd4de4f3f1)
![image](https://github.com/user-attachments/assets/241b26af-4e46-4a28-80a3-db3232ee9392)


