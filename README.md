
Step 1: Navigate to frontend folder
Step 2: Install dependencies
npm install
Step 3: Start React app
npm start
http://localhost:3000

How to Use the Application
===========================

1.Enter your name.
2.Select one or more available seats.
3.Total price updates dynamically.
4.Click Buy.
5.Confirm booking.
6.Seats become booked and UI refreshes.

 Booking Flow:
=============
User selects seats.
Frontend sends POST request:
POST /api/seats/book

Backend:
========
Checks if seats are already booked
Calculates total price
Saves booking
Returns booking confirmation.
Frontend updates UI.
