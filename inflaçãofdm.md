# Fundamentos de Macro - Unicap - 2021
dinilson.pedroza@unicap.br

Texto apresentado em [html](https://pt.wikipedia.org/wiki/HTML) e produzido em [Markdown](https://pt.wikipedia.org/wiki/Markdown), no ambiente [Linux](https://pt.wikipedia.org/wiki/Linux).

![](/home/dinilson/Downloads/logolinux.jpg)


![](/home/dinilson/Downloads/logomark.png)




**[Ciência de dados:](https://pt.wikipedia.org/wiki/Ci%C3%AAncia_de_dados)** consiste em coletar, limpar e tratar dados para fundamentar um proposição.


# INFLAÇÃO


3 noções fundamentais sobre esse assunto:


**Inflação**
É a medida na evolução geral dos preços de bens e serviços. Geral no sentido de que vários bens e serviços são pesquisados. A lista de bens e serviços a serem pesquisados é definida em uma *Pesquisa de Orçamentos Familiares (POF)*. Através da **POF** se tem uma ideia do que as pessoas normalmente consomem, ou seja, qual é a *cesta* de bens e serviços consumida normalmente pelas brasileiras. São os itens dessa cesta que são pesquisados.

**Poder aquisitivo**
A quantidade de bens e serviços que podemos comprar com nossos salários determina o nosso *poder aquisitivo*. Ora, se os preços aumentam (inflação) e o salário continua o mesmo, perdemos poder aquisitivo.

**Índice**
A inflação é um número que sintetiza vários outros. Por exemplo, o índice de inflação de abril de 2021 foi de 0,86%. Esse número representa a evolução no preço de mais de 400 mil itens (bens e serviços). Portanto, é um número que sintetiza vários outros. Um índice.

## 1. Inflação e correção monetária

Considere o seguinte exemplo (hipotético):

### Ex.01

Em janeiro de 2000 uma casquinha de sorvete custava R$ 2,00.
Em março de 2020 a mesma casquinha custava R$ 3,50.

Qual teria sido, então, a "inflação do sorvete"?

inflação = (3,5/2) - 1) * 100 = 75%

Digamos agora que eu tenho o preço do sorvete em janeiro de 2000 e sei a inflação do período (75%). Qual seria o preço do sorvete em março de 2020?

Preço do sorvete em março 2020 = R$ 2,00 * 1,75 = R$ 3,50.

Onde 1,75 é o [multiplicador](#multiplicador) da operação.


Quando fazemos esse tipo de conta estamos *atualizando* para 03/2020 um valor de 01/2000. Atualizar um valor, portanto, e levá-lo de um período para outro.

Vamos complicar um pouco mais esse exercício.

### Ex.02

Em abril de 1987 um carro custava CZ$ 400.000,00. (Números fictícios!).
Sabendo que a inflação entre 04/87 e 02/19 foi de 1.000%, qual seria o preço do carro atualizado para fevereiro de 2019?

Num caso como este não podemos só aplicar o *multiplicador de preços* como fizemos antes.

O problema é a mudança de moeda considerada nesse exemplo hipotético. Em 04/87 a moeda era *Cruzado* e em 02/19 a moeda era *Real*.

No nosso exemplo, considere, contudo,  que CZ$ 1.000,00 = R$ 1,00, ou seja, quando se mudou a moeda, houve um corte de três zeros (para facilitar a vida das pessoas num contexto inflacionário agudo).

Logo, antes de aplicarmos o multiplicador, vamos expressar o valor de 04/87 em R$:

CZ$ 400.000,00 = R$ 400,00.

Feita a conversão, vamos agora sim, aplicar o multiplicador:

1.000% corresponde a um multiplicador de 11. Logo,

R$ 400,00 * 11 = R$ 4.400,00

Portanto, CZ$ 400,00 de abril de 1987 correspondem a R$ 4.400,00 em fevereiro de 2019. Outra maneira de dizer isso: R$ 4.400,00 é o valor de um carro de abril de 1987 a preços de fevereiro de 2019.

Atenção: tivemos dois trabalhos nessa operação: 1º convertemos os valores numa mesma moeda; 2º aplicamos a inflação ao valor de 1987.

Na práticas, as contas são mais complicadas pois aconteceram várias mudanças de moedas, como as mostradas neste [site do Banco Central](https://www.bcb.gov.br/content/acessoinformacao/museudocs/pub/SintesePadroesMonetariosBrasileiros.pdf).

Por outro lado, no [site do IBGE](https://www.ibge.gov.br/explica/inflacao.php) em que a inflação é explicada, há uma calculadora que faz esse tipo de conta usando a inflação medida pelo IPCA.

No site Banco Central há também uma [calculadora](https://www3.bcb.gov.br/CALCIDADAO/publico/exibirFormCorrecaoValores.do?method=exibirFormCorrecaoValores)  que faz esse mesmo tipo de operação, só que disponibilizando uma gama maior de índices de inflação.


### Ex.03

Vamos usar a calculadora do IBGE nessa operação.

Pergunta: O Gol é um automóvel da VW lançado em maio de 1980. Qual seria o preço daquele automóvel lançado em 1980 a preços de hoje?

Dados do problema:

Preço do Gol e julho de 1980 = Cr$ 238.612,00.

Jogando esses valores na calculadora do IBGE, observamos que o preço daquele Gol a valores de hoje seria R$ 46.198,95.

A calculadora considerou uma inflação de 53 trilhões de porcento no período!!

A propósito, assistam o video explicando o que é inflação na página indicada.

## 2. Pegando dados de inflação no SIDRA


[SIDRA](https://sidra.ibge.gov.br/home/pimpfbr/brasil)

IPCA

Relação de tabelas da pesquisa

[Tabela 1737](https://sidra.ibge.gov.br/tabela/1737)

Monte o leiaute da Tabela deixando os meses na linha (arrastando os quadrados).

Escolha a opção: IPCA - Variação mensal (% [janeiro 1980 a fevereiro 2021]): 2 de 2 casas decimais

Marque todos os meses.

Nível territorial: Brasil.

Visualizar

Download

Na janela que se abre escolha a opção CSV(BR)

Abra o arquivo salvo.

Limpe a planilha (lembre-se de tirar o rodapé).

No Calc:

Selecione as duas colunas "Mês" e "IPCA"

Inserir

Gráfico

Linha


## Multiplicadores, inflação e números índices <a name="multiplicador"></a> 

Considere:

$P_0$ = 2,00



$P_1$ = 3,50




Então, temos as seguintes denominações:

*Variação percentual (inflação)* = ((3,5/2) - 1) * 100 = 75%

*Multiplicador* = 3,5/2 = 1,75

*Número índice* = (3,5/2) = 175

Portanto, se somos informados que o número índice entre agosto de 2003 e setembro de 2004 foi 107, deduzo que a inflação no período foi de 7%.




Nome          | valor
--------------|------
Inflação (%)  | 75
Multiplicador | 1,75
Índice        | 175

## 3. Atualizando valores

Vamos aqui aprender a corrigir valores. *Por exemplo, qual salário mínimo apresentou maior poder aquisitivo, o de 1995 ou o de 2005?*

Antes de responder a essa questão, vamos entender de maneira intuitiva a conta a ser feita.

### Ex.04

Digamos que o salário mínimo em dezembro de 2005 era de R$ 600,00 e em dezembro de 2005 era de R$ 800,00. Considerando uma inflação representada pelo número índice = 170, pergunto: qual salário apresentou maior poder aquisitivo? (Notem que para facilitar as coisas usei valores de um mesmo padrão monetário e números redondos).

[Quadro negro]


Para fazer a comparação, podemos levar o valor de 1995 para 2005. Fazemos isso "jogando" a inflação no salário de 1995:

Um número índice de 170, dá uma inflação de 70% e um fator multiplicador de 1,70 (veja a Tabela acima).

Logo:


$W_{1995} * 1,70$ = R$ 1.020,00



Portanto, o poder aquisitivo do salário mínimo de 1995 permitiria comprar mais coisas que o salário mínimo de 2005, em que pese este último ter sido maior. O que aconteceu foi que o aumento no salário mínimo:


Aumento = ((800/600) - 1) * 100 = 33%


Foi menor que a inflação do período, que foi de 70%. Houve, então, perda de poder aquisitivo em nosso exemplo.

### Ex.05

Agora vamos trabalhar com números factuais. Vamos comparar o salário mínimo de dezembro de 1990 com o de março de 2021.

Os dados:

### Salários

Os valores pegamos neste [link](http://startpoint.com.br/SM.htm). 

$W_{12/1990}$ = Cr$ 8.836,82


$W_{03/2021}$ = R$ 1.100,00




### Padrões monetários

Neste [link](https://www.bcb.gov.br/content/acessoinformacao/museudocs/pub/SintesePadroesMonetariosBrasileiros.pdf) vemos que a moeda em dezembro de 1990 era o Cruzeiro (Cr$).

De lá para cá aconteceram os seguintes cortes de zeros:

Divisão por 1.000 em agosto de 1993, quando se criou o Cruzeiro Real (CR$).

Divisão por 2.750 em julho de 1994, quando se criou o Real (R$).

Logo, Cr$ 8.836,82 fica em Reais = R$ 0,003213389090909.

$W_{03/2021}$ = R$ 0,003213389090909.


## Índices de preços

Neste [link](https://sidra.ibge.gov.br/tabela/1737) do SIDRA IBGE pegamos os índices de preços baseados em dezembro de 1993 (=100).

$I_{11/1990}$ = 0,0469240627842

$I_{03/2021}$ = 5674,72

Notem que de acordo com este último número, a inflação (%) entre dezembro de 1993 e março de 2021 foi de:

5674 - 100 = 5574%!!


### Fazendo as contas:

1º vamos levar o salário de dezembro de 1990 para dezembro de 1993. (Se para números depois do período base, multiplicamos, para período anteriores, dividimos) e obtemos o seguinte **fator**:

$I_{11/1990}$/100 = 0,0469240627842 / 100 = 0,000469240627842

O salário mínimo de 12/1990 corrigido para 12/1993 fica:


R$ 0,003213389090909/0,000469240627842 = R$ 6,84806238046183


2º levamos esse último salário para março de 2021. O **fator** (multiplicador) é, então:

$I_{03/2021}$/100 = 5674,72/100 = 56,7472

O salário corrigido para 03/21 fica:

R$ 6,84806238046183 * 56,7472 = 388,608365516544

Logo, bem menor que os R$ 1.100,00. Portanto, ao longo das décadas de 90, 2000 e 2010, o salário mínimo cresceu em termos reais.


Mas atenção! Isto não quer dizer que o salário mínimo é alto hoje. Quer dizer que era ainda mais baixo em 1990.


### Dica:

Alcançaríamos o mesmo resultado se fizéssemos a seguinte (e mais simples conta):


**$W_{12/1990} * (I_{03/2021}/I_{11/1990})$**


Claro está que na fórmula acima o salário já esta em reais.

### Ex.06: Comparem o salário mínimo de julho de 1996 com o de janeiro de 2021. Dica: usem a dica.




































