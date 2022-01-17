from random import shuffle
def shuffle_list(values):
    shuffle(values)
    return values

def your_guess():
    guess=''
    while guess not in ['0','1','2']:
        guess=input("Position value: 0,1 or 2 ")
    return int(guess)


def check_guess(mixer,guess):
    if mixer[guess]=='0':
        print("Wowwwwwww! You Did It")
    else:
        print("Better Luck Next Time ")
        for num,val in enumerate(values):
            if val=='0':
                print("The Correct Ans is : "+val)
values=['','0','']
guess=your_guess()   
mixer=shuffle_list(values)
check_guess(mixer,guess)
