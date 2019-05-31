## 8.1 Cache vs. Computação

A programação dinâmica é essencialmente uma troca de espaço por tempo. Recalcular repetidamente uma determinada quantidade é inofensivo, a menos que o tempo gasto ao fazer isso atrapalhe o desempenho. Então, é melhor armazenar os resultados da computação inicial e procurá-los ao invés de recomputá-los novamente.

A troca entre espaço e tempo explorada em programação dinâmica é melhor ilustrada quando se avaliam relações de recorrência como os números de Fibonacci. Analisamos três programas diferentes para calculá-los abaixo.

### 8.1.1 Números de Fibonacci por recursão

Os números de Fibonacci foram originalmente definidos pelo matemático italitano Fibonacci no século XIII para modelar o crescimento das populações de coelho. Coelhos se reproduzem, bem, como coelhos. Fibonacci supôs que o número de pares de coelhos nascidos em um dado ano é igual ao número de pares de coelhos nascidos em cada um dos dois anos anteriores, começando com um par de coelhos no primeiro ano. Para contar o número de coelhos nascidos no ano n, ele definiu a relação de recorrência:

<p align="center"><img src="../imgs/Número_de_Fibonacci.png?raw=true" alt="Número de Fibonacci" title="Número de Fibonacci"><br></p>

com os casos bases F<sub>0</sub> = 0 e F<sub>1</sub> = 1. Assim, F<sub>2</sub> = 1, F<sub>3</sub> = 2, e a série continua {3, 5, 8, 13, 21, 34, 55, 89, 144, ...}. Como se vê, a fórmula de Fibonacci não fez um bom trabalho contando coelhos, mas ela tem uma série de propriedades interessantes.

Uma vez que eles são definidos por um fórmula recursiva, é fácil escrever um programa recursivo para calcular o n-ésimo número de Fibonacci. Um algoritmo de função recursiva escrito em C se parece com isso:

<p align="center"><img src="../imgs/Algoritmo-recusivo-que-calcula-Fibonacci.png?raw=true" alt="Algoritmo em C que calcula o número de Fibonacci" title="Algoritmo em C que calcula o número de Fibonacci"><br></p>

<p align="center"><img src="../imgs/Árvore-recursiva-para-calcular-Fibonacci.png?raw=true" alt="Algoritmo em C que calcula o número de Fibonacci" title="Árvore recursiva para calcular o número de Fibonacci"><br></p>

<p align="center"> Figura 8.1: A árvore de computação para calcular os números de Fibonacci recursivamente </p>



