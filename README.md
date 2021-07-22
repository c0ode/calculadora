#calculadora
numero = int(input("""
****************** 
*Menu de opciones*
****************** 

1. Suma
2. Resta
3. Multiplicacion
4. Division con decimas
5. Division entera
6. Exponente
7. Modulo o resto

Introduce la opcion deseada: """))

if numero == 1:
    print("Elegiste suma.")
    numero = int(input("Ingresa el primer valor: "))
    numero += int(input("Ingresa el segundo valor: "))
    print("El resultado de tu suma es: ", numero)
elif numero == 2:
    print("Elegiste resta.")
    numero = int(input("Ingresa el primer valor: "))
    numero -= int(input("Ingresa el segundo valor: "))
    print("El resultado de tu resta es: ", numero)
elif numero == 3:
    print("Elegiste multiplicacion.")
    numero = int(input("Ingresa el primer valor: "))
    numero *= int(input("Ingresa el segundo valor: "))
    print("El resultado de tu multiplicacion es: ", numero)
elif numero == 4:
    print("Elegiste division con decimas.")
    numero = float(input("Ingresa el primer valor: "))
    numero /= float(input("Ingresa el segundo valor: "))
    print("El resultado de tu division con decimas es: ", round(numero, 2))
elif numero == 5:
    print("Elegiste division entera.")
    numero = int(input("Ingresa el primer valor: "))
    numero //= int(input("Ingresa el segundo valor: "))
    print("El resultado de tu division entera es: ", numero)
elif numero == 6:
    print("Elegiste exponente.")
    numero = int(input("Ingresa el primer valor: "))
    numero **= int(input("Ingresa el segundo valor: "))
    print("El resultado de tu exponente es: ", numero)
elif numero == 7:
    print("Elegiste modulo o resto.")
    numero = int(input("Ingresa el primer valor: "))
    numero %= int(input("Ingresa el segundo valor: "))
    print("El resultado de tu modulo o exponente es: ", numero)
else:
    print("Opcion no valida.")



print("Buen dia!")
