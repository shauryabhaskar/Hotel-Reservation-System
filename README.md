<center>

# 🏨 **Hotel Reservation System**

A lightweight Java console application that simulates a hotel reservation flow. View available rooms, make reservations by category, and view existing bookings. Designed for beginners to practice object-oriented programming, collections, and console I/O.

</center>

---

## ✨ What it does

- Displays a menu-driven CLI for hotel reservation tasks  
- Shows available rooms and details (room number, category, price)  
- Lets users make reservations (book a room by category)  
- Tracks bookings and lists them on demand  
- Basic payment simulation message printed after booking

---

## 🔎 Project overview 

- Package: `proj1`  
- Main entry: `Main` (menu & user interaction)  
- Core classes: `Rooms`, `Hotel`, `Bookings` (booking container)  
- Room examples included: `101 (Deluxe)`, `102 (Standard)`, `103 (Deluxe)`, `104 (Standard)`  
- Booking logic: `Hotel.makeReservation(customerName, category)` returns a `Bookings` object and marks the room as booked

---

🚀 Example session


--- Hotel Reservation System ---
1. View Available Rooms
2. Make a Reservation
3. View Bookings
4. Exit

   
Enter your choice: 1

Room 101 [Deluxe] - Rs. 5000.0 - Available
Room 102 [Standard] - Rs.3000.0 - Available
Room 103 [Deluxe] - Rs.5000.0 - Available
Room 104 [Standard] - Rs.3000.0 - Available

Enter your choice: 2
Enter your name: Aman
Enter room category (Deluxe/Standard): Deluxe
Booking successful!
Booking: Aman -> Room 101 [Deluxe] - Rs.5000.0 - Booked
Processing payment... Rs.5000.0
Payment successful!

Enter your choice: 3
Booking: Aman -> Room 101 [Deluxe] - Rs.5000.0 - Booked

---

🧩 Features

➤ Menu-driven CLI for ease of use

➤ Room availability checks and booking by category

➤ Tracks bookings in-memory (List of Bookings)

➤ Clear separation: Rooms model, Hotel manager, Main UI

➤ Minimal and easy-to-extend codebase — great for learning

---
🔮 Future enhancements (roadmap)

Save/load bookings to disk (CSV or JSON) so data persists between runs

Add check-in/check-out dates and calculate total cost by nights

Accept user payment details (mock or simulate) and show receipt

Add cancellation fees and refund simulation

Add search/filter for bookings by customer or room

Implement GUI (Swing/JavaFX) or a web front-end + REST backend

Add unit tests for Hotel booking logic

---

👤 Author

Shaurya Bhaskar

🔗 GitHub: https://github.com/shauryabhaskar

