#25% Denis 25% Irving 25% Colin 25% Jack
#All the lists for the code
weapons = ["Fire Bow", "Ice Sword", "Spear"]
inventory = ["Bandage", "Healing Potion", "Magic Orb"]
chest_items =["Healing Potion", "Empty Water Bottle", "Legendary Sword", "Backpack"]
destinations=["Dragon Lair", "Elvish Hills"]
list_of_num = ["1","2","3","4","5","6","7"]
list_choice = [1,2,3,4,5,6,7,8,9,10]
lair_choice = ['Attack The Dragon', 'Free The Woman']
hills_choice = ['Stay', 'Go']
escape_choice = ['Yes', 'No']

#Import text image
from art import tprint 
#import for the random dice 
import random
import new_journey


class DemonSlayer():
 #A simple attempt to represent a car."""
 def __init__(self, slayer, weapon, age):
  #Initialize attributes to describe a car."""
  self.slayer = slayer
  self.weapon = weapon
  self.age = age
  self.health_reading = 1000
   
 def get_descriptive_name(self):
  #Return a neatly formatted descriptive class."""
  long_class = str(self.age) + ' Years old ' + self.slayer + ' with a ' + self.weapon
  return long_class.title()
   
 def read_health(self):
  """Print a statement showing the class's health."""
  print("This class has " + str(self.health_reading) + " health points on it.")

 def update_health(self, mileage):
  """Set the health reading to the given value."""
  self.health_reading = mileage

 def increment_health(self, points):
  """Add the given amount to the health reading."""
  self.health_reading += points

 def decrease_health(self,points):
   self.health_reading -= points


#start of the code
tprint("        Welcome To")
tprint("Monster Hunter!")
name = input("What is your name? ").title()
print ("Welcome to the game", name,"!" )
print ("\nWould you like to start the game?")

