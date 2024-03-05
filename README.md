# **Problem Scenario:** 

A bank needs to manage different states of customer accounts, including active, suspended, and closed. Each state has specific rules and restrictions regarding allowed operations, and accounts have associated attributes like account number and balance.

    1. Active accounts: Allow deposits and withdrawals.
    2. Suspended accounts: Disallow deposits and withdrawals transactions, but allow viewing account information.
    3. Closed accounts: Disallow all transactions and viewing of account information.

Currently, the system relies on conditional statements within the Account class to check the account state and determine valid actions. This approach becomes cumbersome and error-prone as the number of states and their associated logic grows.

# **Implement the State pattern to improve code maintainability and flexibility:**





# **UML CLASS DIAGRAM**

![image](https://github.com/Nayunnie1/CS1_StatePattern/assets/58744536/c8a27b26-b0dc-48fc-8c20-c45390067e06)
