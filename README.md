# payro24 on Django

### Requirements

- Django v3.0.3
- payro24 v0.0.1

### Deployment

```bash
git clone git@github.com:payro24/python-django.git
cd python-django
# Create virtualenv named build
virtualenv -p python3 build
source build/bin/activate
# Set your api-key
cp .env.example .env
vi .env
# Install requirements, migration and run
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
