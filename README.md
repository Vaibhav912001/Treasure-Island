# Treasure-Island
Used Conditional statements of python to create a treasure island game. Also, Used ASCII art to draw the treasure.
print('''*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\` . "-._ /_______________|_______
|                   | |o;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/[TomekK]
*******************************************************************************
      ''')


print("Welcome to the Treasure Island")
print("Your mission is to find the treasure")

first = input("Where do you want to go, Left or Right?")
if first == 'Left':
    second = input("What do you want to do, Swim or Wait?")
    if second == "Wait":
        third = input("Which door would you like to choose, Red or Blue or Yellow?")
        if third == "Yellow":
            print("You Won")
        elif third == "Red":
            print("You have been burnt by fire, Game Over")
        elif third == "Blue":
            print("You have been eaten by a beast, Game Over.") 
            
        else:
            print("Game Over")   
    else:
        print("You have been attacked by a trout, Game Over.")
    
else:
    print("You have fell into a hole, Game Over.")
