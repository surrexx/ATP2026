[TPC7.ipynb](https://github.com/user-attachments/files/34215575/TPC7.ipynb)# TPC7_2026
### Autor: Maria Surreira, a112341,<img width="200" height="250" alt="WhatsApp Image 2026-09-01 at 14 07 13" src="https://github.com/user-attachments/assets/386accd6-8ae9-406d-964b-a33829912ffc" />


## Resumo
#### 1. Listas em Compreensão

Nesta primeira parte do trabalho são realizadas três operações com listas.

- **ncomuns:** Recebe duas listas e devolve uma nova lista com os elementos que não existem em ambas.
- **Seleção de palavras:** Utiliza uma lista em compreensão para selecionar as palavras de um texto com mais de três letras. É utilizado o método `split()` para dividir o texto em palavras e `len()` para calcular o comprimento de cada palavra.
- **Pares de índices e valores:** Cria uma lista de pares constituídos pelo índice e pelo respetivo valor de cada elemento de uma lista.

#### 2. Operações com Strings e Números

Nesta parte são desenvolvidas quatro funções:

- **strCount:** Conta quantas vezes uma substring aparece numa string, sem permitir sobreposições. Utiliza um ciclo `while` para percorrer a string e comparar os elementos.
- **produtoM3:** Recebe uma lista de números inteiros positivos, ordena-os por ordem crescente através de `sorted()` e calcula o produto dos três menores elementos.
- **somaUmaVez:** Calcula a soma dos algarismos de um número inteiro, utilizando os operadores `%` e `//`.
- **reduxInt:** Utiliza repetidamente a função `somaUmaVez` até obter um número com apenas um algarismo.
- **myIndexOf:** Procura uma substring dentro de uma string e devolve a posição da primeira ocorrência. Caso não encontre, devolve `-1`.

#### 3. A Rede Social – MyFaceBook

Nesta última parte do trabalho é criada uma estrutura de dados que representa uma pequena rede social chamada `MyFaceBook`.

A estrutura é constituída por uma lista de dicionários. Cada dicionário representa uma publicação e contém:
- Identificador (`id`);
- Conteúdo da publicação;
- Autor;
- Data de criação;
- Lista de comentários.

Cada comentário é também representado por um dicionário, contendo o texto do comentário e o respetivo autor.

Foram desenvolvidas as seguintes funções:

- **quantosPost:** Conta o número total de publicações existentes na rede social, utilizando `len()`.
- **postsAutor:** Procura e devolve todas as publicações realizadas por um determinado autor.
- **autores:** Percorre as publicações, recolhe os nomes dos autores e organiza-os por ordem alfabética através de `sorted()`.
- **insPost:** Permite adicionar uma nova publicação à rede social, criando um dicionário com os respetivos dados e atribuindo-lhe um novo identificador.
- **numeroid:** Calcula o identificador que será atribuído à próxima publicação.
- **remPost:** Procura uma publicação através do seu identificador e remove-a da rede social.
- **postsPorAutor:** Organiza as publicações num dicionário, agrupando-as pelo respetivo autor.
- **comentadoPor:** Percorre as publicações e os seus comentários, procurando aqueles que foram escritos por um determinado autor.

#### 4. Conclusão

Ao longo deste trabalho foram aplicados vários conceitos fundamentais da linguagem Python, nomeadamente listas, listas em compreensão, strings, ciclos `for` e `while`, condições `if`, funções e dicionários.

Foram também utilizadas operações de pesquisa, ordenação, inserção e remoção de elementos.

A última parte do trabalho permitiu aplicar estes conhecimentos na criação de uma pequena rede social, trabalhando com publicações, autores e comentários.

Este trabalho contribuiu para desenvolver a capacidade de resolver problemas através da programação e de manipular diferentes estruturas de dados em Python.

## Listas de Resultados: [TPC7.ipynb](https://github.com/user-attachments/files/34215590/TPC7.ipynb)



