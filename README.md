answer = input("What do you like to play? (yes/no) ")

if answer.lower().strip() == "yes":

    answer = input("You reach a crossroads, would you like to left or right? ").lower().strip()

    if answer == "left":

        answer = input("You encounter a monster, would you like to run or attack the monster. ")

        if answer == "attack":
            print("You killed the monster....you reached level 10. ")
        else:
            print("You run away from the monster you lost!.")


    elif answer == "right":

        answer = input("This is the land of witches, would you like to go back or attack them ")

        if answer == "attack":
            print("You killed the witch....you reached level 10. ")
        else:
            print("You run away from the witch you lost!. ")

    else:
        print("Invalid choice, you lost!")

else:
    print("That's to bad!")
