# integrantes
Matias Coronel
Genesis Valverde

# Metodos comunes de str

## Cambios de mayusculas/minusculas

print("nombre.lower")       # Genesis
print("nombre.capitalize")  # Genesis
print("nombre.title)       # Genesis (cada palabra en mayúscula)
print(nombre.swapcase())    # gENESIS

## Longitud y busqueda

print(len(nombre))                   # 7 (cantidad de caracteres)
print(nombre.startswith("Gen"))       # True
print(nombre.endswith("esis"))         # True
print(nombre.find("i"))              # 1 (posición donde aparece "i")

## Reemplazar y dividir

print(nombre.replace("Matias", "Genesis"))        # Genesis
print(nombre.split("i"))                      # ['Genes', 's'] (divide por "i")

## Eliminar espacios

texto = "   Hola Matias y Genesis  "
print(texto.strip())   # "Hola Genesis"
print(texto.lstrip())  # "Hola Matias" (quita izquierda)
print(texto.rstrip())  # "Hola Matias y Genesis" (quita derecha)

## Unir cadenas

letras = ["G", "e", "n", "e", "s", "i", "s"]
print("".join(letras))              # Genesis
print("-".join(letras))             # G-E-N-E-S-I-S

letras = ["M", "a", "t", "i", "a", "s"]
print("".join(letras))              # Matias
print("-".join(letras))             # M-a-t-i-a-s

## Validaciones

print(nombre.isalpha())         # True (solo letras)
print("123".isdigit())          # True (solo números)
print("genesis321".isalnum())     # True (letras y números)
print("   ".isspace())          # True (solo espacios)
# Metodos comunes de str

## Cambios de mayusculas/minusculas

print(nombre.lower())       # Genesis
print(nombre.capitalize())  # Genesis
print(nombre.title())       # Genesis (cada palabra en mayúscula)
print(nombre.swapcase())    # gENESIS

## Longitud y busqueda

print(len(nombre))                   # 7 (cantidad de caracteres)
print(nombre.startswith("Gen"))       # True
print(nombre.endswith("esis"))         # True
print(nombre.find("i"))              # 1 (posición donde aparece "i")

## Reemplazar y dividir

print(nombre.replace("Matias", "Genesis"))        # Genesis
print(nombre.split("i"))                      # ['Genes', 's'] (divide por "i")

## Eliminar espacios

texto = "   Hola Matias_Genesis  "
print(texto.strip())   # "Hola Genesis"
print(texto.lstrip())  # "Hola Matias" (quita izquierda)
print(texto.rstrip())  # "Hola Matias_Genesis" (quita derecha)

## Unir cadenas

letras = ["G", "e", "n", "e", "s", "i", "s"]
print("".join(letras))              # Genesis
print("-".join(letras))             # G-E-N-E-S-I-S

letras = ["M", "a", "t", "i", "a", "s"]
print("".join(letras))              # Matias
print("-".join(letras))             # M-a-t-i-a-s

## Validaciones

print(nombre.isalpha())         # True (solo letras)
print("123".isdigit())          # True (solo números)
print("genesis321".isalnum())     # True (letras y números)
print("   ".isspace())          # True (solo espacios) 