# Recipe API Project

This project is a Recipe API built with Django and Django REST framework, along with a frontend built using React and Tailwind CSS.

## Backend Setup
---
## Prerequisites

- Python 3.x
- Django
- Django REST framework
- PostgreSQL
---
### Installation

* _Clone the repository_:
   ```bash
   git clone https://github.com/hnijdam/recipe-api.git
   cd recipe-api
   ```

* _Create a virtual environment and activate it_:
---
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

---
* Install the required packages:
```bash
pip install -r requirements.txt
```

---

* _Set up the PostgreSQL database_:

- Create a PostgreSQL database and user.
- Update the DATABASES setting in settings.py with your database credentials.

---

* Run Migrations
```bash
python manage.py migrate
```
---

* Create a superuser:
```bash
python manage.py createsuperuser
```
---

#### API Endpoints

- Recipes: /api/recipes/
- Tags: /api/tags/
- Ingredients: /api/ingredients/




