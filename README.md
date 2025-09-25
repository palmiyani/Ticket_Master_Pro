# 🎟️ Ticket Master Pro  
**Topic:** *Event Ticket Booking and Management System using Java and MySQL*  

A **Java-based Ticket Management System** designed to simplify event ticket booking, customer management, and database handling. The project includes a SQL database (`ticket_master_pro.sql`) for persistent storage.  

---

## 🚀 Features  

- ✅ Event management (create, update, delete events)  
- ✅ Ticket booking and cancellation system  
- ✅ Customer registration and login  
- ✅ Database support with MySQL/SQL script  
- ✅ Modular Java code structure (`src` folder)  
- ✅ Easy setup in **Visual Studio Code** or any Java IDE  

---

## 📂 Project Structure  

```
Ticket_Master_Pro/
├── ticket_master_pro.sql       # Database schema & seed data
├── src/                        # Java source files
├── lib/                        # Dependencies (e.g., MySQL Connector/J)
├── bin/                        # Compiled Java classes
└── README.md                   # Project documentation
```

---

## 🛠️ Setup & Installation  

1. Clone or extract the project:  
   ```bash
   git clone <your-repo-url>
   ```  

2. Open the project in **Visual Studio Code** (or any Java IDE).  

3. Import the SQL database:  
   - Open **MySQL** or your preferred DBMS.  
   - Run the script:  
     ```sql
     source ticket_master_pro.sql;
     ```  

4. Build and run the project:  
   ```bash
   javac -d bin src/*.java
   java -cp bin Main
   ```  

---

## 🎮 Usage  

- Run the application  
- Create events and manage tickets  
- Book/cancel tickets as a customer  
- View reports and ticket availability  

---

## 📦 Database  

- File: `ticket_master_pro.sql`  
- Contains tables for:  
  - Events  
  - Customers  
  - Tickets  
- Preloaded with sample data for testing  

---

## 🖥️ Technologies Used  

- **Java** → Core programming language  
- **SQL (MySQL)** → Database for event, customer, and ticket data  
- **JDBC** → Connection between Java program and SQL database  
- **Visual Studio Code / Java IDE** → Development environment  
- **Git & GitHub** → Version control and collaboration  

---

## 📚 Java Libraries  

- **JDBC (Java Database Connectivity)** → To connect Java with SQL  
- **java.sql package** → Classes like `Connection`, `Statement`, `ResultSet`  
- **java.util (Collections Framework)** → Managing data structures  
- **java.io** → File handling if needed (logs/reports)  
- **MySQL Connector/J** → Required library in `/lib` for DB connection  

---

## 👨‍💻 Author  

**Pal Miyani**  
