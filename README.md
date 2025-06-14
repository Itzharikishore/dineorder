# Django Restaurant Ordering System 🍽️

A full-featured web-based restaurant menu and ordering system built with Django. Users can browse menu items, filter by category, add items to a cart, and place orders. Includes authentication, search, and order management.

## 🚀 Features

- User Sign Up, Login, and Logout
- Menu browsing by category
- Add items to cart
- Update and remove cart items
- Place orders with checkout
- Order summary page
- Search functionality
- Login-required pages with redirect support
- Admin-ready with Django's built-in admin panel

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS (custom templates)
- **Database**: SQLite (default, easy to swap)
- **Authentication**: Django's built-in system

## 📷 Screenshots

> Add screenshots of the homepage, menu, cart, and checkout here if desired.

## 📁 Project Structure

```
django-restaurant-ordering/
├── customer/
│   ├── migrations/
│   ├── templates/customer/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── django_project/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3
├── manage.py
└── Pipfile
```

## 🚦 How to Run Locally

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/django-restaurant-ordering.git
cd django-restaurant-ordering
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

> If using Pipfile:
```bash
pip install pipenv
pipenv install
pipenv shell
```

3. **Run migrations**

```bash
python manage.py migrate
```

4. **Create a superuser**

```bash
python manage.py createsuperuser
```

5. **Start the server**

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser.

## 🔐 Default URLs

- `/signup/` – User registration
- `/login/` – User login
- `/logout/` – Logout
- `/order/` – Place an order (requires login)
- `/cart/` – View cart
- `/checkout/` – Checkout and confirm order
- `/search/` – Search menu items

## ✅ To Do

- Add user order history page
- Payment integration (e.g., Stripe)
- Add mobile responsiveness
- Include tests and CI pipeline

## 🧑‍💻 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss your ideas.
