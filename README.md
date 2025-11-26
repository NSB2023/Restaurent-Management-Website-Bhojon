# Restaurent-Management-Website-Bhojon
Bhojon – Food Delivery Web Application

Bhojon is a full stack food delivery platform built using Django, where users can browse meals, add items to a cart, place orders.
It includes role based dashboards for Customers, Admin, Restaurant Owners and Delivery Personnel.
A simple chatbot is also included to provide menu suggestions and answer basic user queries.

#Key Features:
### User Features

1.Browse restaurants and food items
2.Add to cart & place orders
3.Built in chatbot for recommendations
4.Profile / account management

### Admin Panel

1.Manage restaurants
2.Manage users
3.View orders and system analytics
4.Restaurant Owner Panel
5.Add, edit, update menu items
6.Manage incoming orders
7.Update preparation status
8.Delivery Personnel Panel
9.View assigned deliveries
10.Update delivery progress

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

