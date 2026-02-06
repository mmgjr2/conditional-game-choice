# conditional-game-choice
python program that shows simple game choice (example)
def game_choice():
    print("Choose to save a talking robotic teddy or a human!")
    choice = input("Choose a character: teddy or bob? ").strip().lower()

     if choice == "teddy":
       agility = input("do you have 10 points in agility?(yes/no)").strip().lower()
         if agility =="yes":
            print("you lept across a building to whack a man with your shoe saving teddy. congrats teddy is thankful.")
        else:
            print("you failed to jump the building and fell from a great height")
      elif choice == "bob":
          strength = input("do you have a value of 8 strength pionts(yes/no)").strip().lower()
            if strength == "yes":
              print("you hold up closed a door that comtains 50 henchmen chasing bod so he could escape.never to be seen again")
                else:
                    print("you fail to hold the door long enough for bob to escape he is caught and tied to a chair. you failed to save bob")

      else:
         print:("choice wasnt made.please choose a selected option.")

game_choice()
          
      
