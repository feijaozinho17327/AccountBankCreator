The Account Bank project is a simple Java program that allows users to create bank accounts and display information about these accounts. The program receives data via the terminal, such as the customer's full name, agency number, account number, and balance, and provides a welcome message with the details of the created account.

## Usage

To use the Account Bank program, follow the steps below:

1. Run the program from a compatible Java environment.

2. The program will prompt you to enter the following information via the terminal:

   - Full name of the customer (beginning with an uppercase letter and without accents or "ç").
   - Agency number in the format "1111" (Four digits).
   - Account number (Four digits).
   - Initial deposit for the account (deposit with a limit of two decimal places and a maximum amount of R$ 99999.00).

3. Enter the requested information, following the instructions displayed in the terminal.

4. After entering all the information, the program will initiate a message with the details of the created account.

## Data Validation

The Account Bank program includes methods that check if the information entered by the user meets the following criteria:

- The customer's full name must be a sequence of alphabetical characters, starting with an uppercase letter, and should be entered without accents or "ç".
- The agency number should be entered following the format of a four-digit integer, which will be formatted by the program as (e.g., "000-0").
- The account number must be a four-character integer.
- The initial balance of the account must be a decimal number limited to two decimal places and must not exceed a defined maximum limit.

These validations ensure that the entered data is consistent with the expectations of the banking system.
