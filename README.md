# Strings

nome = str(input('Nome completo: ')).strip().upper()
print('Seu nome em letras maiúsculas é: {}.'.format(nome))
print('='*65)
endereco = str(input('Digite qual o seu endereço: '))
print('Digite o seu endereço em forma de listas: {}.'.format(endereco.split()))
print('='*65)
cidade = str(input('Digite o nome da cidade em que habita: '))
cont_letras = len(cidade) - cidade.count(' ')
print('O nome da cidade ao todo contém {} letras.'.format(cont_letras))
