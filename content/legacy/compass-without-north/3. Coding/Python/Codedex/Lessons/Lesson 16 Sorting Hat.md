Code written below


```
# Write code below 💖

#Houses and their variables
Gryffindor = int(0)
Ravenclaw = int(0)
Hufflepuff = int(0)
Slytherin = int(0)


print('Please answer the following questions, pick the option which best fits. \nex. 1 for option 1')

#list of questions and their variables
q1 = int(input('Do you like Dawn or Dusk? \n1) Dawn \n2) Dusk'))
q2 = int(input('When I\'m dead, I want people to remember me as: \n1) The Good \n2) The Great \n3) The Wise \n4) The Bold'))
q3 = int(input('which kind of instrument most pleases your ear? \n1) The Violin \n2) The trumpet \n3) The piano \n4) The drum'))

#q1 response list
if q1 == 1:
  Gryffindor +=1 
  Ravenclaw +=1
elif q1 == 2:
  Hufflepuff +=1
  Slytherin +=1
else:
  print('Wrong Input')


#q2 response list
if q2 == 1:
  Hufflepuff +=2
elif q2 == 2:
  Slytherin +=2
elif q2 == 3:
  Ravenclaw +=2
elif q2 == 4:
  Gryffindor +=2
else:
  print('Wrong Input')


#q3 Response list

if q3 == 1:
  Slytherin +=4
elif q3 == 2:
  Hufflepuff +=4
elif q3 == 3:
  Ravenclaw +=4
elif q3 == 4:
  Gryffindor +=4
else:
  print('Wrong input')


#to print the house with most points
if Gryffindor > Ravenclaw and Gryffindor > Hufflepuff and Gryffindor > Slytherin:
  print('You belong in Gryffindor!', Gryffindor)
elif Ravenclaw > Gryffindor and Ravenclaw > Hufflepuff and Ravenclaw > Slytherin:
  print('You belong in Ravenclaw!', Ravenclaw)
elif Hufflepuff > Gryffindor and Hufflepuff > Ravenclaw and Hufflepuff > Slytherin:
  print('You belong in Hufflepuff!', Hufflepuff)
else:
  print('You belong in Slytherin', slytherin)
```




