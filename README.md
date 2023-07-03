# Python-NotasMinimas
# Codigo simples para quantidades de notas 
numero = int(input("Digite um valor para sacar: "))

cem = int(numero/100)
numero= numero-(cem*100)

cinquenta = int(numero/50)
numero = numero-(cinquenta*50)

dez = int(numero/10)
numero = numero-(dez*10)

cinco = int(numero/5)
numero = numero-(cinco*5)

um = numero
#saidas
print("Notas de R$ 100,00 = ",cem)
print("Notas de R$  50,00 = ",cinquenta)
print("Notas de R$  10,00 = ",dez)
print("Notas de R$   5,00 = ",cinco)
print("Notas de R$   1,00 = ",um)
#fim do codigo
