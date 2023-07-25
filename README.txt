"Game Of Life".

   O objetivo é permitir que o usuário jogue o "Conway's Game of Life". 
É de um jogo de simulação, no qual o progresso depende de uma configuração inicial.
A única forma de interação que o usuário terá com o jogo é definir um estado inicial.
O jogo começa com um tabuleiro no qual o usuário seleciona as células que devem ficar inicialmente ativas.
Em seguida, pressiona a tecla "S" para iniciar a simulação.
Durante a simulação, com base no padrão inicial e nas regras específicas do jogo, o estado é alterado,
ligando ou desligando as células do tabuleiro.

para mais informações sobre o jogo acesse: https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life

Regras do jogo:
   1 - "Qualquer célula viva com menos de dois vizinhos vivos morre, como se por subpopulação."
   2 - "Qualquer célula viva com dois ou três vizinhos vivos passa para a próxima geração."
   3 - "Qualquer célula viva com mais de três vizinhos vivos morre, como se por superpopulação."
   4 - "Qualquer célula morta com exatamente três vizinhos vivos torna-se viva, como se por reprodução."
   

Funcionalidades:
   1 - Configurar as celulas ativas no estádo inicial
         -Usando o mause: botão direito para ativar/botão esquerdo para desativar
   2 - Iniciar simulação
         -Tecla "S"
   3 - Finalisar simulação
      -Tecla "Q"

*O Tabuleiro não é infinito
**Diminsões do tabuleiro: 51x51
***Obs:  Esse projeto foi desenvolvido usando a Linguagem Ceu,
         E sua biblioteca grafica, o pico-ceu. Para instalar
         o compilador de Ceu e sua biblioteca grafica acesse
         o link: https://github.com/fsantanna/dceu
