Como funciona o código:
Pygame: Usamos o Pygame para desenhar os objetos (bola, raquetes) e gerenciar a tela do jogo.

Pontuação: A cada vez que a bola sai pela lateral, a pontuação do jogador adversário aumenta e a bola é reposicionada.

Arquivo de Pontuação: Quando o jogo é encerrado (quando o usuário fecha a janela do jogo), as pontuações finais são salvas no arquivo pontuacoes.txt.

Pontos importantes:
As raquetes podem ser controladas com as teclas W/S para o jogador 1 (movimento para cima e para baixo) e Seta para Cima/baixo para o jogador 2.

A bola se move de forma contínua e rebaterá nas raquetes e nas paredes superior e inferior da tela.

Quando a bola sai pela lateral, o jogador adversário ganha 1 ponto, e o jogo recomeça com a bola centralizada.

O arquivo pontuacoes.txt vai armazenar as pontuações das partidas.

Você pode rodar o código, jogar e depois verificar o arquivo pontuacoes.txt para ver a pontuação registrada após o término da partida!
