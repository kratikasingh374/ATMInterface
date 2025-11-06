🏦 ATM Interface – Java Console Project

A simple ATM Simulation System built using Core Java and the Scanner class.
Users can register, log in, and perform basic banking operations like deposit, withdraw, transfer, and view transaction history — all in the command-line interface.

✨ Features

✅ User Registration & Login

💰 Deposit and Withdraw with limits

💸 Transfer money to other users (name-based)

📜 Transaction History tracking

📊 Balance Check

🔐 Secure login system using username and password

📚 Efficient StringBuilder for transaction history

🧩 Tech Stack

Language: Java

IDE (optional): VS Code / IntelliJ / Eclipse

No external libraries — only java.util.Scanner

⚙️ How to Run

Clone or download this repository.

git clone https://github.com/<your-username>/ATM-Interface.git


Open the folder in your IDE or terminal.

Compile the program:

javac ATMinterface.java


Run the program:

java ATMinterface

🧠 Program Flow

User registers by entering name, username, password, and account number.

Login using correct credentials.

Choose from these options:

Withdraw

Deposit

Transfer

Check Balance

View Transaction History

Exit

📸 Sample Output
*****************WELCOME TO ATM******************
1. Register 
2. Exit
Choose an option: 1
Enter your Name: Kratika
Enter your Username: Kratika01
Enter your Password: ****
Enter your Account Number: 12345
Registration Successful. Please log in to your Bank Account.

1. Login 
2. Exit
Enter your choice: 1
Enter your Username: Kratika01
Enter your Password: ****
Login Successful

**********************WELCOME TO YOUR BANK ACCOUNT*********************
1. WITHDRAW
2. DEPOSIT
3. TRANSFER
4. CHECK BALANCE
5. TRANSACTION HISTORY
6. EXIT
