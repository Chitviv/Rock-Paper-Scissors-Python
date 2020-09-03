# Rock-Paper-Scissors-Python
Rock-Paper-Scissors-Python
# random module check to simple game Rock,Paper,Scissors
import random

mylist=["Rock","Paper","Scissors"]
a="1"
while(a=="1"):
    Computer=random.choice(mylist)
    
    Player=input("Enter Rock or Paper or Scissors:")
    print(f"The Computer choice is         :{Computer}")
    if Player == Computer:
        print("Its Tie!")
    elif(Player=="Rock") :
        if (Computer == "Paper"):
            print(f"Player-{Player} Smashes Computer-{Computer}")
        elif(Computer == "Scissors"):
             print(f"Player-{Player} Smashes Computer-{Computer}")
    elif(Player=="Scissors") :
        if (Computer == "Paper"):
             print(f"Player- {Player} cuts Computer-{Computer}")
        elif(Computer == "Rock"):
               print(f"Computer-{Computer} Smashes Player-{Player}")
    elif(Player=="Paper") :
        if (Computer == "Scissors"):
             print(f"Computer- {Computer} cuts Player-{Player}")
        elif(Computer == "Rock"):
             print(f"Computer-{Computer} Smashes Player-{Player}")       
    else:
        print("Enter correct input")
    
    
    a=input("Enter number 1 to continue :")
    print("\n")
