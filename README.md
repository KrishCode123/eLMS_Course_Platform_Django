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

