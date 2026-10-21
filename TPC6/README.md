# TPC6_2026
### Autor: Maria Surreira, a112341,<img width="200" height="250" alt="WhatsApp Image 2026-09-01 at 14 07 13" src="https://github.com/user-attachments/assets/386accd6-8ae9-406d-964b-a33829912ffc" />


## Resumo:

#### 1. Objetivo do projeto

Este projeto permite consultar, guardar e analisar dados meteorológicos através de um menu interativo desenvolvido em Python.

Cada registo da tabela meteorológica contém quatro elementos:

Data: ano, mês e dia.

Temperatura mínima: temperatura mínima registada nesse dia.

Temperatura máxima: temperatura máxima registada nesse dia.

Precipitação: quantidade de chuva registada nesse dia.

O programa permite realizar cálculos estatísticos, consultar dados, guardar e carregar ficheiros e criar gráficos com recurso à biblioteca matplotlib.

#### 2. Explicação das funções

##### menu()

Apresenta as opções disponíveis no programa, permitindo ao utilizador escolher a operação que pretende realizar.

##### medias(tabMeteo)

Calcula a temperatura média de cada dia, somando a temperatura mínima e a máxima e dividindo o resultado por dois. Devolve uma lista com a data e a respetiva temperatura média.

##### guardaTabMeteo(t, fnome)

Guarda os dados da tabela meteorológica num ficheiro de texto. Recebe a tabela e o nome do ficheiro, escrevendo cada registo numa linha.

##### carregaTabMeteo(fnome)

Lê os dados de um ficheiro de texto e converte-os novamente para o formato de tabela utilizado pelo programa, transformando a data numa tupla e as temperaturas e a precipitação em valores numéricos.

##### minMin(tabMeteo)

Percorre a tabela e identifica a temperatura mínima mais baixa entre todos os registos.

##### amplTerm(tabMeteo)

Calcula a amplitude térmica diária, subtraindo a temperatura mínima à temperatura máxima. Devolve uma lista com a data e a respetiva amplitude térmica.

##### maxChuva(tabMeteo)

Procura o registo com maior quantidade de precipitação e devolve a data correspondente e o valor máximo encontrado.

##### diasChuvosos(tabMeteo, p)

Identifica os dias em que a precipitação é superior ao limite p introduzido pelo utilizador. Devolve uma lista com as datas e os valores de precipitação desses dias.

##### maxPeriodoCalor(tabMeteo, p)

Calcula o número máximo de dias consecutivos em que a precipitação é inferior ao limite p. Utiliza duas variáveis para contar os dias consecutivos e guardar o maior período encontrado.

##### grafTabMeteo(t)

Cria três gráficos utilizando a biblioteca matplotlib: um para as temperaturas mínimas, outro para as temperaturas máximas e outro para a precipitação. As datas são utilizadas como eixo horizontal e os valores meteorológicos como eixo vertical.

#### 3. Funcionamento do programa

O programa começa por apresentar uma tabela meteorológica com dados de exemplo. Em seguida, mostra um menu que permite selecionar uma das operações disponíveis.

As instruções condicionais if, elif e else permitem executar a função correspondente à opção escolhida. O ciclo while mantém o programa em funcionamento até o utilizador selecionar a opção 0, que termina a execução.

#### 4. Bibliotecas utilizadas

matplotlib.pyplot: utilizada para criar e apresentar os gráficos meteorológicos.

As restantes funcionalidades são desenvolvidas com recursos nativos do Python, como listas, tuplos, ciclos, condições e operações com ficheiros.

#### 5. Conclusão

Este projeto permite aplicar conceitos fundamentais de programação em Python, como a criação de funções, a manipulação de listas e tuplos, a leitura e escrita de ficheiros, a utilização de ciclos e condições e a representação gráfica de dados.

O objetivo principal é facilitar a análise de dados meteorológicos de forma organizada e interativa.

## Lista de Resultados:[TPC6.ipynb](https://github.com/user-attachments/files/33778172/TPC6.ipynb)
