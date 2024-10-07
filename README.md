import random 

while True:
    ls = ['rock','paper','scissors']
    rps = input("Lets play Rock/Paper/scissors ")
    crps = random.choice(ls)
    if rps == crps:
        print(f"I choices {crps} tied")     
    elif rps == 'rock' and crps == 'scissors':
        print(f'I choices {crps} you win')
    elif rps == 'paper' and crps == 'rock':
        print(f"I choices {crps} you win")
    elif rps == 'scissors' and crps == 'paper':
        print(f'I choices {crps} you win')
    else:
        print(f"I choices {crps} You suck")
