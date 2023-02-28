# Sequ-ncia-de-Fibonacci
T1 = 0
T2 = 1
T3 = 0
n = int(input('Digite um número para saber se faz parte da sequência de Fibonacci: '))
print(f'{T1}\n{T2}')
while n > T3:
    T3 = T1 + T2
    print(f'{T3}')
    T1 = T2
    T2 = T3
if n == 0 or n== 1:
    print ('O número faz parte da sequência de Fibonacci!')
elif n == T3:
    print ('O número faz parte da sequência de Fibonacci!')
else:
    print ('O número digitado NÃO faz parte da sequência de Fibonacci!')
