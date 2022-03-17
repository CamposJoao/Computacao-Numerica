# Computacao-Numerica

## Integração Numérica
Uma função ```integrate(...)``` em Python 3.X que implementa os métodos de integração do **retângulo** (```'rect'```), do **trapézio** (```'trapz'```), de **Simpson 1/3** (```'simp3'```) e de **Simpson 3/8** (```'simp8'```) e que recebe como parâmetros uma função ```f```, o intervalo de integração ```[a, b]```, o número de subintervalos, e a string identificando o método de integração a ser aplicado. No caso de um número de subintervalos inválido, o programa escolhe o próximo número de subintervalos válido maior que aquele fornecido. 

## Equações Diferenciais Ordinárias (EDO) Numérica 
Uma função ```solve_edo(...)``` em Python 3.X que implementa os métodos de integração de **Euler** (```'euler'```), de **Euler modificado** (```'eulerm'```) e do **ponto central** (```'center'```) e que recebe como parâmetros a equação diferencial ```dydx```, o intervalo de solução ```[a, b]```, a condição inicial ```x0```, o passo de solução ```h``` e a string identificando o método de solução de EDOs a ser aplicado.
