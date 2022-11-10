# conversor-de-monedas_kazel
import os
os.system("cls")  

USD = 1
ARS = 290
COP = 4600
MXN = 20

print('"Bienvenido al conversor de monedas internacionales mas chingon"')
print("Elige una de las siguientes opciones de conversion")
print("1-Dolares Estadounidenses a Pesos Argentinos")
print("2-Pesos Argentinos a Dolares Estadounidenses")
print("3-Dolares Estadounidenses a Pesos Colombianos")
print("4-Pesos Colombianos a Dolares Estadounidenses")
print("5-Dolares Estadounidenses a Pesos Mexicanos")
print("6-Pesos Mexicanos a Dolares Estadounidenses")


opcion = input("¿cual es su opcion?")
opcion = int(opcion)
if opcion == 1:
    dolares = int(input("¿cuantos Dolares tienes?"))
    pesos = dolares * ARS
    print(f"Tienes {pesos} pesos Argentinos")
elif opcion == 2:
    pesos = int(input("¿cuantos pesos Argentinos tienes?"))
    dolares = pesos / ARS
    print(f"Tienes {dolares} Dolares") 

elif opcion == 3:
    dolares = int(input("¿cuantos Dolares tienes?"))
    pesos = dolares * COP
    print(f"Tienes {pesos} pesos Colombianos")
elif opcion == 4:
    pesos = int(input("¿cuantos pesos Colombianos tienes?"))
    dolares = pesos / COP
    print(f"Tienes {dolares} Dolares") 

elif opcion == 5:
    dolares = int(input("¿cuantos Dolares tienes?"))
    pesos = dolares * MXN
    print(f"Tienes {pesos} pesos Mexicanos")
elif opcion == 6:
    pesos = int(input("¿cuantos pesos Mexicanos tienes?"))
    dolares = pesos / MXN
    print(f"Tienes {dolares} Dolares") 

else:
    print("¡Escribe una opcion correcta!")

