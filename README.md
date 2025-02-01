# ejercicio_3

### main.py

```python
def calcular_letra_dni(dni):
    letras = "TRWAGMYFPDXBNJZSQVHLCKE"
    return letras[dni % 23]

def calcular_pi(n=200):
    pi = 0
    for k in range(1, n + 1):
        pi += ((-1) ** (k + 1)) / (2 * k - 1)
    return 4 * pi

if __name__ == "__main__":
    # Parte 1: Cálculo de la letra del DNI
    dni = int(input("Introduce el número de DNI: "))
    letra = calcular_letra_dni(dni)
    print(f"La letra del DNI es: {letra}")

    # Parte 2: Cálculo de π
    pi_valor = calcular_pi()
    print(f"Valor aproximado de π: {pi_valor:.6f}")
```

### Rama 1: `calculo_dni`

```python
def calcular_letra_dni(dni):
    letras = "TRWAGMYFPDXBNJZSQVHLCKE"
    return letras[dni % 23]

if __name__ == "__main__":
    # Parte 1: Cálculo de la letra del DNI
    dni = int(input("Introduce el número de DNI: "))
    letra = calcular_letra_dni(dni)
    print(f"La letra del DNI es: {letra}")
```

### Rama 2: `calculo_pi`

```python
def calcular_pi(n=200):
    pi = 0
    for k in range(1, n + 1):
        pi += ((-1) ** (k + 1)) / (2 * k - 1)
    return 4 * pi

if __name__ == "__main__":
    # Parte 2: Cálculo de π
    pi_valor = calcular_pi()
    print(f"Valor aproximado de π: {pi_valor:.6f}")
```

### Rama 3: `funciones_generales`

```python
def calcular_letra_dni(dni):
    letras = "TRWAGMYFPDXBNJZSQVHLCKE"
    return letras[dni % 23]

def calcular_pi(n=200):
    pi = 0
    for k in range(1, n + 1):
        pi += ((-1) ** (k + 1)) / (2 * k - 1)
    return 4 * pi

if __name__ == "__main__":
    # Parte 1: Cálculo de la letra del DNI
    dni = int(input("Introduce el número de DNI: "))
    letra = calcular_letra_dni(dni)
    print(f"La letra del DNI es: {letra}")

    # Parte 2: Cálculo de π
    pi_valor = calcular_pi()
    print(f"Valor aproximado de π: {pi_valor:.6f}")
```

