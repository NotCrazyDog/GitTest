# GitTest
Just a test repository.

import time
choice = ''
i = 1
while i <= 100:
    print(f'{i}% - Carregando...''\n')
    i += 1
    time.sleep(0.25)
while choice != '0':
    print('''
          ----Calculadora Python----
          Soma - 1
          Subtração - 2
          Multiplicação - 3
          Divisão - 4
          Quadrado - 5
          Sair - 0
          --------------------------
          ''')
    choice = input('Digite sua escolha: ')
