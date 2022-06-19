# Análise assintótica

## Resumo do capítulo 5

Referência para o resumo: http://flaviomoura.info/files/lca.pdf

Nesse ponto iremos analisar a quantidade de recursos demandados por um algoritmo.

### Big O Notation

Analíse da eficiência de um algoritmo

- worst-case -> analisamos sempre esse caso
- best-case
- average-case

### Sequential Search

1 - Buscar um elemento x numa lista;
2 - Da esquerda para a direita até encontrar o elemento;
3 - O(n)

Invariante:

Correção do algoritmo:

Complexidade tempo e espaço:

### Insertion Sort

1 - os números são comparados com os números à esquerda;
2 - caso maior, o número é trocado até encontrar um número menor;
3 - 

Invariante:

Correção do algoritmo:

Complexidade tempo e espaço:

### Bubble Sort

1 - A comparação é feita em pares;
2- Cada iteração coloca o maior número para sua posição correta;
3 - 

Invariante:

Correção do algoritmo:

Complexidade tempo e espaço:

### Selection Sort

1 - seleciona o menor elemento;
2 - coloca esse elemento no início da lista;
3 - nova iteração, seleciona novamente o menor elemento a partir da posição n da iteração;
4 - o menor elemento encontrado é colocado na posição n da lista;

Invariante:

Correção do algoritmo:

Complexidade tempo e espaço: