# Hospital Management System

A simple hospital management system built with Java Swing and MySQL.

---

## 🚀 Features

- **Login:** Secure login for authorized users.
- **Doctor Records:**
  - Add new doctors
  - View all doctors
  - Edit doctor information
  - Delete doctors
- **Patient Records:**
  - Admit new patients
  - View all patients
  - Edit patient information
  - Discharge patients
- **User-Friendly Interface:** All forms are centered and have a clean layout.
- **Database Integration:** Uses MySQL to store and retrieve data.

---

## 🛠️ How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/weedu230/Hospital-Management-System
    ```

2.  **Set up the database:**
    - Make sure you have MySQL installed and running.
    - Create a new database named `hms`.
    - Import the `Database File/hms.sql` file to create the necessary tables.

3.  **Configure the database connection:**
    - Open the `DBConnection.java` file and update the following line with your MySQL username and password:
      ```java
      return DriverManager.getConnection("jdbc:mysql://localhost:3306/hms", "root", "");
      ```

4.  **Run the application:**
    - Compile and run the `LoginPage.java` file to start the application.

---

## 🔑 Default Login

| Role    | Username | Password |
| ------- | -------- | -------- |
| Admin   | `admin`  | `admin`  |

---

## 📌 Note

> Make sure your MySQL server is running before launching the app.
> Tested on Java 8+ and MySQL 5.7+.

---

## 🤝 Contributions

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 🧙‍♂️ Author

Made with ☕ and 💻 by **[weedu230](https.github.com/weedu230)**  
_Student of Bahria University Karachi_
