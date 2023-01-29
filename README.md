# ex_3_account_classes_and_objects
Create a class called Account. Upon initialization, it should receive an id (number), a name (string), and a balance (integer; optional; 0 by default). The class should also have 3 additional instance methods:

- credit(amount) - adds the amount to the balance and returns the new balance

- debit(amount) - if the amount is less than or equal to the balance, reduces the balance by the amount and returns the new balance. Otherwise, return "Amount exceeded balance"

- info() - returns "User {name} with account {id} has {balance} balance"
