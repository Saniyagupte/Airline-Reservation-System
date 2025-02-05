# Flight Booking System

## Overview

Flight booking system enabling customers to search, book flights, and admins to manage flights, employees, and reservations.

## Features

*   **User Roles:** Admin, Customer, Employee
*   **Admin Panel:** Flight, Employee, Reservation Management; Report Generation.
*   **Customer Features:** Authentication, Flight Search & Booking, Payment Integration, Booking Management.
*   **Notifications:** Email/SMS for booking confirmations, flight updates, payment receipts.

## Technologies

*   Frontend: HTML, CSS, JavaScript
*   Backend: Python Django
*   Database: MongoDB Atlas

## Setup

1.  Clone repo.
2.  Install dependencies (see `requirements.txt` for Django & MongoDB).
3.  Configure MongoDB Atlas in `settings.py`.
4.  `python manage.py migrate`
5.  `python manage.py createsuperuser`
6.  `python manage.py runserver`
