# Bank Management System

## Project Description
The **Bank Management System** is a Python-based GUI application designed to perform basic banking operations like account creation, balance inquiry, deposits, and withdrawals. This project demonstrates the use of the `tkinter` library for GUI and Python file handling for data persistence.

## Features
1. **Account Creation**
   - Create a new bank account with a unique account number.
   - Users must provide their name, an initial deposit, and a secure PIN.

2. **Login System**
   - Secure login using account number and PIN.

3. **Deposits and Withdrawals**
   - Add funds to an account.
   - Withdraw funds with validation for sufficient balance.

4. **Balance Inquiry**
   - Check the current account balance.

5. **Transaction History**
   - View detailed transaction history for each account, including timestamps, credits, and debits.

6. **User-Friendly Interface**
   - Intuitive navigation using buttons and forms.

7. **Secure Logout**
   - End the session safely to protect account data.

## Technologies Used
- **Programming Language**: Python
- **GUI Library**: tkinter
- **Data Storage**: File handling (text files)

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/bank-management-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd bank-management-system
   ```
3. Run the application:
   ```bash
   python bank.py
   ```

## File Structure
- `bank.py`: Main application script.
- `Accnt_Record.txt`: Tracks the latest account number.
- `<AccountNumber>.txt`: Stores account details (e.g., PIN, balance, name).
- `<AccountNumber>-rec.txt`: Stores transaction history for the account.

## Usage
1. Launch the application by running `bank.py`.
2. Use the main menu to either log in or create a new account.
3. Perform banking operations such as deposits, withdrawals, or balance inquiries.
4. View transaction history for detailed account activities.
5. Logout securely after use.

## Future Enhancements
- Encrypt sensitive data for enhanced security.
- Replace text file storage with a database for better scalability.
- Add features like:
  - Fund transfers between accounts.
  - Loan and interest calculation.
  - Multi-user access and role-based permissions.

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue to discuss any feature or bug.

## Contact
For any questions or feedback, reach out at:
- Email: ajinkyawagh2005@gmail.com
- GitHub: https://github.com/ajinkyawagh4846
