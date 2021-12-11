# dice-game-python-project
import random

u=input("enter 0 to exit or press any key to continue ")
while(u!='0'):
    x=random.randint(1,6)
    n=input("press y to roll the dice and 0 to end ")
    if(n=='y'):
        print("j")
        if(x==1):
            print("-----------------")
            print("[               ]")
            print("[               ]")
            print("[       0       ]")
            print("[               ]")
            print("[               ]")
            print("-----------------")
        elif(x==2):
            print("-----------------")
            print("[               ]")
            print("[               ]")
            print("[       0  0    ]")
            print("[               ]")
            print("[               ]")
        elif(x==3):
            print("-----------------")
            print("[               ]")
            print("[               ]")
            print("[       0 0     ]")
            print("[        0      ]")
            print("[               ]")
            print("-----------------")
        elif(x==4):
            print("-----------------")
            print("[               ]")
            print("[               ]")
            print("[       0 0     ]")
            print("[       0 0     ]")
            print("[               ]")
            print("-----------------")
        elif(x==5):
            print("-----------------")
            print("[               ]")
            print("[       0 0     ]")
            print("[       0 0     ]")
            print("[        0      ]")
            print("[               ]")
            print("-----------------")
        else:
            print("-----------------")
            print("[               ]")
            print("[       0 0     ]")
            print("[       0 0     ]")
            print("[       0 0     ]")
            print("[               ]")
            print("-----------------")
            continue
    elif(n=='0'):
            print("thanks for playing : ")
            break
    else:
        print("please enter correct value ")
        pass

