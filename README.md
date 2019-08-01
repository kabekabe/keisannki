# keisannki
課題
cube=27
for guess in range( abs(cube) + 1)  :
    if  guess**3  >=  abs(cube) :
        break
if  guess**3 != abs(cube) :
    print(cube, 'is not a perfect cube (完全立方)')
else : 
    if cube <0 :
        guess = -guess
    print('Cube root of ' +str(cube) + ' is ' + str(guess) )
