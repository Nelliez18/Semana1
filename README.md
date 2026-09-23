Calculadora de troco
```python
valor_compra = float(input())
valor_pago = float(input())

troco = valor_pago - valor_compra

print(f"Troco: R\$ {troco:.2f}")
```

Média de notas
```python
nota1 = float(input())
nota2 = float(input())
nota3 = float(input())

media = (nota1 + nota2 + nota3) / 3

print(f"Média: {media:.2f}")
```
Conversor de tempo
```python
segundos_total = int(input())

horas = segundos_total // 3600
resto = segundos_total % 3600

minutos = resto // 60
segundos = resto % 60

print(f"{horas}h {minutos}m {segundos}s")
```
Calculadora de desconto
```python
preco_original = float(input())
percentual_desconto = float(input())

desconto = preco_original * (percentual_desconto / 100)
preco_final = preco_original - desconto

print(f"Preço final: R$ {preco_final:.2f}")
```
Par ou ímpar
```python
numero = int(input())

if numero % 2 == 0:
    print("O número é PAR")
else:
    print("O número é ÍMPAR")
```
Inversor de nome
```python
nome = input()
nome_invertido = nome[::-1]

print(f"Nome invertido: {nome_invertido}")
```
