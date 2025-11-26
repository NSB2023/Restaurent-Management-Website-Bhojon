# Restaurent-Management-Website-Bhojon
Bhojon – Food Delivery Web Application

Bhojon is a full stack food delivery platform built using Django, where users can browse meals, add items to a cart, place orders.
It includes role based dashboards for Customers, Admin, Restaurant Owners and Delivery Personnel.
A simple chatbot is also included to provide menu suggestions and answer basic user queries.

#Key Features:
### User Features

-Browse restaurants and food items
-Add to cart & place orders
-Built in chatbot for recommendations
-Profile / account management

### Admin Panel

-Manage restaurants
-Manage users
-View orders and system analytics
-Restaurant Owner Panel
-Add, edit, update menu items
-Manage incoming orders
-Update preparation status

-Delivery Personnel Panel
-View assigned deliveries
-Update delivery progress

## Tech Stack

Backend: Django 5.x, Python 3
Database: SQLite
Frontend: HTML, CSS, Bootstrap 5
Tools: Virtualenv, Django Admin, Django Templating System

📂 Project Structure
Bhojon/
│── Bhojon/               
│── members/              
│── dashboard/            
│── bot/                 
│── static/              
│── templates/            
│── venv/                 
│── manage.py
│── requirements.txt

# Setup Instructions (Local Machine)
1. Clone the Repository
git clone https://github.com/your-username/Bhojon.git
cd Bhojon
2. Create & Activate Virtual Environment
macOS / Linux:
python3 -m venv venv
source venv/bin/activate
Windows:
python -m venv venv
venv\Scripts\activate

3. Install Dependencies
python3 -m pip install --upgrade pip
python3 -m pip install -r requirements.txt
4. Apply Migrations
python3 manage.py migrate

5. Create a Superuser (Optional)
python3 manage.py createsuperuser

Login at:
http://127.0.0.1:8000/admin/
6. Run the Server
python3 manage.py runserver

