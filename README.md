# -Service-for-the-restaurant-kitchen
# Service for the Restaurant Kitchen

A web application built with Django for managing a restaurant's kitchen operations. It provides full CRUD functionality for dishes, ingredients, dish types, and cooks. The app also includes assignment of cooks to dishes, authentication, filtering, and a RESTful API.

---

## Features

### Core Functionality

* CRUD for:

  * Dishes
  * Ingredients
  * Dish Types
  * Cooks
* Assign/unassign cooks to dishes
* Create a dish with multiple ingredients

### User Interface

* Responsive design with Bootstrap
* Navigation bar with links to all key sections
* Home page with kitchen statistics

### Authentication

* User registration
* Login/Logout
* Only authenticated users can perform write operations

### Filtering & Search

* Search for dishes and cooks by name
* Filter dishes by type

### Testing

* Unit tests for:

  * Home page
  * Dish creation with multiple ingredients
  * Cook assignment toggle

### API (via DRF)

* List, retrieve, create, update, delete operations for all models
* Authenticated access via DRF

---

## Getting Started

### Requirements

* Python 3.10+
* Django 5.2+
* Django REST Framework

### Installation

```bash
# Clone the repo
https://github.com/your-username/restaurant-kitchen.git
cd restaurant-kitchen

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Create superuser (optional)
python manage.py createsuperuser

# Run the development server
python manage.py runserver
```

---

## Running Tests

```bash
python manage.py test
```

---

## API Overview

| Endpoint            | Description               |
| ------------------- | ------------------------- |
| `/api/dishes/`      | List & create dishes      |
| `/api/ingredients/` | List & create ingredients |
| `/api/cooks/`       | List & create cooks       |
| `/api/dish-types/`  | List & create dish types  |

---

## Screenshots

Home:
![img.png](image/img.png)
---
Cooks:
![img_1.png](image/img_1.png)

Forms:
![img_3.png](image/img_3.png)

Detail:
![img_4.png](image/img_4.png)




## Author

Created by \Ksenia Malashchuk as part of a Django project assignment.

