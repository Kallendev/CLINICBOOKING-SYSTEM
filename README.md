# Clinic Booking System 🏥

## 📌 Project Description
This is a MySQL-based relational database for a clinic booking system. It manages:
- Patient records
- Doctor profiles
- Appointments
- Payments

## 🛠️ How to Set Up
Step 1: Clone the Repository
Open your terminal or Git Bash and run:
git clone https://github.com/Kallendev/CLINICBOOKING-SYSTEM.git

Step 2: Navigate into the Project Folder
cd CLINICBOOKING-SYSTEM

Step 3: Log in to MySQL (Terminal Method)

- mysql -u root -p

- You’ll be prompted to enter your MySQL root password.

Step 4: Run the SQL Script
After logging in to MySQL, exit with exit;, then run this from your terminal:
- mysql -u root -p < clinic_system.sql

## Alternative (Workbench Method)
1.Open MySQL Workbench

2.Click on your MySQL connection

3.Open clinic_system.sql from the project folder

4.Click the lightning bolt (⚡) button to run the script



## 📷 ERD Screenshot
## 🗺️ ERD Diagram

![Clinic ERD](./clinicbooking%20system.drawio%20(2).png)




## 💡 Relationships
- One Patient can have many Appointments (1:M)
- One Doctor can have many Appointments (1:M)
- Each Appointment can have one Payment (1:1)
