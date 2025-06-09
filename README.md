# 🛒 FreshMart - Online Grocery Store

A Flask-based online grocery store with user authentication and shopping cart functionality.

## ✨ Features

- User registration and login system
- Product catalog with categories
- Shopping cart functionality
- Basic order management
- Responsive design using Bootstrap

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- pip package manager

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/freshmart.git
   cd freshmart

2. Create and activate virtual environment:
   ```bash
    python -m venv venv
  # Windows:
    venv\Scripts\activate
  # Mac/Linux:
    source venv/bin/activate
3 .Install dependencies:
 ```bash
    pip install -r requirements.txt
```
4. Initialize the database:

```bash
python app.py
```
5. Run the application:

```bash
python app.py
```
6. Access the store at: http://localhost:5000
   
## 📂 Project Structure
```text
freshmart/
├── instance/
│   └── grocery.db           # SQLite database
├── static/
│   └── images/              # Product images
├── templates/
│   ├── base.html            # Base template
│   ├── index.html           # Product listings
│   ├── cart.html            # Shopping cart
│   ├── login.html           # Login page
│   └── register.html        # Registration page
├── app.py                   # Main application
└── requirements.txt         # Dependencies
 ```

## 🔍 Exploring the Database
To view database content:

```bash
sqlite3 instance/grocery.db

# Useful commands:
.tables                 # List all tables
SELECT * FROM Product;  # View all products
.schema CartItem        # View table structure
```
# 👤 Default Accounts
Admin Account

Username: admin

Password: admin123

Customer Account

Register new account via /register

# 🛒 Using the Application
Browse products on the homepage

Add items to your cart

View/update your cart

Checkout (demo flow)

# 🛠️ Technical Details
Backend: Flask (Python)

Database: SQLite with SQLAlchemy ORM

Frontend: Bootstrap 5

Authentication: Session-based with password hashing

# 🐛 Troubleshooting
Issue	Solution
"Template not found"	Ensure templates folder exists

Database errors	Delete instance/grocery.db and restart

Missing images	Verify static/images directory

# 📜 License
MIT License - See LICENSE for details.


   
 


