# Smart Banking Console Application

A Python-based, menu-driven banking system built to demonstrate object-oriented programming (OOP) concepts and interactive console input. The project was developed and tested in Jupyter Notebook using the Anaconda environment.

## Features

- Create customer accounts using an account number, name, and PIN
- Secure account login with account number and PIN authentication
- Deposit and withdraw money
- Check the current account balance
- View transaction history
- Transfer funds between registered accounts
- Log out safely or exit the application

## Project Design

The application is organized around three main components:

| Component | Responsibility |
| --- | --- |
| `Bank` class | Stores accounts, authenticates customers, and handles money transfers. |
| `Account` class | Manages account data, deposits, withdrawals, balances, and transaction records. |
| Main program | Presents the menu-driven interface and connects user actions to the banking logic. |

## Requirements

- Python 3.x
- Jupyter Notebook (recommended)
- Anaconda (optional, recommended for the original development environment)

No external Python packages are required for the core application.

## Example Workflow

1. Create two accounts, for example **Tahsin** and **Rubi**.
2. Log in using an account number and PIN.
3. Deposit `₹5000`.
4. Withdraw `₹1000`.
5. Transfer `₹2000` to another account.
6. Review the transaction history to confirm each operation.
7. Log out or exit safely.

## Sample Transaction History

```text
Deposit: +₹5000
Withdrawal: -₹1000
Transfer to Rubi: -₹2000
```

## Learning Outcomes

This project provides hands-on practice with:

- Classes, objects, methods, and encapsulation
- Managing program state with Python data structures
- User input validation and menu-driven control flow
- Authentication with PIN credentials
- Recording and displaying transaction history

## Future Improvements

- PIN hashing and stronger credential validation
- Persistent account storage using files or a database
- Interest and loan management
- Account statements and exportable reports
- Graphical or web-based user interface
- Automated tests and exception handling enhancements

## Disclaimer

This is an educational prototype and is not intended for real banking use. Production banking software requires encryption, secure password hashing, audit controls, regulatory compliance, and robust data protection.

## License

This project is available for educational use. Add a license file if you plan to distribute or reuse it publicly.
