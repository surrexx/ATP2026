# TPC3_2026
### Autor: Maria Surreira, a112341,<img width="200" height="250" alt="WhatsApp Image 2026-09-01 at 14 07 13" src="https://github.com/user-attachments/assets/386accd6-8ae9-406d-964b-a33829912ffc" />



## Resumo:
## Jogo dos 100
O programa começa por importar a biblioteca `random`, que é utilizada para o computador conseguir escolher números aleatoriamente.

De seguida, é criada uma função chamada `menu()`. Esta função apresenta as três opções disponíveis: jogar com o computador como primeiro jogador, jogar com o computador como segundo jogador ou sair do programa.

Depois, é criada uma variável chamada `op`, que guarda a opção escolhida pelo utilizador. O programa utiliza um ciclo `while` que continua a executar enquanto a opção escolhida não for `0`.

Quando o utilizador escolhe a opção `1`, o computador começa o jogo. A variável `total` começa em zero e vai acumulando os números escolhidos pelos dois jogadores. O computador escolhe aleatoriamente um número entre 1 e 10 através de `random.randint()`. Depois, se ainda não tiver chegado aos 100, é a vez do utilizador escolher um número entre 1 e 10. Este processo repete-se até um dos jogadores chegar exatamente a 100.

Quando o utilizador escolhe a opção `2`, é o utilizador que começa. Depois da escolha do utilizador, o computador calcula a sua jogada através da expressão `11 - n`. Desta forma, se o utilizador escolher, por exemplo, 4, o computador escolhe 7. Assim, as duas jogadas juntas totalizam 11. O objetivo desta estratégia é tentar manter o controlo da soma até chegar aos 100.

Em ambos os modos, depois de cada jogada, o programa verifica se o total chegou a 100. Se isso acontecer, apresenta uma mensagem a indicar quem ganhou. Caso contrário, mostra o total acumulado e o jogo continua.

Por fim, se o utilizador escolher a opção `0`, o programa apresenta a mensagem "Até à próxima!" e termina. Se for introduzida outra opção, o programa informa que a opção é inválida e volta a apresentar o menu.

#### Lista de Resultados:
[TPC3.ipynb](https://github.com/user-attachments/files/33000500/TPC3.ipynb)

