# 🛠️ Setup Instructions for `django-week3`

## 📦 Requirements

- Python 3.x
- pip (Python package manager)
- Git (to clone this repo)

## 🔽 1. Clone the repository

```bash
git clone https://github.com/it-web-pro/django-week3.git
cd django-week3
```

## 🧪 2. Create and activate virtual environment

**(Windows)**

```bash
python -m venv env
env\Scripts\activate
```

**(macOS/Linux)**

```bash
python3 -m venv env
source env/bin/activate
```

## 📥 3. Install required packages

```bash
pip install -r requirements.txt
```

## ⚙️ 4. Run migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

## 👤 5. Create superuser (optional but useful)

```bash
python manage.py createsuperuser
```

## 🚀 6. Run the development server

```bash
python manage.py runserver
```

Then go to `http://127.0.0.1:8000` in your browser.

---

## 🧪 Admin login

Visit: [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)  
Use the credentials from the `createsuperuser` step.

---

## 📝 Notes

- If `python` doesn’t work, try `python3`
- If `pip` doesn’t work, try `pip3`
