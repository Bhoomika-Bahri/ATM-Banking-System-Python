# ATM-Banking-System-Python
PIN-based ATM Banking System using Python and File Handling


## Project Overview

This project is a **PIN-based ATM Banking System** developed using Python.  
It simulates basic banking operations such as account creation, login authentication, deposit, withdrawal, balance inquiry and transaction history.

The system is implemented using file handling and JSON storage instead of a database making it suitable for academic learning and understanding core programming concepts.

## Objectives

- To simulate the working of an ATM system.
- To implement authentication using PIN.
- To perform basic banking operations.
- To understand file handling and data persistence in Python.
- To apply data structures like dictionaries and lists.

## Technologies Used

- Python.
- Google Colab.
- JSON (for data storage).
- File Handling.

## Features

- Account creation with unique account number.
- PIN-based login system.
- Deposit and withdrawal functionality.
- Balance checking.
- Transaction history tracking.
- Menu-driven interface.
- Data stored in JSON format (`bank_data.txt`).

## System Design

The system uses:

- **Dictionary** → to store account data (key = account number).
- **List** → to store transaction history.
- **JSON file** → for persistent storage.

## Working Flow

1. Load existing data from file.
2. User selects:
   - Create Account.
   - Login.
3. After login:
   - Deposit.
   - Withdraw.
   - Check balance.
   - View account details.
4. Data is saved after every transaction.

## Limitations

- No encryption for PIN (stored as plain text).
- No database integration.
- No advanced input validation.
- Temporary storage in Google Colab environment.
- Possible duplicate account creation.

## Future Improvements

- Add PIN encryption (hashing).
- Integrate database (MySQL / MongoDB).
- Add input validation.
- Prevent duplicate accounts.
- Develop GUI (Tkinter / Web Interface).

# Conclusion

This project demonstrates how a basic ATM system can be implemented using Python.  
It provides a strong foundation in file handling, authentication logic and data structure usage.
