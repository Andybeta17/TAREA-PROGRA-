# calculadora.py

n1 = input("Ingresa el primer número: ")
n2 = input("Ingresa el segundo número: ")

# --- INICIO DEBUG ---
print(f"DEBUG n1: {n1} tipo: {type(n1)}")
print(f"DEBUG n2: {n2} tipo: {type(n2)}")
# --- FIN DEBUG ---

# BUG: Al ser strings, el signo + une los textos en lugar de sumar los números.
# Si ingresas 5 y 10, el resultado será 510 en lugar de 15.
resultado = n1 + n2

print(f"La suma es: {resultado}")# TAREA-PROGRA-
