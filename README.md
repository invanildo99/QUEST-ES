# QUEST-ES
QUESTÕES DE RACIOCINIO LOGICO
QUESTÃO 1:
# Número previamente definido
numero = 13  # Você pode alterar este valor para o número que deseja verificar

# Função para gerar a sequência de Fibonacci até o número fornecido
def fibonacci_sequence(n):
    sequence = [0, 1]
    while sequence[-1] < n:
        next_value = sequence[-1] + sequence[-2]
        sequence.append(next_value)
    return sequence

# Função para verificar se o número fornecido pertence à sequência de Fibonacci
def check_fibonacci(n):
    sequence = fibonacci_sequence(n)
    if n in sequence:
        return f"O número {n} pertence à sequência de Fibonacci."
    else:
        return f"O número {n} não pertence à sequência de Fibonacci."

# Executando o programa e exibindo o resultado
resultado = check_fibonacci(numero)
print(resultado)


QUESTÃO 2:
# Programa para verificar a existência da letra 'a' (maiúscula ou minúscula) em uma string

# Definindo a string
string_exemplo = "Amazônia, a maior floresta tropical do mundo"  # A string pode ser modificada

# Função para verificar a existência da letra 'a' e contar as ocorrências
def verificar_letra_a(string):
    # Contar a ocorrência de 'a' e 'A'
    count_a = string.count('a') + string.count('A')
    
    # Verificar se a letra 'a' ou 'A' existe e informar a quantidade
    if count_a > 0:
        return f"A letra 'a' (maiúscula ou minúscula) aparece {count_a} vezes na string."
    else:
        return "A letra 'a' (maiúscula ou minúscula) não aparece na string."

# Executando o programa e exibindo o resultado
resultado = verificar_letra_a(string_exemplo)
print(resultado)


QUESTÃO 3:

O valor da variável SOMA é 65

QUESTÃO 4:
a.9 (vai somando numero anterior +2)
b.128 (vai dobrando o numero)
c.49 (vai elevando a 2 potencia os numero em sequencia)
d. 100 (Vai elevando o quadrado dos números pares exemplo: 2^2 = 4; 4^2 = 16 e assim por diante)
e. 13 (Segue a sequencia de Fibonacci, cada numero(a partir do terceiro) e a soma dos dois números anteriores portanto, a sequência segue o padrão F(n)=F(n−1)+F(n−2)).
f. 20 A sequência inicia com o número 2, seguido por um salto significativo para 10. Depois, a sequência é composta por incrementos menores:
10 (incremento de 8 a partir de 2)
12 (incremento de 2 a partir de 10)
16 (incremento de 4 a partir de 12)
17 (incremento de 1 a partir de 16)
18 (incremento de 1 a partir de 17)
19 (incremento de 1 a partir de 18)

Padrão: Após o número 16, a sequência apresenta uma série de números consecutivos (17, 18, 19), indicando que ela provavelmente continua com números inteiros sucessivos.

QUESTÃO 5:

Primeiro identificaria os 3 interrupitores: A, B, C.
Ai ligo o primeiro interruptor A e deixo ligado durante uns 10 min. Após esse tempo, desligo o interruptor A e ligo o interruptor B. Ai vou em uma das salas, e verifico alguns casos:
Caso 1: Se a lampada estiver ligada, ela e controlada pelo interruptor B, que eu deixei ligado.
Caso 2: Se a lampada estiver desligada, porem quente ai tocar nela, eu sei que ela e controlada pelo interruptor A.
Caso 3: Se a lampada estiver desligada e fria, saberei que e o interruptor C, já que nunca liguei.
A partir dai repito o processo e identifico todas
