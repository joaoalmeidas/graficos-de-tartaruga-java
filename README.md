# graficos-de-tartaruga-java
Exercicio 7.21 do livro Java: Como Programar


(Gráficos de tartaruga) A linguagem Logo tornou famoso o conceito de gráficos de tartaruga. Imagine uma tartaruga mecânica que
caminha no lugar sob o controle de um aplicativo Java. A tartaruga segura uma caneta em uma de duas posições, para cima ou para
baixo. Enquanto a caneta estiver para baixo, a tartaruga desenha formas à medida que se move, e enquanto estiver para cima, a tartaruga
move-se quase livremente sem escrever nada. Neste problema, você simulará a operação da tartaruga e criará um bloco de rascunho computadorizado.
Utilize um array de 20 por 20 floor que é inicializado como zeros. Leia comandos a partir de um array que contenha esses comandos.
Monitore a posição atual da tartaruga todas as vezes e se a caneta está atualmente para cima ou para baixo. Suponha que a tartaruga sempre
inicie na posição (0, 0) do chão com sua caneta para cima. O conjunto de comandos de tartaruga que seu aplicativo deve processar é mostrado na Figura 7.29.

Comando Significado

1       Caneta para cima
2       Caneta para baixo
3       Vira para a direita
4       Vira para a esquerda
5,10    Avance 10 espaços (substitua 10 por um número diferente de espaços)
6       Exiba o array 20 por 20
9       Fim dos dados (sentinela)


Suponha que a tartaruga esteja em algum lugar próximo ao centro do chão. O “programa” seguinte desenharia e exibiria um quadrado de 12 por 12 deixando a caneta na posição levantada:
2
5,12
3
5,12
3
5,12
3
5,12
1
6
9
À medida que a tartaruga se move com a caneta por baixo, configure os elementos apropriados do array floor como 1s. Quando o
comando 6 (exibir o array) for dado, onde quer que haja um 1 no array, exiba um asterisco ou o caractere que você escolher. Onde quer que
haja um 0, exiba um espaço em branco.
Escreva um aplicativo para implementar as capacidades dos gráficos de tartaruga discutidas aqui. Escreva vários programas de gráfico
de tartaruga para desenhar formas interessantes. Adicione outros comandos para aumentar as capacidades de sua linguagem de gráfico de
tartaruga.
