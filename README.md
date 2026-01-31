# 🐾 Vet Clinic Management System  
A desktop-based Veterinary Clinic Management System built using Java (Swing/AWT) and Oracle 11g, designed to manage animals, appointments, medicines, vaccinations, and clinic operations efficiently.  
This project was developed as an academic / capstone project and demonstrates end-to-end software development including database design, Java GUI, and installer-based deployment.

## 📁 Project Structure
```pgsql
vetclinicmanagementsystem/
│
├── Documentation/
│   └── Reports.pdf
│
├── Setup File/
│   ├── Database/
│   │   ├── createdatabase.bat
│   │   └── clinic.sql
│   ├── Exe File/
│   ├── Jar File/
│   └── setup.exe
│
├── Source Code/
│   └── src/
│       ├── images/
│       ├── AdminPortal.java
│       ├── AnimalDetails.java
│       ├── Appointment.java
│       ├── AddMedicine.java
│       ├── AddVaccination.java
│       └── ...
```

## ✨ Features
- 🐶 Animal registration & profile management
- 📅 Appointment scheduling & tracking
- 💉 Vaccination & medicine records
- 👨‍⚕️ Admin portal for clinic management
- 🗂 Centralized Oracle database storage
- 🖥 Desktop-based GUI application
- ⚙️ Automated database setup using .bat & .sql files

## 🛠️ Tech Stack

- ☕ **Language:** Java (Swing / AWT)  
- 🗄️ **Database:** Oracle 11g  
- ⚙️ **JDK:** Java Development Kit (JDK 1.6+)  
- 📦 **Installer:** `setup.exe` (Windows-based installer)  
- 📜 **Database Scripts:** SQL scripts & Batch (`.bat`) files  
- 🧰 **IDE:** NetBeans / Eclipse  
- 📄 **Documentation:** Detailed PDF report  


## 🧠 Architecture Overview  
The system follows a layered desktop application architecture, separating UI, business logic, and database access.

### 🏗 Architecture Diagram

```less
+---------------------------+
|       User Interface      |
|     (Java Swing GUI)      |
+-------------+-------------+
              |
              v
+---------------------------+
|   Application Logic Layer |
|   (Java Controllers)      |
+-------------+-------------+
              |
              v
+---------------------------+
|     JDBC Database Layer   |
|   (Oracle JDBC Driver)    |
+-------------+-------------+
              |
              v
+---------------------------+
|      Oracle 11g DB        |
|  Tables, Views, Records   |
+---------------------------+
```

#### 🧩 Component Breakdown
- 🖥 Java GUI
  Handles user interactions and form-based operations.
- ⚙️ Business Logic
  Manages validation, workflows, and operations.
- 🔗 JDBC Layer
  Connects Java application to Oracle database.
- 🗄 Oracle Database
  Stores animals, appointments, medicines, and user data.
- 📜 Setup Scripts
  .bat and .sql automate database creation and setup.
  
#### 📄 Documentation  
📘 Full project report available in:  
```text
Documentation/Reports.pdf
```

## ⚙️ Prerequisites
- ☕ JDK 1.6 or above
- 🧠 JRE installed
- 🗄 Oracle 11g Database
- 🖥 Windows OS
- 🔐 Admin access for environment variables

## 🚀 Installation & Run Steps  
1️⃣ Install Java
- Install JDK 1.6+
- Set Java bin path in System Environment Variables

2️⃣ Install Oracle Database
- Install Oracle 11g
- Ensure Oracle services are running

3️⃣ Create Database  
Navigate to:
```text
Setup File/Database/
```
Run:
```powershell
createdatabase.bat
```
This creates a database named:
```text
cms
```
4️⃣ Create Tables  
Execute the SQL script located in:
```text
Setup File/Database/
```
This initializes all required tables.

5️⃣ Run the Application  
Double-click:
```text
setup.exe
```
🎉 The application will launch and is ready to use.

## ❤️ Contributions
Contributions are welcome!
> Fork the repo → Create a branch → Add feature → Submit PR

</br></br>
<div align="center">
<p>📘 This project is created strictly for educational and learning purposes.</p>
<p>⭐ If you find this project helpful, feel free to star the repository!</p>
<p>© 2026 <strong><a href = "https://bemaurya.github.io">BeMaurya</a></strong>. All rights reserved.</p>
</div>
