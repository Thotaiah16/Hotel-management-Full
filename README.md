Welcome to the Hotel Management System a two‑part solution featuring a Desktop Manager for staff operations and a Spring Boot Web Application for customers, both backed by a shared MySQL database for real‑time, consistent data across the business.

~Hotel Management System - Desktop Manager

A powerful and intuitive JavaFX desktop application designed for hotel staff and managers to streamline daily operations. This application provides a comprehensive suite of tools for managing rooms, bookings, restaurant orders, and administrative tasks, all connected to a central MySQL database.



 Key Features

  🏨 Room Management:** Effortlessly add new rooms, update details (type, price, status), and view real-time availability at a glance.
  🍽️ Menu & Dish Management:** Complete control over the restaurant's menu. Add, edit, or remove dishes, manage categories, and set pricing.
  🧾 Bookings & Order Processing:** A centralized system to create, update, and manage room reservations and food orders from a single interface.
  🔒 Secure Manager Operations:** Includes dedicated forms, dashboards, and data viewers for administrative oversight. Sensitive operations are protected using **BCrypt** hashing for enhanced security.

🛠️ Tech Stack

  - Language/Runtime: Java 21
  - UI Framework: JavaFX + FXML
 - Database: MySQL (managed via XAMPP)
  - Key Libraries:
       MySQL Connector/J
       jBCrypt
       JSON
       JCalendar



 ⚙️ Prerequisites

Before you begin, ensure you have the following installed and configured:

  JDK 21:The Java Development Kit, version 21 or newer.
  Apache NetBeans: Your IDE for running the project. Here is the link( https://netbeans.apache.org/ )
  XAMPP:With the Apache and MySQL modules running. Here is the link( https://www.apachefriends.org/ )
  JavaFX SDK 21: The JavaFX library, which needs to be referenced by your project.


- Getting Started

Follow these steps to get the application running on your local machine.

1\. Clone the Repository

Clone this project to your local machine using your preferred method.

```bash
git clone <your-repository-url>
```

 2\. Database Setup

The application requires a MySQL database. We'll use XAMPP for this.

1.  Start XAMPP: Open the XAMPP Control Panel and start the Apache and MySQL services.
2.  Create the Database:
      * Navigate to `http://localhost/phpmyadmin/` in your browser.
      * Click on **New** in the left sidebar.
      * Enter the database name as `java_hotel_management` and click **Create**.
3.  **Import Schema: In the Hotel Management folder, sql file is provided; import it. This will create all the necessary tables.

 3\. IDE Configuration (NetBeans)

1.  Open Project: Launch NetBeans and open the cloned project (`File > Open Project...`).
2.  Add Libraries:
      |- Right-click the Libraries folder in the project tree.
      - Select Add JAR/Folder...and add the required libraries: `MySQL Connector/J`, `jBCrypt`, `JSON`, and `JCalendar`.



 4\. Run the Application

  - Ensure your main class (e.g., `LoginPage.java` or your designated launcher) is set as the project's main entry point.
  - Click the Run Project (▶️) button in NetBeans. The application's login window should now launch\!
  - Username: admin
  - password: admin
  
After login You can Explore Hotel Management System for only the Desktop Manager/Staff.



Welcome to the Hotel Application — a Spring Boot web experience for customers to register, sign in, and manage bookings and food orders securely from any browser, powered by Thymeleaf views and a shared MySQL backend.

~Hotel Web Application - Online users

-A Spring Boot web application for hotel customers to register, log in, view dashboards, check profiles, and interact with bookings and food orders. This app         runs on a server and exposes an HTTP(S) URL for browsers.

Features
Registration with email OTP 

Secure login/logout with BCrypt password hashing

Dashboard and profile pages showing user info, bookings, and food orders

Server‑side rendering with Thymeleaf templates

Shared MySQL database with the Desktop Manager

Tech stack
Backend: Spring Boot (Web/MVC), Spring Data JPA, Hibernate ORM, Java 21, Maven

Frontend: Thymeleaf templates (+ static CSS/JS/images)

Database: MySQL (Connector/J)

Email/OTP: Spring Boot Mail (Jakarta Mail) via Gmail SMTP (App Password)

Security: Session‑based auth with jBCrypt for password hashing

Testing: Spring Boot Test (JUnit 5)

Notes:
-Use Your Gmail for OTP Generation with App Password. Only after enabling 2FA Authentication.

Run locally
-In NetBeans, import the file And Click on the run button. The server will automatically start.
- This Application Only runs after the Apache and MySQL servers start.

~Security
  -Passwords stored as BCrypt hashes
                                                                                                THANK YOU
