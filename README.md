# DSA_PROJECT
Developed a Smart Railway Management System using graph data structures and Dijkstra's algorithm to calculate shortest paths and fare between two stations, featuring user authentication, ticket booking, cancel booking, route optimization, pathfinding, and time estimation.

Steps to Run the Code

● View All Stations
Select option 3 from the main menu

The system will display all available stations with their index numbers

● Find Route & Calculate Fare
Select option 4 from the main menu

Enter source station index

Enter destination station index

Select a ticket class (1–4)

View distance, route path, travel time estimation and fare details

User Functions
1. Register a New User
Select option 1 from the main menu

Enter a unique username

Enter a password

Registration confirmation will be displayed

2. Login
Select option 2 from the main menu

Enter your username and password

Upon successful login, you'll see the user menu

3. Find Shortest Paths from a Station
Login first

Select option 2 from the user menu

Enter the source station index

View all possible destinations with distances and routes

4. Find Route & Calculate Fare Between Two Stations
Login first

Select option 3 from the user menu

Enter source and destination station indices

Select ticket class

View route details and fare information

5. Book a Ticket
Login first

Select option 4 from the user menu

Enter passenger name and age

Select source and destination stations

Choose ticket class

Receive booking confirmation with ticket number

6. View Your Bookings
Login first

Select option 5 from the user menu

View all your active and cancelled bookings

7. Cancel a Booking
Login first

Select option 6 from the user menu

Enter the ticket number to cancel

Receive cancellation confirmation

Test Cases
✅ Test Case 1: Route Finding & Fare Calculation
Run the application

Select option 3 to see all stations

Select option 4 to find route and fare

Enter source station index (e.g., 0 for New Delhi)

Enter destination station index (e.g., 3 for Chennai)

Select ticket class (e.g., 3 for AC)

Verify the route details, distance, and fare calculation

✅ Test Case 2: User Registration and Login
Run the application

Select option 1 to register

Enter a username (e.g., "testuser")

Enter a password (e.g., "password123")

Select option 2 to login with the same credentials

Verify successful login by checking for the user menu

✅ Test Case 3: Ticket Booking and Management
Login with your credentials

Select option 4 to book a ticket

Enter passenger details (name and age)

Select source and destination stations

Choose ticket class

Note the ticket number from the confirmation

Select option 5 to view your bookings

Verify the booking details

Select option 6 to cancel the booking

Enter the ticket number

Select option 5 again to verify the booking is now marked as cancelled

Default Stations
The system comes pre-loaded with four stations:

New Delhi (index 0)

Kolkata (index 1)

Mumbai (index 2)

Chennai (index 3)

Connections:

New Delhi to Kolkata: 1450 km

New Delhi to Mumbai: 1400 km

Kolkata to Chennai: 1650 km

Mumbai to Chennai: 1350 km


