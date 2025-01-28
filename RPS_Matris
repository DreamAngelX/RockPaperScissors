import random

#                 R        P        S
choice_box = [[0, 1, -1], [-1, 0, 1], [1, -1, 0]]
choices = ["R", "P", "S"]

computer = random.randint(0, 2)
player = input("Rock (R)\nPaper (P)\nScissors (S)\n").upper()

print("Computer's choice: " + str(choices[computer]))
print("Player's choice: " + str(player))

if player not in choices:
    print("Invalid choice!")
else:
    player_index = choices.index(player)
    result = choice_box[computer][player_index]
    
    if result == 0:
        print("It's a tie!")
    elif result == 1:
        print("Congratulations! You won!")
    elif result == -1:
        print("You lost!")
