# Backstory:
You've just landed a job at BankTech, a startup that provides innovative banking solutions to various clients. Your company is developing a new banking system that handles different types of bank accounts like Savings Account, Checking Account, and Business Account. Your manager just came in and gave you a task to implement the system using Object-Oriented Programming (OOP) concepts in Python.

# Objective:
Write a Python program that implements the concepts of abstraction, inheritance, and polymorphism.

# Task:
1) Abstraction: 
- Create an abstract class `BankAccount` that cannot be instantiated, but has common attributes and methods for all accounts, such as `accountNumber`, `accountHolderName`, `balance`, `deposit(amount)`, and `withdraw(amount)`.

2) Inheritance: 
- Create specific account classes (like `SavingsAccount`, `CheckingAccount`, `BusinessAccount`) that inherit from the `BankAccount` class and have additional attributes and methods unique to them. For example, the `SavingsAccount` class could have an additional attribute `interest_rate` and a method `add_interest()` to add the interest to the account balance.

3) Polymorphism: 
- Implement a method `account_type()` in the `BankAccount` class that can be overridden in each subclass to return the appropriate account type. For example, the `SavingsAccount` class's `account_type()` method could return "Savings Account".

4) Instantiation:
- Create instances of `SavingsAccount`, `CheckingAccount`, and `BusinessAccount`, and call their `account_type()` methods.

5) Display Information:
- Once you have completed all the steps, display the account details neatly for the user to read on the console.

# Tips:
- Remember to import the `abc` module for creating an abstract class.
- Always handle potential exceptions, especially when working with data conversions.

**Expected Output in terminal**

Account Number: 123456
Account Holder Name: John Doe
Account Type: Savings Account
Balance: $5000
Interest Rate: 2.5%

# Bonus
- create a Terminal User interface that presents the user with these options after entering the correct pin: 

> display balance and information

> withdraw money:
- mow much would you like to withdraw?

> deposit money:
- mow much would you like to deposit?

>switch account: 
*(View the same option for whatever account is selected, but show the information of that account)*



