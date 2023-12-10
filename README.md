# Fazt - DJANGO CRUD AUTH PROJECT

## Steps

1. **Create Envieronment:**

    ```
    python3 -m venv venv
    ```

2. **Install Django:**

    ```
    pip install django
    ```

3. **Create Project:**

    ```
    django-admin startproject <project-name> .
    ```

4. **Run Server:**

    ```
    python manage.py runserver
    ```

5. **Create App:**

    ```
    python manage.py startapp <app-name> .
    ```

6. **Make Migrate :**

    ```
    python manage.py migrate
    ```

7. **Install Django Rest Framework :**

    ```
    pip install djangorestframework
    ```

8. **Install Django Cors :**

    ```
    pip install django-cors-headers
    ```

9. **Make Migrations:**

    ```
    python manage.py makemigrations
    ```

10. **Run table :**

    ```
    python manage.py migrate
    ```

11. **Connect to Database and edit tables:**

    **This process is more tedious**

    ```
    python manage.py shell
    ```

    or go our browser and run

    ```
    /admin
    ```

12. **Create a superuser:**

    ```
    python manage.py createsuperuser
    user: admin
    mail: python@django.com
    PASSWORD: 12345678@
    ```