# Game War Card desenvolvido em Python

Jogo War
O Jogo War é um jogo de cartas simples entre dois jogadores. O jogo é jogado com um baralho padrão de 52 cartas. As cartas são distribuídas igualmente entre os dois jogadores e o jogo começa.
![Imagem fazendo alusão a um baraho de cartas contendo o símbolo da linguagem Python](https://github.com/Penichezito/war-game/blob/main/img/war-card-python.jpg)

## ***Regras do Jogo War Card***

+ Início do Jogo: No início do Jogo War, cada jogador recebe metade do baralho de cartas. As cartas de cada jogador são mantidas em uma pilha virada para baixo.
+ Jogada: Em cada rodada do Jogo War, cada jogador vira a carta do topo de sua pilha. A carta com o maior valor ganha a rodada e o jogador vencedor leva ambas as cartas, colocando-as no fundo de sua pilha.
+ Valores das Cartas: As cartas têm valores de 2 a 10, seguidos por Valete, Rainha, Rei e Ás em ordem crescente de valor. Portanto, o Ás é a carta de maior valor e 2 é a de menor valor.
+ Empates: Se houver um empate, ou seja, se ambas as cartas tiverem o mesmo valor, nenhuma carta é movida e o jogo continua para a próxima rodada.
+ Fim do Jogo: O Jogo War termina quando um dos jogadores fica sem cartas. O jogador que ainda tem cartas é o vencedor.
+ Sair do Jogo: A qualquer momento durante o Jogo War, um jogador pode escolher sair do jogo pressionando ‘q’ quando solicitado.

## ***Explicação simplificada do código***

+ Classe Card: Esta classe representa uma carta individual no baralho. Cada carta tem um valor (2 a 10, Valete, Rainha, Rei, Ás) e um naipe (Espadas, Copas, Ouros, Paus). A classe também define métodos para comparar duas cartas.
+ Classe Deck: Esta classe representa um baralho de cartas. No início do jogo, um baralho é criado com 52 cartas (13 valores * 4 naipes) e as cartas são embaralhadas. A classe também define um método para remover uma carta do baralho.
+ Classe Player: Esta classe representa um jogador. Cada jogador tem um nome, uma carta atual (que é jogada em cada rodada) e um contador de vitórias.
+ Classe Game: Esta classe representa o jogo em si. Ela define o fluxo do jogo, incluindo a distribuição das cartas, a jogada de cada rodada e a determinação do vencedor. A classe também define métodos para exibir o estado atual do jogo.
+ Fluxo do Jogo: No início do jogo, cada jogador recebe metade do baralho. Em cada rodada, cada jogador joga a carta do topo de sua pilha. A carta de maior valor ganha a rodada e o jogador vencedor leva ambas as cartas. O jogo continua até que um dos jogadores fique sem cartas, e o jogador com cartas restantes é declarado o vencedor.
