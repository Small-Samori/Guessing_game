import random

numOfGames = 0

while(True):
    
    playOrNot = int(input("1.Play 2.Quit "))
    
    if playOrNot == 2:
        break
    else:
        numOfGames = numOfGames+1
    
        markingScheme = random.randint(1,9)

        #print(markingScheme)

        guessedNumber = int(input("Guess a number between 1 and 9: "))

        if guessedNumber > markingScheme:
            print("You are thinking too hard, your number is too high to hit the Jackpot")
        elif guessedNumber < markingScheme:
            print("You are thinking too low, your number is too low to hit the Jackpot")
        else:
            print("CONGRATS. You just hit the Jackpot, you are a millionaire. You've got to be a mind reader")
    
print("You guessed " + str(numOfGames) + " times")
