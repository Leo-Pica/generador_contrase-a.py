import random  # Importamos el módulo random para generar valores aleatorios.
import string  # Importamos el módulo string para acceder a conjuntos de caracteres predefinidos.

def generar_contraseña(longitud=8):
    # Creamos una cadena de caracteres que incluye todas las letras (mayúsculas y minúsculas) y dígitos.
    caracteres = string.ascii_letters + string.digits
    
    # Generamos una contraseña seleccionando aleatoriamente 'longitud' caracteres de la cadena 'caracteres'
    contraseña = ''.join(random.choice(caracteres) for i in range(longitud))
    
    # Retorna la contraseña generada.
    return contraseña
#Para probar el programa generamos una función para saludar y devolvemos la contraseña generada.
def saludar_y_generar_contraseña(nombre_usuario):
    # Saludamos al usuario
    print(f"¡Hola, {nombre_usuario}!")
    
    # Llamamos a la función creada "generar_contraseña"
    contraseña = generar_contraseña()
    
    # Muestra la contraseña generada
    print(f"Tu contraseña generada es: {contraseña}")

# Ejemplo de uso
nombre_usuario = input("Por favor, ingresa tu nombre: ")
saludar_y_generar_contraseña(nombre_usuario)
