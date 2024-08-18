Stock Market Application
Project Description
This is a Django-based web application that allows users to view real-time stock prices using TradingView charts. The application also includes user authentication and a registration/signup page.

Features
Real-Time Stock Prices: Displays real-time stock data with TradingView charts.
User Authentication: Users can register, log in, and manage their accounts.
Watchlist Functionality: Users can add stocks to their watchlist.
Technology Stack
Backend: Django, Python
Frontend: HTML, CSS, JavaScript
APIs: Trading View for stock data
Database: SQLite (default) or PostgreSQL
Authentication: Django's built-in authentication system

1.Create virtual environment
2. pip install -r requirements.txt
3. python manage.py migrate
4. python manage.py runserver

Then access the application

USAGE
Viewing Stock Prices
•	After logging in, users can search for stocks and view real-time data using embedded TradingView charts.
Watchlist
•	Users can add stocks to their watchlist for easy tracking.
API Integration
•	TradingView: The application integrates TradingView charts using their widget to provide real-time stock data.


File structure

stock-market-app/
│
├── stocks/                    
│   ├── migrations/            # Database migrations
│   ├── templates/             # HTML templates
│   ├── static/                # Static files (CSS, JS, images)
│   ├── urls.py                # URL routing
│   ├── views.py               # View functions
│   └── models.py              # Database models
│
├── stock_market_app/          # Project configuration
│   ├── settings.py            # Project settings
│   ├── urls.py                # Project URL routing
│   └── wsgi.py                # WSGI configuration
│
├── manage.py                  # Django management script
├── requirements.txt           # Python dependencies

