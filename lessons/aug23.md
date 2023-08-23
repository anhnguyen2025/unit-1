# Class code

```.py
# This is a comment
"""
This class is about the basics of programming
Aug 23
"""
# Get input from the user
first_name = input("Please enter your first name ")
#output
print("Hello ", first_name)

# other types of variables
school = "uwcisak.jp" #strings
year = 2025 #numbers
height = 180.8 #float: decimals numbers
is_student = True

last_name = input("Please enter your last name ")
#output
email = f"{year}.{first_name}.{last_name}@{school}"
print(email)

message = ("Welcome to the smartest temperature converter")
print(message)
print("#"*len(message))
fahrenheit = input("Enter the current temperature in F")
#before converting we need to validate that the user knows how to read
if fahrenheit.isdigit() == True:
    celsius = (int(fahrenheit) - 32)*5/9
    print(f"This temperature is {celsius} C")
else:
    print("WRONG INPUT.USE DECIMAL NUMBERS".lower())


```




