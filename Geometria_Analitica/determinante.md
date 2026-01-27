## Determinante

#### O que é um determinante?
&emsp;Um determinante é uma função que mapeia uma matriz quadrada em um escalar real (valor único). Em matemática, o determinante de uma matriz quadrada A é mostrado como det(A) ou |A|.

&emsp;Assim como a própria matemática, o determinante tem uma longa história que remonta aos matemáticos chineses. Na China antiga, os matemáticos usavam determinantes para resolver sistemas de equações lineares (seu método de resolução de equações lineares é hoje chamado de Regra de Cramer). Mais tarde, na Europa do século XVI, o matemático Cardano trouxe os determinantes à tona, aplicando-os na solução de sistemas de equações lineares. Mais tarde, Takakazu (século XVII), Leibniz (século XVII), Vandermonde e Cauchy (século XVIII) estabeleceram a base teórica dos determinantes na matemática pura.

##### Como calcular?
&emsp;**Matrix de ordem 1 (1 x 1)**
O determinante é o valor do único elemento presente na matrix.
![alt text](images/determinante1x1.png)

&emsp;**Matrix de ordem 2 (2 x 2)**
O determinante é o valor da multiplicação dos números da diagonal principal subtraído pela multiplicação dos números da diagonal secundária.
![alt text](images/determinante2x2.png)

&emsp;**Matrix de ordem 3 (3 x 3) (usando regra de Sarrus)**
Consiste em escrever as três colunas da matriz e repetir as duas primeiras colunas, logo depois deve-se somar o resultado da multiplicação das três primeiras diagonais da parte superior da matrizm, e subtrair pela soma do resultado da multiplicação das três primeiras colunas inferiores da matriz 
![alt text](images/determinante3x3.png)

&emsp;**Matrix de qualquer ordem acima de dois (teorema de Laplace)**
Para entender esse teorema precisamos de dois conceitos preliminares, que são,
menor complementar e cofator