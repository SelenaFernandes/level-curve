O arquivo notebook python consiste implementação de uma função em Python que calcule numericamente a curva de nível de uma dada função f. 

Assumiremos que a função \( f \) é diferenciável e seu domínio é o plano cartesiano \( \mathbb{R}^2 \) e a imagem é a reta real.

A função segue a seguinte assinatura:

```
def level\_curve(f, x0):

```

Na função level_curve, f é a função da qual você deseja encontrar a curva de nível, e x0 é um ponto por onde a curva de nível passa, ou seja, f(x) = f(x0) define o nível da curva.