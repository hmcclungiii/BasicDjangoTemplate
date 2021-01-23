Basic, blank template for Django projects.

Clone the repo.
python3 -m venv venv
. venv/bin/activate
pip3 install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py collectstatic

