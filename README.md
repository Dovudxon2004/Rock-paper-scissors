# Rock-paper-scissors
It's a rock-paper-scissors game
a='rock'
b='scissors'
c='paper'
player1=input('Player1, your choice:')
player2=input('Player2, your choice:')
if player1 == a and player2 == b:
    print('congratulations, player1')
elif player1 == a and player2 == c:
    print('congratulations, player2')
elif player1 == b and player2 == a:
    print('congratulations, player2')
elif player1 == b and player2 == c:
    print('congratulations, player1')
elif player1 == c and player2 == a:
    print('congratuations, player1')    
elif player1 == c and player2 == b:
    print('congratulations, player2')
elif player1 == a and player2== a:
    print('It was draw.')    
elif player1 == b and player2 == b:
    print('It was draw')
elif player1 ==c and player2 == c:
    print('It was draw')
else: print("Either or both of you didn't type rock, paper, scissors correctly. Please, restart the game")
