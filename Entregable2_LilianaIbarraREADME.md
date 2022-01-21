# Ejercicio 2


Usuario = "Laura Lopez"
Num_Cuenta = "1976937658932"
Vigencia = "19 / 12"
Fecha_de_vencimiento = "11 / 23"

def mi_funcion(**kwargs):
Usuario = kwargs["Laura Lopez"]
Num_Cuenta = kwargs["1976937658932"]
Vigencia = kwargs["19 / 12"]
Fecha_de_vencimiento = kwargs["11 / 23"]
    return mi_funcion
    
Tarjeta_Bancaria = mi_funcion(Usuario)
print("Los datos son:", Tarjeta_Bancaria)
