# Adivinhar-Um-Numero-Em-Python
Adivinhar Um Numero Em Python


from random import randint
def numero_aleatorio():
  aleatorio=randint(1,10000)
  chute=0
  while aleatorio != chute:
    chute=int(input("Digite um valor (1 a 10000): "))
    if (aleatorio == chute):
      print("Parabéns. Você acertou!")
    else:
      print("Tente novamente.")
numero_aleatorio()
