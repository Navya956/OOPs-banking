# OOPs-banking
# Initialize a new bank account
account = BankAccount(account_number=12345678, pin=1234, balance=1000.0)

# Login to the account
account.login()  # Prompts for PIN and grants access upon correct input

# Deposit funds
account.deposit()  # Prompts to enter deposit amount and updates balance

# Withdraw funds
account.withdraw()  # Prompts to enter withdrawal amount, checks balance, and updates

# Check balance
account.check_balance()  # Displays the current balance
