# ATM Simulation Program

A simple Python-based console application that simulates basic ATM operations such as credit, debit, and mini statements. This program is designed for learning purposes and demonstrates user authentication and basic banking functionality.

---

## Features

1. **Credit:** Add funds to the account.
2. **Debit:** Withdraw funds from the account (with sufficient balance check).
3. **Mini Statement:** View the current account balance.
4. **Exit:** End the session.

---

## Program Flow

1. **User Authentication:**  
   - Enter the correct username and PIN to access the system.
   - The default username is `Swaroop` and the default PIN is `1234`.
   - Incorrect credentials will result in denial of access.

2. **Menu Options:**  
   After successful login, the following options are displayed:  
   - `1. Credit` – Enter the amount to add to the account.
   - `2. Debit` – Enter the amount to withdraw. The program checks for sufficient funds.
   - `3. Mini Statement` – View the total available balance.
   - `4. Exit` – Exit the program.

3. **Session Termination:**  
   - Selecting `4. Exit` ends the session with a friendly message.

---

## Sample Output

```plaintext
Enter your name: Swaroop
Enter your PIN: 1234

1.Credit
2.Debit
3.Mini statement
4.Exit
Enter a choice: 1
Enter the credit amount: 200
Total amount after credit: 700.0

1.Credit
2.Debit
3.Mini statement
4.Exit
Enter a choice: 2
Enter the debit amount: 300
Total amount after debit: 200.0

1.Credit
2.Debit
3.Mini statement
4.Exit
Enter a choice: 3
###MINI STATEMENT###
Total amount available in your account: 500

1.Credit
2.Debit
3.Mini statement
4.Exit
Enter a choice: 4
Thank you 🙏 
Visit Again
```

---

## Requirements

- Python 3.6 or higher.

---

## Notes

- The default username is `Swaroop` and the default PIN is `1234`. You can change these values in the code.
- This program is for demonstration purposes only and does not store data persistently.

---


Feel free to explore, modify, and improve the project. Contributions are welcome!
