# Foxes are cute
Se trata de um jogo onde o jogador controla uma raposa, essa pode se mover em um cenário 2D e possui pulos duplos! O objetivo do jogo é coletar 7 diamantes espalhados pela fase com o mínimo de erros possível. Cada vez que o jogador esbarra com um inimigo ou cai em espinhos ele é retornado para o começo da fase e é adicionada uma perda ao contador. Ao coletar os 7 diamantes, o jogador pode inserir o nome que quiser, este será enviado para o banco de dados da app para gerar um ranking que mostra quais jogadores morreram mais ou menos que outros!

Alguns detalhes extra sobre o jogo, ao coletar um coração, a raposa ganha um boost permanente de velocidade e altura do pulo. O jogo também possui uma mecânica onde algumas esferas amarelas estão espalhadas pelo mapa, estas não são coletáveis, mas servem para resettar seu pulo duplo. Toda vez que passar por uma esfera amarela, a raposa podera utilizar seu pulo duplo mais uma vez.

Bom game!

Preciso também ressaltar alguns problemas que tive. Primeiro é o tempo de resposta do banco de dados. Por algum motivo, o banco está com tempo de resposta extremamente lento, demorando mais de minuto. Mas se aguardar ou deixar rodando em segundo plano, eventualmente ele responde. Outro detalhe é o newline. Tentei de tudo mas por algum motivo o Construct está identificando newline como string, ao invés do comando para criar uma nova linha, então os dados estão chegando do banco mas estão sendo mal formatados devido a este problema.

https://www.construct.net/en/free-online-games/foxes-cute-75966/play
