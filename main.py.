
# Programa principal: main.py

import Operaciones

print("========== CALCULADORA ==========")

# Solicitar dos numeros al usuario
num1 = float(input("Ingrese el primer numero: "))
num2 = float(input("Ingrese el segundo numero: "))

# Mostrar las operaciones disponibles
print("\nSeleccione la operacion:")
print("1. Sumar")
print("2. Restar")
print("3. Multiplicar")
print("4. Dividir")

opcion = input("Ingrese una opcion: ")

# Realizar la operacion seleccionada
if opcion == "1":
    resultado = Operaciones.sumar(num1, num2)
    print("El resultado de la suma es:", resultado)

elif opcion == "2":
    resultado = Operaciones.restar(num1, num2)
    print("El resultado de la resta es:", resultado)

elif opcion == "3":
    resultado = Operaciones.multiplicar(num1, num2)
    print("El resultado de la multiplicacion es:", resultado)

elif opcion == "4":
    resultado = Operaciones.dividir(num1, num2)
    print("El resultado de la division es:", resultado)

else:
    print("Opcion invalida. Intente nuevamente.")
