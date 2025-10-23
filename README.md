# Análise Estatística e Ordenação de Sequências de Números Inteiros
## Descrição

Este programa em C lê um conjunto de números a partir de um arquivo (dados.txt), realiza diversas análises estatísticas e gera diferentes arquivos de saída:

- estatisticas.txt: Contém a contagem de números positivos, negativos, zeros, pares e ímpares.

- distintos.txt: Armazena os números únicos do arquivo de entrada.

- ordenado.txt: Salva todos os números em ordem crescente.

- distintos_ordenado.txt: Armazena apenas os números únicos em ordem crescente.

## Funcionalidades

- Lê um arquivo de entrada e processa até 108 números.

- Verifica se o arquivo contém pelo menos 30 números.

- Realiza análise estatística sobre os números.

- Implementa o algoritmo Bubble Sort para ordenação crescente.

- Salva os dados processados em arquivos de saída separados.

## Compilação e Execução

1. Compile o programa utilizando o GCC:

gcc program.c -o program


2. Execute o programa compilado:

./program

## Formato do Arquivo de Entrada (dados.txt)

O arquivo de entrada deve começar com um número inteiro indicando a quantidade de valores, seguido pela lista dos números inteiros:

30
12 -5 0 8 3 ...

## Tratamento de Erros

- Caso o arquivo de entrada não possa ser aberto, uma mensagem de erro será exibida.

- Se o número de valores exceder 108, o programa será encerrado com erro.

- Se forem fornecidos menos de 30 números, o programa também será encerrado com erro.

- Erros ao criar arquivos de saída resultam em uma mensagem de erro e encerramento do programa.

## Algoritmo de Ordenação

O programa utiliza o algoritmo Bubble Sort para ordenar os números em ordem crescente.

## Exemplo de Saída

Após a execução, o programa gera os seguintes arquivos:

- estatisticas.txt:

   Quantidade de números positivos: X

   Quantidade de números negativos: Y

   Quantidade de zeros: Z

   Quantidade de números pares: A

   Quantidade de números ímpares: B


- distintos.txt: Números únicos separados por espaços

- ordenado.txt: Números ordenados separados por espaços

- distintos_ordenado.txt: Números únicos ordenados separados por espaços

## Observações

Certifique-se de que o arquivo de entrada siga o formato correto antes da execução para evitar erros.
