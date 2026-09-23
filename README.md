import random

number= random.randint(1, 100)


print ("Welcome to the Number Guessing Game!")

print ("I'm thinking of a number between 1 and 100.")


guess = int(input("enter your guess: "))

if guess<number:
    print("Congratulations! You guessed the correct number.")


else:
  print("Sorry, that's not the correct number. The number was", number)

  print("Better luck next time!")# AISHA-AFZAL
 learning something new
