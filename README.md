# EstimaPi

Estime o valor de π utilizando o [método de Leibniz](https://pt.wikipedia.org/wiki/F%C3%B3rmula_de_Leibniz_para_%CF%80):

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/564a366471bdc3ca4d5403d3acf90c4370d4145e)

Ex.:
```
-- Estimador do valor de pi pelo método de Leibniz --
Quantas iterações? 1000000
Estimativa: 3,141594
```

_Desafio_: Fixar o número de casas decimais de precisão da estimativa. Dica: verifique o erro entre a estimativa atual e a anterior de forma que a diferença esteja em dígitos menores que a precisão desejada.

Ex.:
```
-- Estimador do valor de pi pelo método de Leibniz --
Quantas casas de precisão (<=10)? 7
Estimativa após 199999997 iterações: 3,1415926486
```

_Desafio 2_: Utilizar [outros métodos](https://en.wikipedia.org/wiki/Approximations_of_%CF%80) mais eficientes.
