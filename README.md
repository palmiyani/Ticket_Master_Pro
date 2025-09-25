🎟️ Ticket Master Pro

A Java-based Ticket Management System designed to simplify event ticket booking, customer management, and database handling. The project includes a SQL database (ticket_master_pro.sql) for persistent storage.

🚀 Features

✅ Event management (create, update, delete events)

✅ Ticket booking and cancellation system

✅ Customer registration and login

✅ Database support with MySQL/SQL script

✅ Modular Java code structure (src folder)

✅ Easy setup in Visual Studio Code or any Java IDE

📂 Project Structure
Ticket_Master_Pro/
├── ticket_master_pro.sql       # Database schema & seed data
├── src/                        # Java source files
├── lib/                        # Dependencies (if any)
├── bin/                        # Compiled Java classes
└── README.md                   # Project documentation

🛠️ Setup & Installation

Clone or extract the project.

git clone <your-repo-url>


Open the project in Visual Studio Code (or any Java IDE).

Import the SQL database:

Open MySQL or your preferred DBMS.

Run the script:

source ticket_master_pro.sql;


Build and run the project:

javac -d bin src/*.java
java -cp bin Main

🎮 Usage

Run the application.

Create events and manage tickets.

Book/cancel tickets as a customer.

View reports and ticket availability.

📦 Database

File: ticket_master_pro.sql

Contains tables for:

Events

Customers

Tickets

Preloaded with sample data for testing.

👨‍💻 Author

Pal Miyani
