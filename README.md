# Basic-Game
game_list=[1,2,3]
def display game():
    print("Here is current list:")
    print(game_list)
display game()
def position_choice():
    
  choice='wrong'
    
  while choice not in ['1', '2', '3']:
        
    
  choice=input("Enter a number between range(0-3): ")
    
  if choice not in ['1', '2', '3']:
       print("This is invalid input")
        
  return int(choice)  
  position_choice()
    def replacement choice(game_list,position):
    userplacement=input("Enter a string you want to replace: ")
    
   game_list[position]=userplacement
    return game_list
 replacement_choice(game_list,1)
 def game_choice():
    
    
  choice='wrong'
    
  while choice not in ['yes',' no']:
        
    
  choice=input("Do you want to keep playing? (yes or no): ")
    
  if choice not in ['yes',' no']:
       print("sorry! This is invalid input")
        
  if choice=='yes':
      return True
  else:
    return False
     game choice()
      ganme_on=True
game_list=[1,2,3,4,5]

while game_on:
    
  display game()
    
  position=position_choice
    
  game_list=replacement_choice(game_list,1)
    
  display game()
    
  game=gameon_choice()
