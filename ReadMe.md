# Customer Banking System
## Overview
The application allows users to calculate and track interest earned and see updated balances. 
## Project Structure
- `Account.py`: Contains the `Account` class with methods to set the balance and interest.
- `cd_account.py`: Contains the function `create_cd_account` to handle CD account calculations.
- `customer_banking.py`: Main script to run the application, handle user input, and display results.
- `savings_account.py`: Contains the function `create_savings_account` to handle savings account calculations.
## Usage
1. **Navigate to Project Directory**
2. **Run the Application**
3. **Follow the Prompts**:
    - Enter the savings account balance, interest rate (APR), and the number of months.
    - Enter the CD account balance, interest rate (APR), and the number of months.
4. **View Results**:
    - The application will display the interest earned and the updated balance for both the savings and CD accounts.
## Example of how the application works:
```bash
$ python customer_banking/customer_banking.py
Enter the savings account balance: 1000
Enter the savings account interest rate (APR): 5
Enter the number of months: 12
Savings Account:
Interest Earned: $50.00
Updated Balance: $1050.00

Enter the CD account balance: 2000
Enter the CD account interest rate (APR): 3
Enter the number of months: 12
CD Account:
Interest Earned: $60.00
Updated Balance: $2060.00



