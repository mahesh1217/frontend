
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
1.User selects seats.
2.Frontend sends POST request:
3.POST /api/seats/book

Backend:
========
1.Checks if seats are already booked
2.Calculates total price
3.Saves booking
4.Returns booking confirmation.
5.Frontend updates UI.
