#Develop the following app
# computer picks a random number
# the user needs to provide a guess
# the computer needs to provide a guess
# the game goes until the user has the correct guess
# Finally, the machine prints out the number of guesses

import random

picked_number = random.randint(1,101)

x = int(input("Enter your guess:"))

guessed_number = 1

#print ("The random number is: " + str(picked number ) + "and the guessed number is " + str(x))

while (picked_number !=x):
    if (x < picked_number):
        print ("Incerease the value of your guess")
    if (x > picked_number ):
        print ("Decrease the value of your guess")
    x = int(input("Enter your New guess:"))
    guessed_number += 1

print("Succesful!! Number of  guesses is: " + str(guessed_number))


*******#Exercise: develop a code that reads three integers from user and prints out the maximum of the numbers.
#Required Time: 10 minutes

x= int(input("integer number 1: "))
y= int(input("integer number 2: "))
z= int(input("integer number 3: "))

if(x>y,z):
     print("maximum of the three is:" +(str(x)))
if (y>x,z):
     print("maximum of the three is:" +(str(y)))
if (z>x,y):
    print("maximum of the three is:" +(str(z)))



*******Develop the code that takes in three integers and prints out if they belong to a right triangle

# biggest_number = 0
a =  int(input("Enter number a "))
b =  int(input("Enter number b"))
c=   int(input("Enter number c"))

if (a==b and b==c):
     print(str(a) + " is the maximum")
if (a>b and a>c):
     print(str(a) + "is the maximum")
if (b>a and b>c):
     print(str(b) + "is the maximum")
if (c>b and c>a):
     print(str(c) + "is the maximum ")

if (a**2 == b**2 + c**2) or(b**2 == a**2 + c**2) or (c**2 == b**2 + a**2):
    print("Yes, they belong to a right triangle.")
else:
    print("No, they belong to a right triangle.")



