# Railway Reservation System

## Overview
The **Railway Reservation System** is a C++ project designed to manage user accounts, book train tickets, and authenticate users. This project simulates the basic functionalities of a railway ticket booking system and provides an interactive console interface for users.

## Project Structure
Here's how the project is organized:

```
RailwayReservationSystem/
├── main.cpp              // Entry point of the application
├── Header.h              // Header file containing class declarations and function prototypes
├── User.cpp              // Implementation of User class methods
├── User.h                // Header file for the User class
├── Data.txt              // File to store user data (used for persistence)
└── README.md             // Project documentation (this file)

```

## Features
- **User Account Creation**: Users can create an account with required details.
- **User Login**: Existing users can sign in and access their accounts.
- **Ticket Booking**: Authenticated users can book train tickets.
- **Data Storage**: User data is stored in `Data.txt` for persistence.

## Requirements
- **Compiler**: C++11 or higher.
- **Operating System**: Cross-platform (Windows, macOS, Linux).
- **IDE**: Visual Studio, Code::Blocks, or any C++ compatible editor.

## How to Set Up and Run
### 1. Clone the Repository
To set up the project locally, clone it using the following command:
```bash
git clone  origin https://github.com/ARWA2003/RailWay-System.git

```
## How to Set Up and Run the Project

### Step 1: Open Visual Studio
- Launch Visual Studio on your computer.
- Select **File > Open > Project/Solution**.

### Step 2: Create a New Project or Open an Existing Project
- **New Project**: Select **Create a new project** and choose **Empty Project** under C++.
- **Existing Project**: Navigate to the folder containing the project and open `main.cpp`.

### Step 3: Add Source Files
Ensure that `main.cpp`, `Header.h`, `User.h`, and `User.cpp` are added to your project:
- Right-click on **Source Files** in the Solution Explorer.
- Choose **Add > Existing Item** and select `User.cpp` and `main.cpp`.
- Right-click on **Header Files** and add `Header.h` and `User.h` similarly.

### Step 4: Configure Project Settings
Ensure the project is set to use C++11 or higher:
- Right-click on the project in **Solution Explorer**.
- Select **Properties**.
- Navigate to **C/C++ > Language** and set **C++ Language Standard** to **ISO C++11** or higher.

### Step 5: Compile the Project
- Click **Build > Build Solution** or press `Ctrl + Shift + B` to compile the project.

### Step 6: Run the Project
- Click **Debug > Start Without Debugging** or press `Ctrl + F5` to run the application.
- Follow the on-screen prompts to create an account, sign in, or book a ticket.

## How to Use the Application

### 1. Create an Account
- Select option **1** from the main menu.
- Provide the required details (e.g., username, password, and other necessary information).

### 2. Sign In
- Select option **2** from the main menu.
- Enter your credentials to log in.

### 3. Book a Ticket
- After logging in, follow the on-screen instructions to book a ticket.
## License
This project is open-source and free to use for educational and personal purposes.

## Contact
For questions or feedback, reach out to **Arwa Hossam** at **arwais.2222003@gmail.com**.



