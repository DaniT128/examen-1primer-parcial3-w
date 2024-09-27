# examen-1primer-parcial3-w
examen primer parcial 3-w

# Función para calcular el factorial
def factorial(n): #para definir el valor
    if n == 0 or n == 1: #ingresr un solo valor 
        return 1 #finalzacion del codigo
    else: #para finalizar el programa
        return n * factorial(n - 1) #para verificar el cdigo del programa 

# Solicitar un número entero positivo al usuario
numero = int(input("Introduce un número entero positivo: ")) #pide el introducir un numero positivo 

# Verificar que el número sea positivo
if numero < 0: #para verificar un valor menor que 
    print("Por favor, introduce un número entero positivo.") #pidel el ingresar un numero positivo
else: #para finalizar el programa 
    # Calcular el factorial
    resultado = factorial(numero) #pide el resultado del valor que se ingreso 
    print(f"El factorial de {numero} es: {resultado}") #el valor que se ingreso fue 


![image](https://github.com/user-attachments/assets/592e1e7b-c05d-444f-ae5f-987a504ac6df)


![image](https://github.com/user-attachments/assets/726a6024-234d-4990-94ff-f752baff05ec)
