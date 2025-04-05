
# ShopCraft

**ShopCraft** is a comprehensive e-commerce web application built with the Django framework. It features user authentication, product management, order processing, article/blog system, contact form, and an admin dashboard. This platform is ideal for managing an online shop with multiple functional modules.

---

## Features

- **User Authentication**: Register, login, logout, and manage user profiles.
- **Admin Panel**: A custom interface to manage all the data and modules.
- **Product Management**: Add/edit/remove products, categorize them, and display product listings.
- **Order System**: Users can add products to cart, place orders, and track order history.
- **Articles/Blog**: Publish and manage informative or promotional articles.
- **Contact Form**: Enable users to send inquiries or feedback.
- **Polls System**: Create and manage user polls for engagement or feedback.
- **User Dashboard**: Allow users to manage their personal data and view orders.
- **Site Settings Module**: Manage global settings for the website.

---

## Technologies Used

- Python 3.x
- Django Framework
- HTML5 / CSS3 / JavaScript
- SQLite (default, can be replaced with PostgreSQL or others)
- Bootstrap (or any other frontend framework, if used)
- All required libraries are listed in `req.txt`

---

## Installation

Follow these steps to run the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/mahdizargarzadeh/ShopCraft.git
cd ShopCraft
```

### 2. Create and activate a virtual environment

```bash
python -m venv venv
```

- On **Windows**:

```bash
venv\Scripts\activate
```

- On **macOS/Linux**:

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r req.txt
```

### 4. Apply database migrations

```bash
python manage.py migrate
```

### 5. Create a superuser (admin account)

```bash
python manage.py createsuperuser
```

Follow the prompts to set a username and password.

### 6. Run the development server

```bash
python manage.py runserver
```

Now open your browser and navigate to `http://127.0.0.1:8000/` to view the site.

---

## Project Structure

```
ShopCraft/
├── account_module/        # Handles user registration, login, and profiles
├── admin_panel/           # Custom admin interface
├── article_module/        # Blog/news system
├── contact_module/        # Contact form handling
├── product_module/        # Product catalog and management
├── order_module/          # Order and cart system
├── polls/                 # Voting and polls system
├── site_module/           # General site settings
├── user_panel_module/     # User dashboard and order history
├── ShopCraft/             # Project settings and URLs
├── req.txt                # Python package requirements
└── manage.py              # Django management script
```

---

## Contributing

Contributions are welcome and appreciated!

To contribute:

1. Fork the repository
2. Create a new branch:
   ```bash
   git checkout -b your-feature-name
   ```
3. Make your changes
4. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
5. Push to your fork:
   ```bash
   git push origin your-feature-name
   ```
6. Open a Pull Request on the original repository

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

## Contact

If you have any questions or suggestions, feel free to reach out:

**Mahdi Zargarzadeh**  
[GitHub Profile](https://github.com/mahdizargarzadeh)

---

Thank you for checking out **ShopCraft**!
