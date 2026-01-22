## Matrizes

&emsp;Matriz é uma estrutura matemática disposta em tabela e que possui as operações de adição, subtração e multiplicação muito bem definidas.

&emsp;A definição matemática de uma matriz de ordem (m x n) é uma tabela de números dispostoes em m linhas e n colunas.

##### Notação:
&emsp; A = [**a**ij]3X2
A é a matriz, **a** o elemnto, i o número da linha, e j o número da coluna que ele se encontra, cada elento possui seu endereço na forma da anotação acima.

#### Tipos de matrizes:
&emsp;Lembrando que uma matriz pode ter vários tipos.
##### Matriz Linha:
&emsp;São matrizes que possuem apenas uma única linha. 
Matematicamente: m = 1.
Por exemplo: 

    [1 , 2, 3, 4] = 1 X n

##### Matriz Coluna:
&emsp;São matrizes que possuem apenas uma única coluna.
Matematicamente: n = 1. 
Por exemplo: 

            [1]
            [2]  = 1 X n
            [3]

##### Matriz Nula:
&emsp;Todas as suas entradas são 0
Matematicamente: **a**ij = 0.
Por exemplo:

    A = 0 0 0
        0 0 0 
        0 0 0

##### Matriz Quadrada:
&emsp;Matrizes que o número de linhas e colunas são iguais
Matematicamente: m = n.
Por exemplo:
    
    A = 1 2 3 5
        5 2 5 5
        1 0 4 4
        1 3 3 7

A matriz quadrada possui alguns subgrupos como:
##### Matriz Identidade:
&emsp;Possui 1 na diagonal principal e 0 nos endereços restantes:
Por exemplo:

    A = 1 0 0
        0 1 0
        0 0 1

##### Matriz Diagonal:
&emsp;Todos os valores fora da diagonal principal são 0.
Por exemplo:

    A = -5 0 0
         0 2 0
         0 0 1

##### Matriz Escalar:
&emsp;Possui valores iguais na diagonal principal e 0 nos endereços restantes:
Por exemplo:

    A = 2 0 0
        0 2 0
        0 0 2

##### Matriz Triangular Superior:
&emsp;Possui valores localizados apenas no triângulo da parte de cima da  matriz 
Por exemplo:

    A = 2  1 -7
        0  5  4
        0  0  8

##### Matriz Triangular Inferior:
&emsp;Possui valores localizados apenas no triângulo da parte de baixo da  matriz 
Por exemplo:

    A =  2 0 0
         3 6 0
        -7 4 2

#### Operações com matrizes:
##### &emsp;Adição:
&emsp;Para realizar a adição de uma matriz A à uma matriz B, primeiramente
as duas tem que ter a mesma quantidade de linhas e de colunas
e depois deve-se somar elemento a elemento da matriz A com os da matriz B o que resulta em uma matiz C
    por exemplo:

        A = 1 2 3   B = 5 -8 7    C = 6  -6 10
            4 8 6       4 -1 0        8   7  6
            7 9 7       4  7 6        11 16 13

##### Multiplicação por escalar:
&emsp;para multiplicação por escalar (n . Matriz) acontece, o n deve 
multiplicar cada item dentro da matrix
por exemplo:
        
        n = 3            
        A = 1 2 3       (n . A) =    3  6  9            
            4 8 6                   12 24 18       
            7 9 7                   21 27 21
         
            
            
        
        