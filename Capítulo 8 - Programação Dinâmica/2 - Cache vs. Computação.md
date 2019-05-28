## Cache vs. Computação

A programação dinâmica é essencialmente uma troca de espaço por tempo. Recalcular repetidamente uma determinada quantidade é inofensivo, a menos que o tempo gasto ao fazer isso atrapalhe o desempenho. Então, é melhor armazenar os resultados da computação inicial e procurá-los ao invés de recomputá-los novamente.

A troca entre espaço e tempo explorada em programação dinâmica é melhor ilustrada quando se avaliam relações de recorrência como os números de Fibonacci. Analisamos três programas diferentes para calculá-los abaixo.
