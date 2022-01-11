# Introduccion-a-Python-Bedu
Entregables

Nombre_de_la_tarjeta = input("Desea conocer su adeudo?")

Uno = input("La tasa de interes es: ")
operando1 = float(Uno)
producto = operando1 / 12
print("La tasa de interes menusal es: ")
print(producto)

Dos = input("A cuanto asceinde su deuda? ")
Tres = input("Monto de pago ")
operando2 = float(Dos)
operando3 = float(Tres)
producto2 = (operando2 - operando3) * (1 + producto)
print("La deuda recalculada es de: ")
print(producto2)

Cuatro = input("Cargos ")
operando5 = float(Cuatro)
producto3 = producto2 + operando5
print("Su nueva deuda es de: ")
print(producto3)
