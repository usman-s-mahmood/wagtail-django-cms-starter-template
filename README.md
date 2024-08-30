# Wagtail - A Django CMS website builder
**Steps for starting with wagtail project**
    1. python -m venv virt `for creating virtual environment with name virt`
    2. cd virt/scripts; ./Activate.ps1; `for activating virt`
    3. pip install wagtail `for installing wagtail on virt`
    4. wagtail start MyProject `starting a wagtail CMS project with name MyProject`
    5. cd MyProject `moving into project DIR`
    6. pip install -r requirements.txt `for installing dependencies`
    7. python manage.py migrate `for applying migrations to database`
    8. python manage.py createsuperuser `for admin creation`
    9. python manage.py runserver `for running development server`
