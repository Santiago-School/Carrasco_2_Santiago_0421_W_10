# Carrasco_2_Santiago_0421_W_10

print(" ")

print("Santiago Carrasco 0421 3°W")

print(" ")

# solicitar un numero entero al usuario

n = int(input("ingrese un numero entero para calcular su factorial: "))



# inicializar el factorial en 1

factorial = 1



# comprobar si n es negativo

if n < 0:

    print("el factorial no esta definido para numeros negativos")

else:

    # calcular el factorial usando un bucle
    for i in range(1, n + 1):
        factorial = factorial * i  # multiplicar el factorial por i

    # imprimir el resultado
    print("el factorial de", n, "es", factorial)

![image](https://github.com/user-attachments/assets/078c74ed-765e-496e-b590-18622700ae1f)

