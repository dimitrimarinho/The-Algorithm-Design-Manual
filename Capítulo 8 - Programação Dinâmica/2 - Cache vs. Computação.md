## 8.1 Cache vs. Computação

A programação dinâmica é essencialmente uma troca de espaço por tempo. Recalcular repetidamente uma determinada quantidade é inofensivo, a menos que o tempo gasto ao fazer isso atrapalhe o desempenho. Então, é melhor armazenar os resultados da computação inicial e procurá-los ao invés de recomputá-los novamente.

A troca entre espaço e tempo explorada em programação dinâmica é melhor ilustrada quando se avaliam relações de recorrência como os números de Fibonacci. Analisamos três programas diferentes para calculá-los abaixo.

### 8.1.1 Números de Fibonacci por recursão

Os números de Fibonacci foram originalmente definidos pelo matemático italitano Fibonacci no século XIII para modelar o crescimento das populações de coelho.Os coelhos. Coelhos se reproduzem, bem, como coelhos. Fibonacci supôs que o número de pares de coelhos nascidos em um dado ano é igual ao número de pares de coelhos nascidos em cada um dos dois anos anteriores, começando com um par de coelhos no primeiro ano. Para contar o número de coelhos nascidos no ano n, ele definiu a relação de recorrência:

<p align="center"><img src="../imgs/Número_de_Fibonacci.png?raw=true" alt="Número de Fibonacci" title="Número de Fibonacci"><br></p>
