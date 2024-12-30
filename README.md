# ATM Machine Simulation

Welcome to the **ATM Machine Simulation** project! This Python-based application replicates the core functionalities of an ATM, providing a seamless and interactive experience for users.

## Features

- **Secure PIN Management:**
  - Create a new PIN
  - Change an existing PIN

- **Account Management:**
  - Check account balance
  - Deposit money
  - Withdraw money

- **Fund Transfers:**
  - Transfer funds to another account securely

- **Loan Services:**
  - Apply for a loan
  - Check outstanding loan balance

- **Transaction Insights:**
  - View detailed transaction history
  - Access a mini statement of recent transactions

- **ATM Cash Management:**
  - Tracks available ATM cash

## How It Works

1. **Launch the Program:**
   - Run the `Atm` class in Python to start the simulation.

2. **Navigate the Menu:**
   - Choose from the available options displayed in the menu.

3. **Secure Access:**
   - Enter your PIN to perform sensitive operations.

4. **Dynamic Updates:**
   - The system automatically updates balances, transactions, and ATM cash as you interact.

## Getting Started

### Prerequisites
- Python 3.x installed on your machine.
- A code editor or terminal to run the program.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/atm-machine-simulation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd atm-machine-simulation
   ```
3. Run the program:
   ```bash
   python atm.py
   ```

## Code Overview

The project is encapsulated in the `Atm` class, featuring methods for each functionality. Highlights include:

- **Error Handling:** Robust try-except blocks to handle user input errors.
- **Data Management:** Tracks user balance, loan balance, and transaction history.
- **Modular Design:** Each feature is implemented as a separate method for clarity and reusability.

## Customization

- To change the initial ATM cash or loan limits, modify the class attributes:
  ```python
  self.atm_cash = 10000000  # Set initial ATM cash
  self.loan_balance = 0     # Initial loan balance
  ```

- Add more features or customize existing ones by editing the respective methods in the class.

## Sample Menu
```plaintext
1. Create your PIN
2. Change your PIN
3. Check Balance
4. Withdraw Money
5. Deposit Money
6. Fund Transfer
7. Apply for Loan
8. View Transaction History
9. Mini Statement
10. Check Loan Balance
11. Exit
```

## Future Enhancements

- Integrate database support for storing user information.
- Add multi-user support.
- Include an admin panel for managing ATM cash and settings.
- Develop a GUI for a more interactive experience.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contribution

Contributions are welcome! Feel free to open issues or submit pull requests to enhance the project.

---

### Author
**Muhammad Hammad**  
For inquiries, contact: hammadshah7218@gmail.com
Thank you for exploring the ATM Machine Simulation project! Your feedback and suggestions are highly valued.

