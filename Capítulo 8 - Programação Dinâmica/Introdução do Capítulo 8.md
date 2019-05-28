## Programação Dinâmica

Os problemas algorítmicos mais desafiadores envolvem a otimização, onde buscamos encontrar uma solução que maximize ou minimize alguma função. O vendedor viajante é um problema clássico de otimização, onde buscamos o passeio visitando todos os vértices de um grafo pelo custo total mínimo. Mas, como mostrado no Capítulo 1, é fácil propor "algoritmos" que geram soluções razoáveis, mas nem sempre produzam o passeio de custo mínimo.

Algoritmos para problemas de otimização exigem prova de que eles sempre retornam a melhor solução possível. Algoritmos gulosos que tomam a melhor decisão local em cada etapa são tipicamente eficientes, mas geralmente não garantem a otimização global. Algoritmos de busca exaustiva que tentam todas as possibilidades e selecionam sempre as melhores produzem o melhor resultado, mas geralmente a um custo proibitivo em termos de complexidade de tempo.

A programação dinâmica combina o melhor dos dois mundos. Ela nos dá um jeito de projetas algoritmos personalizados que pesquisam sistematicamente todas as possibilidades (garantindo assim a correção) ao armazenar os resultados para evitar a recomputação (proporcionando assim eficiência). Ao armazenar as consequências de todas as decisões possíveis e usar esta informação de maneira sistemática, a quantidade total de trabalho é minimizada.
