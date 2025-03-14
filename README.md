# Atividade-infinity

import random

def lancar_dados():
    dado1 = random.randint(1, 6)  # Lança o primeiro dado
    dado2 = random.randint(1, 6)  # Lança o segundo dado
    total = dado1 + dado2  # Soma os resultados
    return total

# Testando a função
resultado = lancar_dados()
print(f"O resultado do lançamento dos dados é: {resultado}")
