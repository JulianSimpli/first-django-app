# Django Polls Application Tutorial

## Project Description
This is a simple Django web application that creates a basic polling system where users can:
- View available polls
- Vote on poll options
- See poll results

## Prerequisites
- Python 3.10+
- Django 5.0 or later
- pip (Python package manager)

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/JulianSimpli/first-django-app.git
cd first-django-app
```

### 2. Create a Virtual Environment
```bash
# On Windows
python -m venv venv
venv\Scripts\activate

# On macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install django~=5.0.0
```

### 5. Database Setup
```bash
python manage.py migrate
python manage.py createsuperuser
```

### 6. Run the Development Server
```bash
python manage.py runserver
```

## Testing
```bash
python manage.py test polls
```

## Troubleshooting
- Ensure you're using Python 3.10 or newer
- Check Django 5.0 compatibility with your packages
- Use `pip list` to verify dependency versions

