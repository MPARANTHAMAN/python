# python
Pizza ordering program using puthon
print("welcome to pizza shop")
print("press 1 for pizza")
print("press 2 for soft drink")
print("press 3 for roll")
choice=int(raw_input("my choice= "))
if(choice==1):
  print("you are selected for pizza")
  print("press 1 for veg-pizza")
  print("press 2 for non-vegpizza")
  choicepizza=int(raw_input("my choice is= "))
  if(choicepizza==1):
     print("you are selected for veg-pizza")
     print("press 1 for cheese")
     print("press 2 for capsicum")
     pizch=int(raw_input("my choice is= "))
     
     if(pizch==1):
       print("you are selected for cheese pizza =120")
     elif(pizch==2):
         print("you are selected for capsicum pizza =140")            
  elif(choicepizza==2):
     print("you are selected for non- vegpizza")
     print("press 1 for chicken")
     print("press 2 for meat")
     pizchi=int(raw_input("my choice is= "))
     if(pizchi==1):
       print("you are selected for chicken pizza =120")
     elif(pizchi==2):
        print("you are selected for meatpizza =140") 
if(choice==2):
  print("you are selected for softdrink")
  print("press 1 for pepsi")
  print("press 2 for limca")
  juice=int(raw_input("my choice is= "))
  if(juice==1):
     print("you are selected for pepsi")
     print("press 1 for normal")
     print("press 2 for chill")
     pepsi=int(raw_input("my choice is= "))
     
     if(pepsi==1):
       print("you are selected for normal =50")
     elif(pepsi==2):
         print("you are selected for chill =40")            
  elif(juice==2):
     print("you are selected for limca")
     print("press 1 for chill")
     print("press 2 for normal")
     limca=int(raw_input("my choice is= "))
     if(limca==1):
       print("you are selected for chill=10")
     elif(limca==2):
        print("you are selected for normal =100")
if(choice==3):
  print("you are selected for roll")
  print("press 1 for veg-roll")
  print("press 2 for non-vegpizza")
  roll=int(raw_input("my choice is= "))
  if(roll==1):
     print("you are selected for veg-roll=15")
  elif(roll==2):
         print("you are selected for non-veg roll =14")
