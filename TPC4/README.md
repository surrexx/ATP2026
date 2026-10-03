# TPC3_2026
### Autor: Maria Surreira, a112341,<img width="200" height="250" alt="WhatsApp Image 2026-09-01 at 14 07 13" src="https://github.com/user-attachments/assets/386accd6-8ae9-406d-964b-a33829912ffc" />

### Resumo:
O programa começa por importar a biblioteca `random`, que vai ser utilizada para gerar números aleatórios quando for criada uma lista automaticamente.

De seguida, criei a função `menu()`, que apresenta no ecrã todas as opções disponíveis: criar uma lista, ler uma lista, calcular a soma, calcular a média, encontrar o maior e o menor elemento, verificar se a lista está ordenada de forma crescente ou decrescente, procurar um elemento e sair do programa.

Também criei a função `Nota()`, que mostra uma mensagem a avisar o utilizador de que, antes de utilizar as opções 3 a 9, tem de criar ou ler uma lista através das opções 1 ou 2.

Depois são criadas duas variáveis principais: `op`, que guarda a opção escolhida pelo utilizador, e `lista`, que começa como uma lista vazia.

Na opção 1, é utilizada a função `criaLista(n)`. O utilizador indica quantos números quer na lista e a função utiliza um ciclo `while` para gerar essa quantidade de números aleatórios entre 0 e 100. Cada número é acrescentado à lista através do método `append()`. No final, a função devolve a lista criada.

Na opção 2, é utilizada a função `LerLista(n)`. Neste caso, o utilizador escolhe quantos números quer inserir e, através de um ciclo `while`, vai introduzindo os números um a um. Esses números são adicionados à lista e, no final, a função devolve a lista.

Na opção 3, a função `soma(lista)` calcula a soma de todos os elementos. Para isso, começa com uma variável `soma` igual a zero e percorre todos os elementos da lista, adicionando cada um ao total.

Na opção 4, a função `media(lista)` calcula a média dos elementos. Primeiro soma todos os valores e depois divide essa soma pelo número de elementos existentes na lista, utilizando `len(lista)`.

Na opção 5, a função `maior(lista)` procura o maior elemento. Começa por considerar que o primeiro elemento é o maior e depois percorre a lista. Sempre que encontra um número maior, atualiza a variável `maior`.

Na opção 6, a função `menor(lista)` funciona de forma semelhante, mas procura o menor elemento. Começa pelo primeiro elemento e vai substituindo o valor sempre que encontra um número mais pequeno.

Na opção 7, a função `estaOrdenadaC(lista)` verifica se a lista está ordenada por ordem crescente. Compara cada elemento com o elemento seguinte. Se encontrar um elemento maior do que o seguinte, significa que a lista não está ordenada de forma crescente e o resultado passa a ser `não`.

Na opção 8, a função `estaOrdenadaD(lista)` faz o processo contrário. Verifica se cada elemento é maior ou igual ao seguinte, para determinar se a lista está ordenada por ordem decrescente.

Na opção 9, a função `procuraElem(lista, elem)` procura um determinado elemento dentro da lista. O utilizador introduz o elemento que quer procurar e a função percorre a lista. Se encontrar o elemento, devolve a sua posição. Se não encontrar, devolve `-1`.

Depois de todas estas funções estarem definidas, começa o ciclo principal do programa. Enquanto a opção escolhida não for `0`, o menu é apresentado e o utilizador escolhe uma operação.

Para as opções 3 a 9, o programa primeiro verifica se a lista está vazia através de `len(lista) == 0`. Se estiver vazia, apresenta uma mensagem a dizer que primeiro é necessário criar ou ler uma lista. Caso contrário, executa a operação escolhida.

Quando o utilizador escolhe a opção `0`, o programa mostra a lista que está guardada naquele momento e apresenta uma mensagem de despedida. O ciclo termina e o programa fecha.

Por fim, se o utilizador introduzir uma opção que não existe no menu, o programa apresenta uma mensagem de erro e volta a mostrar o menu.

### Lista de resultados:
[TPC4.ipynb](https://github.com/user-attachments/files/33000590/TPC4.ipynb)
