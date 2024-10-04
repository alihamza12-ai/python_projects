## Methods

### `__init__(bal, acc)`

- **Parameters**:
  - `bal`: Initial balance of the account.
  - `acc`: Account number.
  
### `debit(amount)`

- **Parameters**:
  - `amount`: The amount to be debited from the account.
- **Functionality**: Reduces the account balance by the specified amount and prints the new balance.

### `credit(amount)`

- **Parameters**:
  - `amount`: The amount to be credited to the account.
- **Functionality**: Increases the account balance by the specified amount and prints the new balance.

### `get_total_balance()`

- **Returns**: The current balance of the account.

## Conclusion

This `Account` class provides a basic structure for managing an account's balance with simple debit and credit operations. You can expand this class by adding features like transaction history or interest calculations.
