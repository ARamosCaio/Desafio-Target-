# Desafio Target
## Respostas as questões do teste

1) O valor da variável SOMA após o final do processamento é 91

```python
indice, k, soma = 13, 0, 0

while k < indice:
  k += 1
  soma += k
print(soma)

```

2)

```python
num_informado = int(input("Insira o valor desejado: "))

seq = 0
num = 1
ans = 0
fib = []
while ans < num_informado:
  ans = seq + num
  seq = num
  num = ans
  fib.append(ans)
  print(ans)

if num_informado in fib:
  print("O valor inserido pertence a sequência")
else:
  print("O valor inserido não pertence a sequência")

```
3) 


a) 1, 3, 5, 7, __9__ (números ímpares)

b) 2, 4, 8, 16, 32, 64, __128__ (dois elevado a 1, dois elevado a 2, dois elevado a 3 ...)

c) 0, 1, 4, 9, 16, 25, 36, __49__ (0x0, 1x1, 2x2, 3x3 ...)

d) 4, 16, 36, 64, __100__ (quadrados perfeitos: 2x2, 4x4, 6x6 ...)

e) 1, 1, 2, 3, 5, 8, __13__ (fibonacci)

f) 2,10, 12, 16, 17, 18, 19, __200__ (números que iniciam com a letra "d" ordenados)


4)

 - Pressionaria o primeiro interruptor duas vezes, ligando e desligando a lâmpada.
 - Pressionaria o segundo interruptor e deixaria a lâmpada ligada.

Após isso, entraria em qualquer uma das salas, a lâmpada que estiver quente e apagada corresponde ao primeiro interruptor, a que estiver fria e apagada corresponde ao último interruptor e a que estiver acesa corresponde ao segundo interruptor

5)

```python
def inverter_string(string):
    return string[::-1]

entrada = input("Digite a string a ser invertida: ")
print("String invertida:", inverter_string(entrada))
```
