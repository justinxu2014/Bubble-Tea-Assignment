# Bubble Tea Shop Assignment
# Introduction
### A bubble tea shop has hired you to create a program that stores a customer order and prints a receipt of the transaction. For simplicity, This assignment is split into 2 parts. 

# Part 1
### How do we store items for our order? One way we can do it is using Object Oriented Programming. In this part, you will implement a class that represents a bubble tea in an order. You will then create a bubble tea object and print out it's details. 

- Criteria for class
    - Each bubble tea has parameters which can be customized
        - Name
        - Price ($)
        - Size (Regular or Large)
        - Sugar Level (100%, 75%, 50%, 25%)
        - Ice Level (100%, 75%, 50%, 25%)
        - Bubbles (Yes, No)
    - Bubble tea parameters are private

Example Output:
```java
Rose Milk Tea 
Price: $7.50
Size: Regular 
Sugar: 50%
Ice: 50%
Bubbles: Yes
```
# Part 2
### Now that we understand how to represent a bubble tea item using classes, we have the tools to complete the program. In this part, you modify your program to allow a customer to add multiple items to their order and print a receipt detailing the transaction.


### *Details not Implemented

Example Receipt:
```java
-------------------------
        Receipt
-------------------------
Rose Milk Tea       $7.50
Rose Milk Tea       $7.50

Subtotal:          $15.00
Tax(6%):            $0.90
Tip:                $1.00
Total:             $16.90
```
