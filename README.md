# Calculo-do-ano-de-nascimento

# Online Python compiler (interpreter) to run Python online.
# Write Python 3 code in this online editor and run it.

nome = input ("Digite seu nome:")
print ("Seu nome é:", nome)

idade =int (input ("Qual sua idade? "))
print (("O ano em que você nasceu é? "),2023 - idade)


saldo = float(input("Digite seu saldo:"))
print (nome, "O seu saldo é de:",saldo)

perc = int(input("Qual a porcentagem bônus?"))
print ("Seu saldo com bônus:" ,(saldo*perc)/100+saldo) 
print (f"Você {nome} que nasceu em {2023-idade} terá o bônus de {perc}%, que será de R${(saldo*perc)/100+saldo}")
