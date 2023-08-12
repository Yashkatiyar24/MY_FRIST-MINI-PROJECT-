# Basic-Game
gamelist=[1,2,3]
def display game():
    print("Here is current list:")
    print(game list)
display game()
def position choice():
    
  choice='wrong'
    
  while choice not in ['1', '2', '3']:
        
    
  choice=input("Enter a number between range(0-3): ")
    
  if choice not in ['1', '2', '3']:
       print("This is invalid input")
        
  return int(choice)  
  position choice()
    def replacement choice(game list,position):
    userplacement=input("Enter a string you want to replace: ")
    
   gamelist[position]=userplacement
    return game list
 replacement choice(game list,1)
 def game choice():
    
    
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

while game on:
    
  display game()
    
  position=positionchoice
    
  gamelist=replacementchoice(game list,1)
    
  display game()
    
  game=gameonchoice()
