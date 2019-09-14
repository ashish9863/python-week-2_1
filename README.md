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
