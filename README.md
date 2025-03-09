# Online School Website / เว็บไซต์โรงเรียนออนไลน์ 🏫

## Overview | เกี่ยวกับโปรเจค
This project is an **Online School Website** developed using **Java** Dynamic Web Servlet and connected to a **SQL database**. The website allows students to view courses, enroll in classes, check grades, and manage their profiles. The project is packaged as a `.war` file, which can be deployed on web servers like **Apache Tomcat** or **XAMPP**.  
โปรเจคนี้คือ **เว็บไซต์โรงเรียนออนไลน์** ที่พัฒนาด้วย **Java** Dynamic Web Servlet และเชื่อมต่อกับ **ฐานข้อมูล SQL** เว็บไซต์นี้ให้บริการสำหรับนักเรียนในการดูคอร์สเรียน สมัครเรียน ตรวจสอบเกรด และจัดการโปรไฟล์ของตัวเอง โปรเจคนี้ได้ถูกบรรจุเป็นไฟล์ `.war` ซึ่งสามารถนำไปติดตั้งบนเว็บเซิร์ฟเวอร์เช่น **Apache Tomcat** หรือ **XAMPP**

## 🏗️ Project Structure | โครงสร้างโปรเจค
The project consists of the following key components:  
โปรเจคนี้ประกอบด้วยส่วนสำคัญดังนี้:

### 1️⃣ Front-end (HTML, CSS, JavaScript) 💻
- 🚀 **Built with**: HTML for structure, CSS for styling, and JavaScript for interactivity.
- 🖱️ **UI Components**: 
  - Forms for student login, enrollment, and profile management.
  - Responsive design for seamless navigation across devices.

### 2️⃣ Back-end (Java Dynamic Web Servlet) 🔧
- 🗄️ **Database Connection**: Uses JDBC (Java Database Connectivity) to interact with an SQL database.
- 🛠️ **Servlets**: Handles HTTP requests and responses, such as user authentication, course enrollment, and grade viewing.
- 📑 **Business Logic**: Responsible for processing user inputs, querying the database, and rendering dynamic content to the web pages.

### 3️⃣ Database (SQL) 🛢️
- 🛠️ **Database**: SQL (e.g., MySQL) used for storing student information, course details, grades, and enrollment data.
- 📊 **Data Management**: Handles CRUD operations (Create, Read, Update, Delete) for student and course data.

## 🛠️ Technologies Used | เทคโนโลยีที่ใช้
- 🖥️ **Java Dynamic Web Servlet** (Back-end)
- 🗄️ **JDBC** (Database Connection)
- 🛢️ **SQL (MySQL)** (Database)
- 📑 **HTML, CSS, JavaScript** (Front-end)
- 📦 **WAR File** (Packaging for Deployment)

## 🚀 How to Run the Project  

## 🚀 How to Run the Project

### 1️⃣ Install Required Software
Make sure you have the following installed:
- ✅ **XAMPP** (for Apache and MySQL)
- ✅ **Apache Tomcat** (for deploying `.war` files)
- ✅ **Java JDK** (for Java Servlets)
- ✅ **MySQL** (for the database)
(If you prefer, you can also use **MySQL Workbench** for a graphical interface to manage MySQL)

### 2️⃣ Start Required Services
1. Open **XAMPP** and start service:
   - **Apache** ✅
   - **MySQL** ✅
2. Start **Apache Tomcat**:
   - Go to the `Tomcat/bin` folder and run:
     - `startup.bat` (Windows)
     - `startup.sh` (Mac/Linux)
   - Tomcat should run at [`http://localhost:8080`](http://localhost:8080).

### 3️⃣ Deploy `.war` File
1. Open **Tomcat Manager** at [`http://localhost:8080/manager`](http://localhost:8080/manager).
2. Log in with the default credentials (`admin/password`).
3. Scroll to **WAR file to deploy**, select **`tanachod_school_V7.war`**, and click **Deploy**.
4. The website will be available at: [`http://localhost:8080/tanachod_school_V7/`](http://localhost:8080/tanachod_school_V7/).

### 4️⃣ Set Up the MySQL Database
1. Open **XAMPP** and go to **phpMyAdmin** at [`http://localhost/phpmyadmin`](http://localhost/phpmyadmin).
2. Create a new database named `tanachod_school` (or whatever the name is used in your project).
3. Import the provided `.sql` file into the newly created database.
4. Ensure the database credentials match what’s configured in your project (e.g., in `web.xml` or database configuration file).

After completing these steps, your project should be up and running!


