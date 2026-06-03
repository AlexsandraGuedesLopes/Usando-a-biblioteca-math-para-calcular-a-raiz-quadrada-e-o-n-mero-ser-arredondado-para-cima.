# Usando-a-biblioteca-math-para-calcular-a-raiz-quadrada-e-o-n-mero-ser-arredondado-para-cima.
Usando a biblioteca "math" para calcular a raiz quadrada e o número será arredondado para cima com a função "ceil"
import math
n1 = int(input("Digite um número: "))
raiz = math.sqrt(n1)
print("A raiz de {} é igual a {}".format(n1, math.ceil(raiz)))
