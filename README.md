This mini-project is a simple Hotel Room Booking Management System in C language that allows admins to manage rooms and customers to book rooms. The system keeps track of room details, bookings, and customer information.

Step-by-step Explanation
1. Main Menu
When the program starts, the user is presented with three options:
Admin Menu
Customer Menu
Exit

2. Admin Menu
The admin has the following options:

Add Room: Add details like Room ID, Type (Single/Double/Suite), and Price per Night. The room is marked as available by default.
View Rooms: Display the list of rooms along with their availability status.
View Bookings: View all customer bookings with details like customer name, room ID, number of days, and total price.
Exit Admin Menu

3. Customer Menu
The customer can perform the following actions:

View Available Rooms: Displays all rooms and their availability.
Book a Room:
Enter customer name.
Choose a room by entering Room ID.
Specify the number of days to stay.
The system calculates the total price (price per night * days) and marks the room as not available.
Exit Customer Menu

4. Functions Explained
add_room(): Adds a new room to the system.
view_rooms(): Shows all rooms and their availability status.
book_room(): Allows customers to book a room and calculates the total cost.
view_bookings(): Displays all customer bookings.
