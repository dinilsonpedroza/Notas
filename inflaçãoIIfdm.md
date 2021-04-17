# MANUAL - ATUALIZANDO VALORES (complementando arquivo anterior)
Professor Dinilson Pedroza Júnior


dinilson.pedroza@unicap.br

Texto escrito em Markdown, em um ambiente Linux.

***

Considere a seguinte pergunta:


Qual salário é mais valioso (no sentido de comprar mais coisas, de *poder aquisitivo*)?

R$ 1.000,00 em janeiro de 1995 ou R$ 1.000,00 em março de 2021?

Claro que mil reais compravam mais coisas em 1995 que em 2021. Mas o que diferencia os dois valores? A *inflação*.

Vamos aqui aprender a precisar, em números, a diferença entre esses dois valores. Para fazer essas contas precisamos de uma medida da inflação entre esses duas datas.

## Por exemplo.

Digamos que a inflação entre as duas datas tenha sido de 100%.

Para facilitar nossa compreensão, vamos imaginar que R$ 1.000,00 em janeiro de 1995 nos permitia comprar 50 pizzas (ou seja, cada pizza custava R$ 20,00, números hipotéticos!).

Ora, se os preços subiram 100%, isso quer dizer que cada pizza passou a valer R$ 40,00 em março de 2021.

***

## Lembrete:

Inflação = 100%

Multiplicador = 2

Número índice = 200

***


Logo, por causa da inflação, R$ 1.000,00 só permitem comprar 25 pizzas em março de 2021. Ou seja, o poder aquisitivo do salário caiu pela metade. Culpada? A inflação, claro.


## Atualizando valores

Vamos atualizar o salário de 1995 para março de 2021 e compará-lo com o pago em março de 2021. Fazemos isso *jogando* a inflação do período (número índice = 200) no salário de 1995. Vamos fazer as contas trabalhando com o *número índice*, pois é assim que a inflação é normalmente divulgada (ver lembrete acima).


**Objetivo:**

Queremos expressar o salário de 1995 "a preços" de 2021. Trazer o valor de janeiro de 1995 para março de 2021. É comum chamar esse resultado de salário real:

$WR_{95/21}$ [salário real de janeiro de 95 a preços de março de 2021]


***

## Lembrete:

Salário real = salário corrigido pela inflação

Salário nominal = salário sem correção de inflação



***

## Dados:

$W_{01/1995}$ = R$ 1.000,00 [salário nominal de janeiro de 1995]

$W_{03/2021}$ = R$ 1.000,00 [salário nominal de março de 2021]

$I_{03/21}$ = 200 [índice de preços de março de 2021, base 01/95 = 100]

## Contas:

$WR_{95/21} = W_{01/1995} * \frac{I_{03/21}}{100}$

 

Ou seja,

2.000 = 1.000,00 * 200/100 = 1.000,00 * 2

## Comparação

Fica evidente que o salário de janeiro de 1995 "a preços" de março de 2021 ($WR_{95/21}$ = R$ 2.000,00) >  salário de março de 1995 ($W_{03/2021}$ = R$ 1.000,00). Ou seja, $W_{01/1995}$ tinha mais poder aquisitivo que $W_{03/2021}$.

***

 
## Índices de períodos anteriores ao período base

No exercício anterior, fica subtendido que o índice de preços do período inicial é igual a 100. A inflação é contada a partir desse período inicial, logo

$I_{01/95} = 100$


Logo,

Inflação = 0% (a inflação passa a contar dessa data)

Multiplicador = 1

## Contando para frente:

$I_{02/95} = 107$


Logo,

Inflação = 7%

Multiplicador = 1,07

## Períodos anteriores:


Se,

$I_{12/94} = 90$ (números hipotéticos!)

Multiplicador = 0,90

Portanto, o que era R$ 1.000,00 em janeiro de 1995, valia:

R$ 1.000,00 x 0,90 = R$ 900,00 em dezembro de 1994.

Por outro lado, R$ 900,00 em 12/94 vale:

R$ 900,00/0,9 = R$ 1.000,00, em janeiro de 1995.

***


## Nota técnica:

Agora, se algo custava R$ 900,00 em 12/94 e passou a custar R$1.000,00 em 01/95, a variação de preços foi de (em %):


(1.000,00 - 900,00)/900,00 = 11,11%

***


Considere que a inflação entre 01/80 e 01/95 foi muito, muito alta. Neste caso, o índice de janeiro de 1980 poderia ser algo do tipo:

$I_{01/80} = 0,634$ (atenção, este é o número índice e não a inflação em termos percentuais).



Portanto, R$ 1,00 em 01/80 valeria:

R$ 1,00 / (0,634/100) = 1,00/0,00634 = R$ 157,73


***


Exercício: se o salário mínimo fosse de R$ 5,00 em 01/80, quando valeria em 03/21?

Vamos, primeiro trazer o salário de 01/80 para 01/95 e depois jogar o valor resultante para 03/21.

### Dados:

$W_{01/80} = R\$ 5,00$

$I_{01/80} = 0,634$

$I_{03/21} = 200$


**1º**


R$ 5,00/(0,634/100) = R$ 788,64 [salário de 01/80 a preços de 01/95]

**2º**

R$ 788,64 * (200/100) = R$ 1.577,29 [salário de 01/80 a preços de 03/21]


Poderíamos ter feito de uma maneira mais direta:

R$ 5,00 * 100/0,634 * 200/100 = R$ 5,00 * (200/0,634) = R$ 1.577,29


***

## Em fórmulas:


$WR_{80/21} = W_{01/80}*\frac{100}{I_{01/80}}*\frac{I_{03/21}}{100}$


**$WR_{80/21} = W_{01/80} * \frac{I_{03/21}}{I_{01/80}}$**

Onde:

$WR_{80/21}$ = salário real de janeiro de 1980 (a preços de março de 2021)

$W_{01/80}$ = salário nominal de janeiro de 1980

$I_{03/21}$ = índice de preços de março de 2021 (contando a partir de 01/1995)

$I_{01/80}$ = índice de preços de janeiro de 1980 (tendo como referência 01/95)

**Atenção!** Esta última fórmula deixa a conta muito fácil.




















