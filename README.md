# Labirinto do Rato
Este é um simples jogo de labirinto onde um rato (representado pela letra 'R') busca por um pedaço de queijo (representado pela letra 'Q') em um labirinto gerado aleatoriamente. O rato pode se mover para cima, baixo, esquerda ou direita, desde que não encontre uma parede (representada pelo caractere '*').

# Funcionamento do Código
O código consiste em uma aplicação em C# que utiliza uma matriz para representar o labirinto. Aqui está uma breve visão geral das funções principais:

mostrarLabirinto(char[,] array, int l, int c): Esta função exibe o labirinto na tela, onde array é a matriz representando o labirinto, l é o número de linhas e c é o número de colunas do labirinto.
criaLabirinto(char[,] meuLab): Esta função é responsável por criar o labirinto. Ela preenche a matriz meuLab com espaços vazios e paredes aleatórias, além de colocar o queijo em uma posição aleatória.
buscarQueijo(char[,] meuLab, int i, int j): Esta função é a principal do jogo. Ela implementa a lógica do rato buscando o queijo. O rato se move pelo labirinto de acordo com algumas regras simples, como verificar se pode se mover em uma direção e evitar paredes. O processo é repetido até que o rato encontre o queijo ou não consiga mais se mover.

# Executando o Jogo
Para executar o jogo, basta chamar a função Main na classe LabirintodoRato. Esta função inicializa o labirinto, exibe-o na tela, e então inicia a busca pelo queijo. O resultado da busca será exibido no console.

