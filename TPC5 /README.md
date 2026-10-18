# TPC5_2026
### Autor: Maria Surreira, a112341,<img width="200" height="250" alt="WhatsApp Image 2026-09-01 at 14 07 13" src="https://github.com/user-attachments/assets/386accd6-8ae9-406d-964b-a33829912ffc" />



## Resumo:
#### Descrição:
Esta aplicação, desenvolvida em Python, permite gerir uma turma de alunos através de um menu interativo no terminal. 
O utilizador escolhe uma operação no menu e a aplicação executa-a. No fim de cada operação, o menu é apresentado novamente e é pedida uma nova opção, até o utilizador decidir sair.

#### Estrutura de dados:
Cada aluno é representado por um tuplo com o seguinte formato:
aluno = (nome, id, [notaTPC, notaProj, notaTeste])
nome: nome do aluno (string);
id: número de identificação do aluno (inteiro);
[notaTPC, notaProj, notaTeste]: lista com as três notas do aluno (valores decimais).
A turma é uma lista de alunos:
turma = [aluno1, aluno2, aluno3, ...]

#### Menu de operações:
Quando a aplicação arranca, apresenta o seguinte menu:

1: Criar uma turma
2: Inserir um aluno na turma
3: Listar a turma
4: Consultar um aluno por id
8: Guardar a turma em ficheiro
9: Carregar uma turma de um ficheiro
0: Sair da aplicação

#### Funcionamento de cada operação: 
Opção 1 (Criar uma turma): cria uma turma vazia, ou seja, uma lista sem alunos. Se já existia uma turma em memória, esta é substituída pela nova.

Opção 2 (Inserir um aluno na turma): pede ao utilizador o nome, o id e as três notas (TPC, projeto e teste). Com esses dados, constrói o tuplo do aluno e adiciona-o à turma.

Opção 3 (Listar a turma): mostra no ecrã todos os alunos da turma, um por linha, com o nome, o id e as respetivas notas.

Opção 4 (Consultar um aluno por id): pede ao utilizador um id e procura na turma o aluno correspondente. Se existir, mostra os seus dados. Caso contrário, informa que o aluno não foi encontrado.

Opção 8 (Guardar a turma em ficheiro): pede o nome do ficheiro e escreve nele a turma, com um aluno por linha, no formato nome | id | notaTPC#notaProj#notaTeste. Por exemplo, uma linha do ficheiro pode ser: Ana | 101 | 15.0#17.0#14.0

Opção 9 (Carregar uma turma de um ficheiro): pede o nome do ficheiro, lê-o linha a linha e reconstrói a turma em memória, convertendo o id para inteiro e as notas para decimais. A turma carregada substitui a que estava em memória.

Opção 0 (Sair da aplicação): termina a execução do programa.

## Lista de Resultados:
[TPC5.ipynb](https://github.com/user-attachments/files/33626849/TPC5.ipynb)
