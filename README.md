# Exercicio011.py
#Faça um algoritmo que leia o preço de um produto e mostre seu novo preço, com 5% de desconto

t = float(input('Digite o valor: '))
r = (t*0.05)
s = (t-r)
print('{:.2f}'.format(s))
