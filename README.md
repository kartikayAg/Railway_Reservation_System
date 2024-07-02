# Railway Reservation System - README

## Overview
This project is a simple Railway Reservation System implemented in C++. It allows users to make, cancel, and inquire about train reservations, and provides an admin interface for managing train and user details.

## Features
- **Admin Mode**: Allows administrators to manage train details, add new trains, and display train details.
- **User Mode**: Allows users to reserve tickets, cancel reservations, and inquire about train schedules and availability.
- **Login System**: Ensures secure access to both user and admin functionalities.

## Classes and Methods
### Classes
1. **`login`**: Handles user login functionalities.
   - `getid()`: Prompts the user for ID and password.
   - `displayid()`: Displays the user ID and password.
2. **`Detail`**: Stores train details.
   - `getDetail()`: Prompts the admin to enter train details.
   - `displaydetail()`: Displays the train details.
3. **`reser`**: Manages reservation details.
   - `getresdet()`: Prompts the user to enter reservation details.
   - `displayresdet()`: Displays reservation details.
4. **`canc`**: Manages cancellation details.
   - `getcancdet()`: Prompts the user to enter cancellation details.
   - `displaycancdet()`: Displays cancellation details.

### Methods
1. **Admin Functions**
   - `database()`: Admin menu for managing train details.
   - `manage()`: Admin menu for managing user details.
2. **User Functions**
   - `user()`: User login and menu.
   - `reserve()`: User menu for reserving tickets.
   - `res()`: Reservation logic.
   - `cancell()`: Cancellation logic.
   - `enquiry()`: Displays train details.

### Main Menu
- `main()`: The main function providing the primary interface to choose between Admin Mode, User Mode, and Exit.

## Usage
### Compilation
To compile the program, use a C++ compiler such as g++:
```sh
g++ -o railway_reservation railway_reservation.cpp
```

### Running the Program
After compilation, run the executable:
```sh
./railway_reservation
```

### Admin Mode
1. Choose **Admin mode** from the main menu.
2. Enter the admin password (default is `admin`).
3. Use the admin menu to manage train details and user management:
   - Create train detail database.
   - Add new train details.
   - Display all train details.
   - Manage user details.
   - Display all passenger details.

### User Mode
1. Choose **User mode** from the main menu.
2. Enter your user ID and password.
3. Use the user menu to:
   - Reserve a ticket.
   - Cancel a reservation.
   - Inquire about train schedules.

### Exiting the Program
Select the **Exit** option from the main menu.

## File Handling
- **Train Details**: Stored in `t.txt`.
- **Passenger Details**: Stored in `p.txt`.
- **Cancellation Details**: Stored in `cn.txt`.
- **User Login Details**: Stored in `id.txt`.

## Contributing
1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License
This project is open-source and available under the MIT License.

---

Feel free to explore and enhance the Railway Reservation System to fit your requirements. For any issues or contributions, refer to the Contributing section.
