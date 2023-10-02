# garrafas

T = int(input("Quantidade de testes:"))

for i in range(T):
    N, K = [int(x) for x in input("Digite o número de garrafas compradas e o número de garrafas vazias para ganhar uma cheia, separados por espaço:").split()]
    
    if K > N:
        print(N)
    else:
        print((N % K) + (N // K))

