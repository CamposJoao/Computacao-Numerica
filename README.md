# Computacao-Numerica

## Sistemas de Equações Lineares
### Substituição Regressiva
Uma função ```back_substitution(...)``` em Python 3.X que implementa o método da **substituição regressiva** e que recebe como parâmetros uma matriz triangular superior ```A``` e um vetor ```b``` e que retorna um vetor ```x``` com a solução do sistema linear triangular, se houver.
### Substituição Progressiva
Uma função ```forward_substitution(...)``` em Python 3.X que implementa o método da **substituição progressiva** e que recebe como parâmetros uma matrix triangular inferior ```A``` e um vetor ```b``` e que retorna um vetor ```x``` com a solução do sistema linear triangular, se houver.
### Eliminação de Gauss com Pivotação Parcial
Uma função ```gauss_elimination(...)``` em Python 3.X que implementa a **eliminação de Gauss com pivotação parcial** e que recebe como parâmetro uma matrix  quadrada ```A```e um vetor ```b``` de dimensões adequadas e que retorna um vetor ```x``` com a solução do sistema linear, se houver.
### Decomposição LU
Uma função ```gauss_elimination(...)``` em Python 3.X que implementa a **decomposição LU** e que recebe como parâmetro uma matriz  quadrada ```A``` e que retorna seus fatores ```L``` e ```U```, se houverem.

## Integração Numérica
Uma função ```integrate(...)``` em Python 3.X que implementa os métodos de integração do **retângulo** (```'rect'```), do **trapézio** (```'trapz'```), de **Simpson 1/3** (```'simp3'```) e de **Simpson 3/8** (```'simp8'```) e que recebe como parâmetros uma função ```f```, o intervalo de integração ```[a, b]```, o número de subintervalos, e a string identificando o método de integração a ser aplicado. No caso de um número de subintervalos inválido, o programa escolhe o próximo número de subintervalos válido maior que aquele fornecido. 

## Equações Diferenciais Ordinárias (EDO) Numérica 
Uma função ```solve_edo(...)``` em Python 3.X que implementa os métodos de integração de **Euler** (```'euler'```), de **Euler modificado** (```'eulerm'```) e do **ponto central** (```'center'```) e que recebe como parâmetros a equação diferencial ```dydx```, o intervalo de solução ```[a, b]```, a condição inicial ```x0```, o passo de solução ```h``` e a string identificando o método de solução de EDOs a ser aplicado.
