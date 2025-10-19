## Repository Name  
**`python-login-age-check`**  

## Description  
A simple Python script for beginner-friendly **login authentication** and **age verification**. Perfect for learning Python input handling and conditionals.  

## Script Overview  

- **Author:** Terex (with help from my middle school teacher)  
- **Functionality:**  
  - Asks the user for a **username** and **password**  
  - Grants access only if the password is `"QWERTY"`  
  - Checks the user’s **age**  
  - Allows access only if the user is **18 or older**  

```python
# Tickets
# Made by Terex (tho my teacher from middle school helped me)

user_name = input("Type username: ")
password = input("Type password: ")

if password != "QWERTY" and (len(user_name) > 0):
   print("You are not allowed")
   exit()

age = int(input("Type age: "))
if (age >= 18):
   print("You are welcome")
else:
    print("You are not allowed till 18 yo")