#beginning of the action
yes_no = input("").title()
if yes_no == "Yes":
  print ("Let's start the game, you are stumbling across a Fire Dragon, you notice weapons laying around, which one do you choose to fight? ", weapons)
  weapon_choice = input("").title()
  if weapon_choice == "Fire Bow":
    print ("You managed to hurt the dragon but not kill him, the dragon got scared and flew away.")
    if weapon_choice =="Fire Bow":
      print("It was a tough fight, and you need to heal yourself, look at your inventory (yes/no)")
    inventory_look = input("").title()
    if inventory_look == "Yes":
      print(inventory) 
      potion = input("").title()
      if potion == "Bandage":
       print ("You have healed yourself 75%.")
       print ("However, you have lost the will to fight, see you stranger.")
      elif potion == "Healing Potion":
        print("Congratuations, you are fully healed!")
      elif potion == "Magic Orb": 
        print("You have summoned Eric, the Magic Wizard to help you! He has taken you to his house to heal you!")
        print("The wizard has asked you where you are going next.", destinations)
        destination_choice=input("").title()
        if destination_choice == "Dragon Lair":
          print("The wizard gives you an electric lance to help fight against the dragon!")
          print("You make your way to the dragon's lair and find him sleeping in front of a cage with a woman trapped in it. Do you attack the dragon while it is sleeping or try to free the woman in the cage?" + str(lair_choice))
          dragon_lair_choice=input("").title()
          if dragon_lair_choice == "Attack The Dragon":
            print("The wizard's electric lance was faulty and the dragon killed you.")
          else:
            print("The woman screamed and woke the dragon. It killed you.")
            tprint("Game")
          tprint("Over")
        else:
          print('You travelled to the elvish hills and met many kind elves. One elf you became fond of and she asks you to stay. Do you?')
          print(hills_choice)
          love_choice=input("").title()
          if love_choice == "Stay":
            print('You live happily for the rest of your life with the elf. Your adventure is over.')
          else:
            print('n\The elves are offended that you chose to leave and take you captive. Your cellmate wants to escape and offers you the chance to come with him. Do you?')
            print(escape_choice)
            escape=input("").title()
            if escape == "Yes":
              print('The elves caught you in the midst of escape and heightened their security. You live out the rest of your days in the elvish prison.')
            else:
              print('Eventually, Eric the Wizard frees you from captivity and you return to his home with him.')
              print('n\The wizard now gives you his electric lance to take on the dragon in his lair.')
              print("n\You make your way to the dragon's lair and find him sleeping in front of a cage with a woman trapped in it. Do you attack the dragon while it is sleeping or try to free the woman in the cage?" + str(lair_choice))
          dragon_lair_choice=input("").title()
          if dragon_lair_choice == "Attack The Dragon":
            print("The wizard's electric lance was faulty and the dragon killed you.")
            tprint("Game")
            tprint("Over")
          else:
            print("The woman turns out to be the elf who fell in love with you. You free her and she helps you slay the dragon. You now have a travelling companion!")
            elf_travel=input("Where would you like to travel with your companion? (Dwarven Caves/Western Cursed Lands.").title()
            if elf_travel=="Dwarven Caves":
              print("You found once you arrived to the Dwarven Caves, that there was no dwarves save one, who said they had been taken to The Western Cursed Lands by a demon. You have gained another travelling companion.")
              throw_choice=input("You get to the Western Cursed Lands and are about to drink out of a river but your Dwarven friend gets attacked by a jackal and you need to help him. Throw Lance/Distraction").title()
              if throw_choice == "Distraction":
                print("Good Job! The Jackal turned his attention to you and mauled you.")
                tprint("Try Again")
              else:
                print("You threw your electric lance at the jackal and electrocuted it to death.")
                print("n\For helping him, the Dwarf has given you his battle ax to compensate for the lance.")
                ohio=input("You travel deeper into Cursed Lands and stumbled on the capital city of the lands, Ohio. Do you go inside? Yes/No").title()
                if ohio == 'Yes':
                  print("You, the elf, and the dwarf sneak into the city and find the dwarf's kin imprisoned. As you try to free them, a mystrious figure captures you and your companion and brings you to the cursed king.")
                  print("When you see you the king and recognize his moustache. It is Eric the wizard!")
                  combat=input("You as for freedom, but Eric challenges you to single combat to win it. Do you accept? Yes/No").title()
                  if combat == 'Yes':
                    print("You accept and win you and all of the companions freedom, as well as the dwarves. You live the rest of your life helping the dwarves start again.")
                  else:
                    print("Eric laughs and says fine, live in a cell for the rest of your life. And you do.")
                else:
                  print("Your Dwarven friend got angry with you for not wanting to help his people and kills your and your elvish love.")
            else:
              print("You travelled to the Western Cursed Lands but you drank out of a river of poison by accident and died.")
                  
    else:
      print("You bled out and died.")
  elif weapon_choice == "Ice Sword":
    print ("Fire Dragon melted your sword, he attacked you but you managed to dodge his attack, you get second chance, choose another weapon.")
    new_weapon = input("").title()
    if new_weapon == "Fire Bow":
      print("You managed to escape the dragon but you have been hurt and lost all of your inventory.")
      print ("After walking for an hour, you saw a chest on the hill, you decide whether you want to open it.(yes/no)")
      chest = input().title()
      if chest == "Yes":
        print("The chest turns out to be able to talk, and it offers you a one item from the chest.")
        print (chest_items)
        item_1 = input("").title()
        if item_1 == chest_items[0]:
          print ("You have chosen a Healing Potion, however, a talking chest said you can only use it once you are on the verge of death.\n Your health is at 25% and you are now too weak to move. This is the end of your journey.")
        elif item_1 == "Empty Water Bottle":
          print ("You have chosen an Empty Water Bottle, what are you going to do with that? ")
          print("You bled out and died.")
        elif item_1 == "Legendary Sword":
          print ("You have chosen Legendary Sword, it teleports you to the kingdom of camelot")
          print("The king welcomes you to his castle. He tells you that he has a quest for you and will reward you handsomely.") 
          kings_quest_choice=input("Do you want to go on the quest? Yes/No ").title()
          if kings_quest_choice=="No":
            print ("The king stares at you blankly. You are thrown in the dungeon and spend your days eating bread and drinking sewer water")
          else: 
            print("Great choice, traveler. The princess has been abducted! Please retrieve my daughter from the villain named Browser.") 
            print("You have arrived in purgatory, land of the dead. You wander a while to find Browsers evil castle. Inside is the princess, guarded by demons.")
            enter_demon_castle=input("Do you enter? Yes/No")
            if enter_demon_castle=="No": 
              print("You are a coward. A flying demon snatches you and feeds you to its children.")
            else:
              print("The demons spot you! You see weapons lying on the ground from defeated warriors. Which weapon do you choose?")
              weapon_demon_choose=input("taser, katana, plunger")
              
        elif item_1 == "Backpack":
            print("You have chosen Backpack, inside is a special 10 sided die.")
            print ("The chest says you must roll, if you get 0-5, you are doomed for all eternity. ")
            print("If you get 6-10, you have become the Dragon Slayer")
            rand_idx = random.randint(0, len(list_choice)-1)
            random_num = list_choice[rand_idx]
            print("Random selected dice side is : " + str(random_num))
            if random_num <= 5:
               print("You are unlucky, your adventure is done. ")
            else:
               print("Congratulations, you have become a Dragon Slayer.However, your journey has just begun.")
               my_used_class = DemonSlayer('\nNobody', 'Fire Bow', 25)
               print("Your old class has changed from: ")
               print(my_used_class.get_descriptive_name())


               my_new_class = DemonSlayer('\nWarrior', 'Magic Sword', 25)
               print("\nTo")
               print(my_new_class.get_descriptive_name())
               my_new_class.read_health()
               print("You are about to start a brand new journey from the bottom all the way to the top, it will be challenging, but unfortunately you have no choice.")
               print("Every new enemy will deplete your health points, you are starting with 1000.")
               #filename = "new_journey.py"
               #with open(filename) as file_object:
               #new_journey.Text()
                 
      elif chest == "No":
        print("As you continue your path you come across a 10 foot tall Cyclops, he pushes you off the cliff.")
        tprint("Game")
        tprint("Over")
    else:
      print("Your weapon choice was once again incorrect, see ya in another life!")
  else:
    print("The Dragon put you on fire.")
    tprint("Game")
    tprint("Over")
else:
  print ("That's too bad, see you soon!")

