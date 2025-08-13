 ATM Management System

A Java-based desktop application that simulates an ATM interface.  
This project demonstrates Java Swing-based GUI development, MySQL database integration, and core banking operations.

Features

User Authentication  
- Sign up with personal details  
- Secure login with card number and PIN  

Banking Operations  
- Deposit  
- Cash withdrawal  
- Fast Cash  
- Mini Statement  
- Pin Change  
- Balance Enquiry  

Database Integration  
- MySQL database for storing user details and transaction history  
- MySQL queries are provided in `mysqlQueries.sql` to set up the database schema and initial data  


Technology Stack

- Java: Core application logic  
- Swing and AWT: GUI components  
- MySQL: Database for user and transaction data  

Project Structure

ATM-Management-System/  
├── images/  
│   ├── atm.jpg  
│   ├── bank.png  
│   └── bank1.png  
├── BalanceEnq.java  
├── FastCash.java  
├── LoginPage.java  
├── MiniStatement.java  
├── PinChange.java  
├── SignUp1.java  
├── SignUp2.java  
├── SignUp3.java  
├── deposit.java  
├── mysql-connector-java-8.0.28.jar  
├── mysql.java  
├── mysqlQueries.sql  
├── transaction.java  
└── withdraw.java  

Setup and Installation

1. Clone the repository:  
git clone https://github.com/vaibhav-pant/ATM-Management-System.git
cd ATM-Management-System

2. Database Setup:  
- Ensure MySQL is installed and running  
- Add your MySQL username and password in the `mysql.java` file  
- Import the `mysqlQueries.sql` file to set up the database schema and initial data  

3. Run the Application:  
- Compile the Java code using `javac`  
- Run the main class (e.g., `LoginPage.java`)

  Commands:
- javac -cp ".;jcalendar-tz-1.3.3-4.jar;mysql-connector-java-8.0.28.jar" *.java
- java -cp ".;jcalendar-tz-1.3.3-4.jar;mysql-connector-java-8.0.28.jar" LoginPage

Sign Up:  
- New users can sign up by providing personal details across three forms  
- Details include name, address, contact information, etc.  

Login:  
- Use the card number and PIN created during sign-up  

Banking Operations:  
- Perform transactions like balance inquiry, PIN change, deposit, and withdrawal  
