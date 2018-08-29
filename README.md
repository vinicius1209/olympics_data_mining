# Olympics Data Mining

## Questões:

1) Qual/Quais países irão ter o maior número de medalhas nas proximas olimpiada de verão 

~~2) O clima quente influencia ou não no número de medalhas dos países quentes quando comparado ao clima frio?~~

3) O quanto a altura influencia no numero de medalhas na modalidade Atletismo?

4) Atletas dos países sedes tem maiores chances de ganhar mais medalhas?

~~5) Se o atleta participou de mais de uma olimpiada, o seu numero de medalhas aumentou? O numero de medalhas aumenta conforme o numero de participação nas olimpiadas?~~

6) Descobrir tendencias de medalhas por esporte para cada país

7) Paises com mais participantes tem mais medalhas conquistadas.

## Relatório:

1) Escolhemos 5 perguntas com base no dataSet dos jogos de verão
2) Retiramos a coluna "Games", que basicamente concatenava o ano com o tipo da olimpiada(summer)
3) Fizemos um levantamento do numero de ganhadores de medalhas versus não ganhadores de nenhuma medalha
4) Análise de questões (Quais utilizar para os estudos)

## Pré Processamento e limpeza de dados

1) Retiramos a coluna "Name" notamos que não faria sentido mante-la;

2) Em "Age" identificamos os valores nulos e preenchemos com o valor médio, mantendo um valor inteiro. A média obtida foi 25.64, e foi arredondado para cima (26);

3) Em "Height" alteramos os valores nulos e preenchemos com o valor médio (175.4), arredondamos para  175;

4) Em "Weight" alteramos os valores nulos e preenchemos com o valor médio (70.6), arredondamos para 70.5, mantendo o padrão dos outros dados. Eliminamos valores outliers, de pesos como 733.33.33 , 603.33.33.

5) Em "Team", foi utilizamos as siglas para definir os países. 

6) Para simbolizar o país sede, também mantemos as siglas.

7) Para "Medals", utilizamos valores booleanos, ou o atleta ganhou ou não ganhou a prova. Tiramos dados como "Bronze", "Prata" e "Ouro"

8) Retiramos a coluna "Games", que basicamente concatenava o ano com o tipo da olimpiada(summer)
