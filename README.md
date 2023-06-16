# aula1python
Aula 1 de python IMC
#CARACTERES - STR
#INTEIRO - INT
#REAL - FLOAT

nome = str(input("escreva seu nome"))
print("seja bemvindo: ", nome)

print("vamos calcular o IMC")
peso = float(input("digite seu peso: "))
altura = float(input("digite sua altura: "))

IMC = (altura * 2) / peso





print(f"esse e meu peso: {peso}\n essa e minha altura: {altura}\n e esse e seu IMC: {IMC}")


print("-----OMS-----")



if IMC < 20:
    print(f"Você esta abaixo do peso! /n seu IMC e: {IMC}")
elif IMC >= 20 and IMC < 25:
    print(f"Você esta no peso ideal! /n seu IMC e: {IMC}")
elif IMC >=25 and IMC <30:
    print(f"Você esta acima do peso! /n seu IMC e: {IMC}")
elif IMC >=30 and IMC <34:
    print(f"Você esta fofinho! /n seu IMC e: {IMC}")
else  :
    print(f"Você esta fofinho ate demais! /n seu IMC e: {IMC}")
#############################################################


