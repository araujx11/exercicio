# exercicio
5° questao
a = []
for i in range(10):
    num = int(input("Digite um número para o vetor A: "))
    a.append(num)
X = int(input("Digite um número para a variável X: "))
m= [num * X for num in a]
print("O vetor M é:", m)
6º questao
numeros = []
for i in range(5):
    numero = int(input("Digite um número: "))
    numeros.append(numero)
print(numeros)
for i in range(4, -1, -1):
    print(numeros[i])
    7° questao igual a 6
    8°e 9° nao consegui
    10°
    11°
    vetor = []
for i in range(30):
    numero = int(input("Digite um número: "))
    vetor.append(numero)
numero_procura = int(input("Digite um número para buscar no vetor: "))
contagem = vetor.count(numero_procura)
print("O número", numero_procura, "aparece", contagem, "vezes no vetor.")
12°
nomes = []
for i in range(5):
    nome = input("Digite um nome: ")
    nomes.append(nome)
print("Lista dos nomes:")
for nome in nomes:
    print(nome)
print("Nomes na ordem inversa:")
for nome in reversed(nomes):
    print(nome)
    13°
    vetor = []
for i in range(30):
    numero = int(input('Digite um número inteiro: '))
    vetor.append(numero)
print('Números pares')
for numero in vetor:
    if numero % 2 == 0:
        print(numero)

menor = min(vetor)
maior = max(vetor)
print('Menor valor:', menor)
print('Maior valor:', maior)
media = sum(vetor) / len(vetor)
contador = 0
for numero in vetor:
    if numero > media:
        contador += 1
print('Quantidade de valores maiores ', contador)
