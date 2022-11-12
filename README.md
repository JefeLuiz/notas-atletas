# notas-atletas
Foi desenvolvida uma função capaz de receber uma matriz de objetos contendo o nome do atleta e as cinco notas atribuídas. 
A é capaz de calcular a média das notas sem considerar a maior e menor nota do atleta. Como resultado apresenta ao usuário o nome de cada atleta, 
seguido das notas e da média calculada.

A partir do objeto atletas compostos por chaves de nome e notas, foi criada uma nova variavel para armazenar as notas  após a ordenação decrescente da mesma,
em seguida foi criado um loop for para percorrer todo o objeto.

Através do método sort() e slice() foi possivel ordenar as notas e desconsiderar as notas mais altas e mais baixas, na proxima operação ainda dentro do loop
foi somado as notas de cada atleta e em seguida feito a média das notas de cada um.

Por fim, através da variável media construida dentro do laço for, foi adicionado os valores das médias ao objeto atletas, possibilitando assim a cosnstrução
da respota mostrando os seguintes resultados no console.log.


Atleta: Cesar Abascal
Notas Obtidas: 10,10,9.34,8.42,7.88
Média Válida: 9.253333333333332
 
Atleta: Fernando Puntel
Notas Obtidas: 10,10,9.33,8,7
Média Válida: 9.11
 
Atleta: Daiane Jelinsky
Notas Obtidas: 10,9.5,9.5,8,7
Média Válida: 9
 
Atleta: Bruno Castro
Notas Obtidas: 10,10,10,9.5,9
Média Válida: 9.833333333333334
 
