# OddEven-Project
Function to check odd &amp; even numbers
def check_even_odd(num):
     if num % 2 == 0:
        return "Even"
     else:
        return "Odd"
# Input from the user
num = int(input ("Enter a number:"))
#Display the result
result = check_even_odd(num)
print(f"The number {num} is {result}.")
#Loop two times
for i in range(2):
    num = int(input("Enter a number:"))
    result = check_even_odd(num)
    print(f" The number {num} is {result}.")
