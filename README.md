
| CS-665       | Software Design & Patterns |
|--------------|----------------------------|
| Name         | Qinchen Gu                 |
| Date         | 02/07/2024                 |
| Course       | Spring                     |
| Assignment # | 1                          |

# Assignment Overview
This is a software application to control a fully automated beverage
vending machine. 

# GitHub Repository Link:
https://https://github.com/Lunaticgq/Qinchen_Gu-cs-665-assignment-1

# How is Flexibility?
This program is pretty flexible and easy for modifications. Only added a new enum constant with price designed to 
program will finish the job of adding a new drink. And vice versa, delete the respective constant from enum is only 
action taken for remove a drink.

# How are Simplicity and Understandability?
As mentioned above, an enum represent drink types is used, thus code will be more clear and readable. It clearly 
described types and prices and other attributes by a specific construct. Different classes serve distinct 
responsibilities, so muddled will not happen, at least in most scenarios. 

# How you avoid duplicated code?
After enumeration types to represent all drink types and prices, only specified drink types are considered in the 
program. This action eliminates the need for repeated checking of drink types. Also, all codes about interacting with 
users for example calculating prices and obtaining order information are located in a separate class.

# Why avoid duplicated code is important?
Since less code there are, more readable it is, and it will be easier for debugging. Also, this action can make modify 
of code much easier.

# Design Pattern
Strategy Pattern. Since strategy pattern can handle similar objects with different behaviors, which is quite suitable 
for drinks, condiments and prices. 

## Compile
Type on the command line: 

```bash
mvn clean compile
```





