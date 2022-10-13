#Rock, Paper, Scissors, Lizard, Spock Game
from random import randint

#moves for the player
moves= ["Rock", "Paper", "Scissors", "Lizard", "Spock"]

while True:
    computer = moves[randint(0,4)]
    player = input("Rock, Paper, Scissors, Lizard, Spock? (or end the game)")
    if player == "end the game":
        print("The game has ended.")
        break
    elif player == computer:
        print("Tie")
    elif player == "Rock":
        if computer == "Paper":
            print("You Lose", computer, "Beats", player)
        if computer == "Scissors":
            print("You Win", player, "Beats", computer)
        if computer == "Lizard":
            print("You Win", player, "Beats", computer)
        if computer == "Spock":
            print("You Lose", computer, "Beats", player)
    elif player == "Paper":
        if computer == "Scissors":
            print("You Lose", computer, "Beats", player)
        if computer == "Rock":
            print("You Win", player, "Beats", computer)
        if computer == "Spock":
            print("You Win", player, "Beats", computer)
        if computer == "Lizard":
            print("You Lose", computer, "Beats", player)
    elif player == "Scissors":
        if computer == "Rock":
            print("You Lose", computer, "Beats", player)
        if computer == "Paper":
            print("You Win", player, "Beats", computer)
        if computer == "Lizard":
            print("You Win", player, "Beats", computer)
        if computer == "Spock":
            print("You Lose", computer, "Beats", player)
    elif player == "Lizard":
        if computer == "Scissors":
            print("You Lose", computer, "Beats", player)
        if computer == "Paper":
            print("You Win", player, "Beats", computer)
        if computer == "Spock":
            print("You Win", player, "Beats", computer)
        if computer == "Rock":
            print("You Lose", computer, "Beats", player)
    elif player == "Spock":
        if computer == "Paper":
            print("You Lose", computer, "Beats", player)
        if computer == "Scissors":
            print("You Win", player, "Beats", computer)
        if computer == "Rock":
            print("You Win", player, "Beats", computer)
        if computer == "Lizard":
            print("You Lose", computer, "Beats", player)
    else:
        print("Check the spelling.")
    
    
