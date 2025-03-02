#fortune cookie project
import random
lucky_number = random.randint(1,100)
#importing a random module
fortune_number = random.randint(1,3)
#fortune_text is a variable
fortune_text = ''

if fortune_number == 1:
  fortune_text = 'You will have a great day!'
if fortune_number == 2:
  fortune_text = 'Today will be tough...but worth it.'
if fortune_number == 3:
  fortune_text= 'You will get married this year!'
  
  




print(f"{fortune_text}Your lucky number is: {lucky_number}")
# add f to the beginning of the string to add variables into the string and use curly brackets to add the variables
