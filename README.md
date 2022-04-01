import random
list = ["rock","paper","scissors"]
random_item = random.choice(list)
pick = input(str.lower("choose rock paper or scissors: "))
if random_item == "rock" and pick == "scissors":
    print("computer wins")
elif random_item == "paper" and pick == "rock":
     print("computer wins")
elif random_item == "scissors" and pick == "paper":
    print("computer wins")
elif pick == "rock" and random_item == "scissors":
    print("player wins")
elif pick == "paper" and random_item == "rock":
    print("player wins")
elif pick == "scissors" and random_item == "paper":
    print("player wins")
elif random_item == "rock" and pick == "rock":
    print("draw")
elif pick == "rock" and random_item == "rock":
    print("draw")
elif pick == "paper" and random_item == "paper":
    print("draw")
elif pick == "scissors" and random_item == "scissors":
    print("draw")





