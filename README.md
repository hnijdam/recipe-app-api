# Recipe API Project

Dit project is een **Recipe API** gebouwd met **Django** en de **Django REST framework**, en een frontend die gebruikmaakt van **React** en **Tailwind CSS**.

## Backend Setup

### Prerequisites

- Python 3.x
- Django
- Docker
- Django REST framework
- Swagger UI
- PostgreSQL

### Installation

1. **Clone de repository**:
    ```bash
    git clone https://github.com/hnijdam/recipe-api.git
    cd recipe-api
    ```

2. **Maak een virtual environment aan en activeer deze**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Voor Windows: `venv\Scripts\activate`
    ```

3. **Installeer de vereiste pakketten**:
    ```bash
    pip install -r requirements.txt
    ```

4. **PostgreSQL database instellen**:
   - Maak een PostgreSQL database en gebruiker aan.
   - Update de `DATABASES` instelling in `settings.py` met jouw databasegegevens:
     ```python
     DATABASES = {
         'default': {
             'ENGINE': 'django.db.backends.postgresql',S
             'NAME': 'jouw_database_naam',
             'USER': 'jouw_database_gebruiker',
             'PASSWORD': 'jouw_database_wachtwoord',
             'HOST': 'localhost',  # Of het IP-adres van je database
             'PORT': '5432',       # De standaard PostgreSQL poort
         }
     }
     ```

5. **Voer de migraties uit**:
    ```bash
    python manage.py migrate
    ```

6. **Maak een superuser aan**:
    ```bash
    python manage.py createsuperuser
    ```

### API Endpoints

- **Recipes**: `/api/recipes/`
- **Tags**: `/api/tags/`
- **Ingredients**: `/api/ingredients/`

#### Nog steeds een work in progress..dus stay tuned for updates.
