# 🏥 Hospital Management System (HMS)

A **Java Swing-based desktop application** to manage hospital operations including patient records, doctor management, and admin functionalities — powered by MySQL.

---

## ✨ Features

- 🔐 **Admin Login System**
- 👨‍⚕️ **Doctor Management**
- 🧑‍🤝‍🧑 **Patient Management**
- 🗃️ **Secure MySQL Database Integration**
- 🖥️ **User-friendly GUI with Java Swing**

---

## 🛠️ Technologies Used

| Tech      | Description |
|-----      |-------------|
| ☕ Java  | Core application logic & Swing-based GUI |
| 🗃️ MySQL | Relational database to store hospital data |
| 🔌 JDBC  | Java Database Connectivity API |

---

## 🚀 How to Run

1. 🧱 **Set up the database**  
   Import the `hms.sql` file into your MySQL server.

2. 🛡️ **Update DB credentials**  
   Go to the DB connection class and change the username/password as per your setup.

3. ▶️ **Launch the app**  
   Open the project in NetBeans (or any Java IDE) and run `LoginPage.java`.

---

## 🔑 Default Login

| Role | Username | Password |
|------|----------|----------|
| Admin | `admin` | `admin` |

---



## 📂 Folder Structure (optional)
HospitalManagementSystem/
├── src/
│ └── hospital/
│ ├── LoginPage.java # Admin login screen
│ ├── Doctors/ # Doctor-related operations
│ │ ├── addDoctor.java # Add new doctor
│ │ ├── editDoctor.java # Edit doctor details
│ │ └── ... # More doctor modules
│ ├── Patients/ # Patient-related operations
│ │ ├── admitPatient.java # Admit a new patient
│ │ ├── dischargePatient.java # Discharge patient logic
│ │ └── ... # More patient modules
│ └── ... # Additional utility classes
├── lib/ # External libraries / dependencies
├── hms.sql # MySQL database schema
└── README.md # Project documentation




---

## 📌 Note

> Make sure your MySQL server is running before launching the app.  
> Tested on Java 8+ and MySQL 5.7+.

---

## 🤝 Contributions

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 🧙‍♂️ Author

Made with ☕ and 💻 by **[weedu230](https://github.com/weedu230)**  
_Student of Bahria University Karachi_

---




