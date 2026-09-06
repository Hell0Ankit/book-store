# Book Store

A Django-based online bookstore "Sonu Book Store" application with user accounts, product catalog, shopping cart, order management, live chat, and a customer dashboard. Styled with Tailwind CSS.

## Features

- **Accounts** — user registration, login, logout, and password reset/forgot-password flows
- **Product** — book catalog with listings and details
- **Cart** — shopping cart management
- **Orders** — order placement and history
- **Customer Dashboard** — customer-facing account/order overview
- **Chat** — real-time or in-app messaging/support
- **Core** — shared/base app logic
- **Tailwind CSS** — modern, responsive UI styling

## Tech Stack

- **Backend:** Python, Django
- **Frontend:** Django Templates, Tailwind CSS
- **Database:** SQLite (`db.sqlite3`)

## Project Structure

```
book-store/
├── accounts/            # User authentication (login, register, password reset)
├── book_store/          # Django project settings
├── cart/                # Shopping cart app
├── chat/                # Chat/support app
├── core/                # Shared core functionality
├── customer_dashboard/  # Customer dashboard app
├── media/               # User-uploaded media files
├── orders/              # Order processing app
├── product/             # Product/book catalog app
├── static/               # Static assets (CSS, JS, images)
├── tailwind_css/         # Tailwind CSS configuration
├── templates/            # HTML templates (login, reset password, forgot password, etc.)
├── db.sqlite3            # SQLite database
├── manage.py              # Django management script
└── requirements.txt        # Python dependencies
```

## Getting Started

### Prerequisites

- Python 3.x
- pip

### Installation

1. Clone the repository
   ```bash
   git clone <repository-url>
   cd book-store
   ```

2. Create and activate a virtual environment
   ```bash
   python -m venv env
   env\Scripts\activate      # Windows
   source env/bin/activate   # macOS/Linux
   ```

3. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations
   ```bash
   python manage.py migrate
   ```

5. Run the development server
   ```bash
   python manage.py runserver
   ```

6. Visit `http://127.0.0.1:8000/` in your browser

