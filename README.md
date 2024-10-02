# JAVA

# Banking Application

This is a simple Java-based Banking Application that allows users to create a bank account, deposit money, withdraw money, and check their balance. The application handles exceptions such as insufficient balance during withdrawals.

## Features
- **Create an Account**: A user can create an account with an initial balance.
- **Deposit Money**: The user can deposit money into their account.
- **Withdraw Money**: The user can withdraw money, but the application will throw an `InsufficientBalanceException` if they attempt to withdraw more than the current balance.
- **Check Balance**: The user can check their current account balance.
- **Custom Exception Handling**: Includes a custom exception (`InsufficientBalanceException`) to handle situations where the withdrawal amount exceeds the balance.

## How to Use

1. Clone the repository.
2. Compile the `BankingApplication.java` using a Java compiler.
3. Run the application.

```bash
javac BankingApplication.java
java BankingApplication
```

### Menu Options:
Once the application is running, you'll be presented with the following options:

1. **Deposit**: Enter the amount to deposit into your account.
2. **Withdraw**: Enter the amount to withdraw. If the amount is greater than your current balance, the application will show an error message.
3. **Check Balance**: Display the current balance.
4. **Exit**: Exit the application.

### Example

```
Enter account holder's name: John Doe
Enter initial balance: 500.00

Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Choose an option: 1
Enter amount to deposit: 150
Deposited: $150.0

Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Choose an option: 2
Enter amount to withdraw: 700
Error: Withdrawal amount exceeds current balance.

Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Choose an option: 3
Account Holder: John Doe, Balance: $650.0
```

## Custom Exception

- `InsufficientBalanceException`: This exception is thrown when the user tries to withdraw more money than is available in their account.

## Dependencies

- No external libraries are required. This is a pure Java application.

## Author
ABHINAV
Feel free to reach out if you have any questions or suggestions.
