# Hamim-s-TBG-Action-Menu

#TBG Action Menu - Hamim Sazzad
#May 18, 2022

from colorama import Fore

print('Welcome to the 5th cloud')
print('A text based game by Hamim Sazzad')
print('Contacts - hamim.sazzad@rbe.sk.ca')
print('*\n*')

items= ['Charms','Steroids','Book Of Wisdom','Bottle O Enchanting']
levels= ['1st Gorilla Fight','2nd Monkey Fight','3rd Snake Fight','4th Bear Fight']



print(Fore.GREEN + 'Which item will you pick to help you wit this cloud?')
for equip in items:
    print('-' + equip)
backpack = input()



print('Which level do you wish to use this item on?')
for choice in levels:
    print('-' + choice)
clouds = input()

    


if backpack == 'Charms' and clouds == '1st Gorilla Fight' :
    print(Fore.YELLOW + 'The gorilla acknowledges your charm and lets you pass! You won!')
elif backpack == 'Charms' and clouds == '2nd Monkey Fight' :
    print(Fore.RED + 'The monkey stole your charms! You lost!')
elif backpack == 'Charms' and clouds == '3rd Snake Fight' :
    print(Fore.YELLOW + 'The charms helped you out with the poision from the snake! You won!')
elif backpack == 'Charms' and clouds == '4th Bear Fight' :
    print(Fore.RED + 'The bear ate your charms! Then you! You lost!')




elif backpack == 'Steroids' and clouds == '1st Gorilla Fight' :
    print(Fore.YELLOW + 'You overpower the gorilla! You won!')
elif backpack == 'Steroids' and clouds == '2nd Monkey Fight' :
    print(Fore.RED + 'You have stength, the monkey has brains. You lose!')
elif backpack == 'Steroids' and clouds == '3rd Snake Fight' :
    print(Fore.RED + 'The snake poisons you! You lose!')    
elif backpack == 'Steroids' and clouds == '4th Bear Fight' :
    print(Fore.YELLOW + 'You overpower the bear! You won!')




elif backpack == 'Book Of Wisdom' and clouds == '1st Gorilla Fight' :
    print(Fore.YELLOW + 'You outsmart your enemy! You won!')
elif backpack == 'Book Of Wisdom' and clouds == '2nd Monkey Fight' :
    print(Fore.YELLOW + 'You outsmart your enemy! You won!')    
elif backpack == 'Book Of Wisdom' and clouds == '3rd Snake Fight' :
    print(Fore.YELLOW + 'You outsmart your enemy! You won!')    
elif backpack == 'Book Of Wisdom' and clouds == '4th Bear Fight' :
    print(Fore.YELLOW + 'You outsmart your enemy! You won!')
         
        

elif backpack == 'Bottle O Enchanting' and clouds == '1st Gorilla Fight' :
    print(Fore.RED + 'You heal yourself with the item! But not enough damage! You lose!')
elif backpack == 'Bottle O Enchanting' and clouds == '2nd Monkey Fight' :
    print(Fore.YELLOW + 'You and the monkey have similar strength! But you heal! You won!')    
elif backpack == 'Bottle O Enchanting' and clouds == '3rd Snake Fight' :
    print(Fore.RED + 'The snake has poison the forever damages you! You can not heal fast enough! You lose!')    
elif backpack == 'Bottle O Enchanting' and clouds == '4th Bear Fight' :
    print(Fore.RED + 'The bear overpowers you! You can not heal fast enough! You lose!')
    
else:
    print('Please pick the options listed!')
