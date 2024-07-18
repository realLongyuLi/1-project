# 1-project

//random number game

import random

maximumNumber = int(input("please enter a maximum number: "))

randomNumber = random.randint(1,maximumNumber)

print("The random number you generate from 1 to " + str(maximumNumber) + " is " + str(randomNumber))
