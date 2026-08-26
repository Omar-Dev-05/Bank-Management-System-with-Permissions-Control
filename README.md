# Bank Management System with Permissions Control

A console-based banking management system developed in C++.

The application provides a complete interface for managing bank clients, performing financial transactions, and controlling user permissions. It allows authorized users to add, delete, update, search, and display client records, as well as perform deposits, withdrawals, and manage user accounts based on assigned permissions. Client and user data are stored persistently in text files.

## Features

- Display all registered clients.
- Add new clients.
- Prevent duplicate account numbers.
- Delete clients by account number.
- Update client information.
- Search for clients by account number.
- Display detailed client information.
- Deposit money into client accounts.
- Withdraw money from client accounts.
- Prevent withdrawals exceeding the available balance.
- Calculate and display total balances.
- Display all system users.
- Add new users.
- Prevent duplicate usernames.
- Delete users.
- Update user information.
- Search for users by username.
- Assign permissions to users.
- Support full system access.
- Control access to client management features.
- Control access to transaction features.
- Control access to user management features.
- Store and retrieve client data using text files.
- Store and retrieve user data using text files.
- Convert records between structured data and text-file format.
- Separate client management, transactions, and user management menus.
- Menu-driven console interface.
- Login system using username and password.

## Client Information

Each client record contains:

- Account Number
- PIN Code
- Name
- Phone Number
- Account Balance

## User Information

Each user record contains:

- Username
- Password
- Permissions

## Technologies Used

- C++
- Standard Library
- File Handling (`fstream`)
- Vectors (`vector`)
- Structures (`struct`)
- Enumerations (`enum`)
- String Manipulation
- Console Input/Output
- Data Processing
- Access Permissions Control

## Data Storage

Client records are stored in a text file named:

`Clients.txt`

User records are stored in a text file named:

`Users.txt`

Each record is stored as a single line using the following separator:

`#//#`

The application reads records from the files when required and writes changes back to the files after adding, updating, deleting, and performing financial transactions.

## Permissions System

The system provides permission-based access control for different operations.

Available permissions include:

- Show Client List
- Add New Client
- Delete Client
- Update Client
- Find Client
- Transactions
- Manage Users

Users can either receive specific permissions or be given full access to the system.

Unauthorized users are prevented from accessing restricted features.

## Getting Started

### Prerequisites

To build and run this project, you need:

- A C++ compiler such as GCC or Microsoft Visual C++.
- A C++ development environment such as Visual Studio or Visual Studio Code.

### How to Run

1. Clone the repository:

`git clone https://github.com/Omar-Dev-05/Bank-Management-System-with-Permissions-Control.git`

2. Open the project in your preferred C++ IDE.

3. Make sure `Clients.txt` and `Users.txt` are available in the project directory.

4. Build the project.

5. Run `main.cpp`.

6. Log in using a valid username and password.

7. Use the main menu according to the permissions assigned to the current user.

## Main Menu

The application provides the following options:

`[1] Show Client List`  
`[2] Add New Client`  
`[3] Delete Client`  
`[4] Update Client Info`  
`[5] Find Client`  
`[6] Transactions`  
`[7] Manage Users`  
`[8] Logout`

## Transactions Menu

The transaction section provides:

`[1] Deposit`  
`[2] Withdraw`  
`[3] Total Balances`  
`[4] Main Menu`

## Manage Users Menu

The user management section provides:

`[1] List Users`  
`[2] Add New User`  
`[3] Delete User`  
`[4] Update User`  
`[5] Find User`  
`[6] Main Menu`

## Project Structure

The project is implemented as a C++ console application and includes functionality for:

- Bank client management
- User management
- User authentication
- Permissions control
- Client record searching
- Client information updating
- User information updating
- File-based data persistence
- Deposit and withdrawal operations
- Total balance calculation
- Transaction management
- Record conversion
- Permission validation
- Main menu navigation
- Console-based user interaction

## About the Author

**Omar Abobakr** is a software developer focused on problem-solving and building practical software projects.
