import time
import math



def menu():
    print('')
    print('-=' * 20)
    print('-=' * 7, '{}Bem-Vindo{}'.format('\033[7;36;40m', '\033[m'), '-=' * 7)
    print('-=' * 20)
    print('-' * 5, '{}by Nayron Gabriel{}'.format('\033[4;36;40m', '\033[m'), '-' * 5)

    time.sleep(1)

    print('''            _______________________________
           |                               |
           |<1>  Para Soma                 |
           |<2>  Para Subtração            |
           |<3>  Para Divisão              |
           |<4>  Para Multiplicação        |
           |<5>  Para Potenciação          |
           |<6>  Para Raiz Quadrada        | 
           |<7>  Para Seno,Coseno,Tangente |  
           |<8>  Para Sair
           |_______________________________| ''')

    sinal = int(input('Qual operaçao você deseja ?'))
    opr(sinal)


def opr(sinal):
    if sinal == 1:
        n1 = int(input('Qual o primeiro número? '))
        n2 = int(input('Qual o segundo número? '))
        print('o resultado e {}'.format(n1 + n2))

    elif sinal == 2:
        n1 = int(input('Qual o primeiro número?  '))
        n2 = int(input('Qual o segundo número?  '))
        print('o resultado e {}'.format(n1 - n2))

    elif sinal == 3:
        n1 = int(input('Qual o primeiro numero?  '))
        n2 = int(input('Qual o segundo numero?  '))
        print('O resultado e {}'.format(n1 / n2))

    elif sinal == 4:
        n1 = int(input('Qual o primeiro número?  '))
        n2 = int(input('Qual o segundo número?  '))
        print('o resultado e {}'.format(n1 * n2))

    elif sinal == 5:
        n1 = int(input('Qual o número?  '))
        n2 = int(input('Quer elevar a quanto ??  '))
        print('o resultado e {}'.format(n1 ** n2))

    elif sinal == 6:
        n1 = int(input('Qual o número que quer a raiz?  '))
        print('o resultado e {}'.format(math.sqrt(n1)))

    elif sinal == 7:
        n1 = int(input('Qual o angulo?  '))
        print('O seno e {:.2f}'.format(math.sin(n1)))
        print('O cosseno e {:.2f}'.format(math.cos(n1)))
        print('A tangente e {:.2f}'.format(math.tan(n1)))
    menu()


menu()
