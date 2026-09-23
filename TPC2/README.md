# TPC2_2026
### Autor: Maria Surreira, a112341,<img width="200" height="250" alt="WhatsApp Image 2026-09-01 at 14 07 13" src="https://github.com/user-attachments/assets/386accd6-8ae9-406d-964b-a33829912ffc" />


## Resumo:
Este TPC consiste num jogo de adivinhação desenvolvido em Python, no qual o utilizador pode escolher entre duas modalidades diferentes: numa delas, o utilizador tenta descobrir um número escolhido aleatoriamente pelo computador; na outra, é o computador que tenta descobrir o número pensado pelo utilizador.

### Funcionamento do Programa:
Ao iniciar o programa, é apresentado um menu com três opções:

O utilizador tenta adivinhar o número escolhido pelo computador;
O computador tenta adivinhar o número pensado pelo utilizador;
Sair do programa.

O programa utiliza um ciclo while principal para manter o menu ativo até que o utilizador escolha a opção 3.


#### Modalidade 1:
Nesta modalidade, o computador utiliza a função random.randint(0,100) para gerar aleatoriamente um número inteiro entre 0 e 100.

O utilizador introduz sucessivamente os seus palpites. A cada tentativa:

Se o palpite for menor que o número escolhido, o programa indica que o número correto é maior;
Se o palpite for maior, indica que o número correto é menor;
Se o palpite for igual ao número escolhido, o programa informa que o utilizador acertou e apresenta o número de tentativas realizadas.

Para controlar este processo é utilizado um ciclo while, que continua enquanto o palpite for diferente do número escolhido.

#### Modalidade 2:
Nesta modalidade, o utilizador pensa num número entre 0 e 100, sem o introduzir no programa.

O computador começa por gerar aleatoriamente um número dentro desse intervalo através de random.randint().

Depois de cada tentativa, o utilizador deve indicar se o número pensado é:

maior — o número pensado é superior ao palpite do computador;
menor — o número pensado é inferior ao palpite;
sim — o computador acertou.

Com base na resposta, o programa atualiza os limites do intervalo de procura. Por exemplo, se o computador disser 50 e o utilizador responder maior, o limite inferior passa a ser 51.

Este processo repete-se até o computador acertar o número. No final, é apresentada a quantidade de tentativas necessárias.

### Lista de Resultados: [TPC2.ipynb](https://github.com/user-attachments/files/32563417/TPC2.ipynb)
