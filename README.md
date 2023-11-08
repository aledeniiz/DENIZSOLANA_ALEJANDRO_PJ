# DENIZSOLANA_ALEJANDRO_PJ
import random
l = 0
num = random.randrange(100)
while (True):
    intento = int(input("Dime un numero del 0 al 99: "))
    l = l + 1
    if num != intento :
        print("El numero que has introducido es distinto al aleatorio")
        if num < intento :
                print ("El numero que has elegido es mayor que el que quieres adivinar.")
        else:
                print ("El numero que has elegido es menor que el que quieres adivinar.")    
    elif num == intento:
        print("Has acertado el número: ", num)
        break

print ("Has necesitado ",l, " intentos.")
