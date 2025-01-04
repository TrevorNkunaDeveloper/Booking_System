# Booking System Project

A Django-based Booking System that allows users to:
- View available rooms and scenic locations.
- Book and cancel rooms.
- Manage profile pictures and payment options.

## Table of Contents
1. [Project Description](#project-description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Credits](#credits)

## Project Description
This project is designed to provide a seamless booking experience for users. It offers features such as room listing, profile management, and secure payment integration using various payment options (e.g., PayPal, Visa, Mastercard).

## Installation
To run this project locally, follow these steps:

```bash
git clone https://github.com/trevornkunadeveloper/BookingSystem.git
cd BookingSystem
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

##Usage
- Navigate to http://127.0.0.1:8000/ in your browser after starting the server.
- Use the interface to:
- View room details and images.
- Book or cancel rooms.
- Manage user profiles.

##Credits
Author - Hlulani Trevor Nkuna
