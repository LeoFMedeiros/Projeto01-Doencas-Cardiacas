# Projeto01-Doenças-Cardíacas

## Previsões de Doenças Cardíacas

![](img_banner.jpg)

# Problema de Negócio

As doenças cardiovasculares (DCV) são a causa número um de mortes no planeta. Os fatores de risco são variados: desde fumo, diabetes, hipertensão e obesidade, até poluição do ar e condições raras e negligenciadas. 

<<<<<<< HEAD
O seguinte trabalho tem o objetivo de estudar uma base de dados que contém 70 mil pessoas, tendo como parâmetros: idade, altura, peso, sexo, pressão sistólica, entre outras caractríscticas. A partir dessa análise, vamos fazer um estudo de insights para procurar fatores que aumentem as chances de se encontrar de forma preditiva pessoas mais propensas de terem doenças cardíacas. Além disso, o foco principal é a produção de um modelo de Machine Learning que, por meio de certas descrições, conseguimos 'prever' se ela é uma pessoa com risco de se ter doenças. 

Portanto, como a detecção de doenças é feita por meio de exames e só há duas saídas possíveis (doente ou saudável), vamos criar uma IA (inteligência artificial) que, com alguns parâmetros, conseguiremos obter sua opinião. Caso sejam obtidos ótimos resultados de precisão e acertos de inúmeros casos, vamos alcançar um ganho no tempo de processo(atendimento até o resultado do exame), e, assim, também será possível diminuir os gastos com a realização de exames, devido aos auxílios na tomada de decisão.
=======
O seguinte trabalho tem o objetivo de estudar uma base de dados que contem 70 mil pessoas, que possuem: idade, altura, peso, sexo, pressão sistólica, entre outras caractríscticas. Com ela vamos fazer um estudo de insights para procurar fatores que aumentem as chances de se encontrar de forma preditiva pessoas mais propensas de terem doenças cardíacas. Além disso, o foco principal é a produção de um modelo de Machine Learning que dadas certas descrições conseguimos 'prever' se ela é uma pessoa com risco de se ter doenças. 

Portanto, como a detecção de doenças é feita por meio de exames e so temos duas saídas possíveis (doente ou saudável), vamos criar uma IA (inteligência artificial) que com alguns parâmetros conseguimos obter sua opinião. Caso sejam obtido ótimos resultados de precisão e acertos de inúmeros casos vamos se ter um ganho no tempo de processo(atendimento até o resultado do exame), e assim, também conseguimos diminuir os gastos com a realização de exames por se ter auxílios na tomada de decisão.
>>>>>>> c21efa9d8582ddd1d2afff0fef7ad6f70f744c88

-Link da competição: https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset

# Estratégia de Solução

**1° Etapa)** Descrição dos dados: Procurar entender as métricas e os valores encontrados na base de dados.

**2° Etapa)** Criação de Novas Features: Criar ou derivar características da própria base de dados para melhor descrever o fenômeno.

**3° Etapa)** Filtragem dos dados: Vão ser tratados linhas que não correspondem ao problema de negócios, valores faltantes e anomalias dos dados.

**4° Etapa)** Análise Exploratória: Procurar insights para compreender melhor o impacto de cada variável. 

**5° Etapa)** Preparação de Dados: Prepare os dados para que os modelos de Machine Learning possam aprender o comportamento específico.

**6° Etapa)** Modelagem de Machine Learning: treinamento do modelos de Machine Learning. 

# 4 Principais Insights de Dados

- 1°) Há mais casos de doenças cardíacas para quem fuma do que para quem não fuma.

**FALSO** Conforme a base de dados mostra, não existe diferença significativa nessa afirmação 

- 2°) Pessoas com mais peso são mais propensas a terem casos de doenças cardíacas. 

**VERDADEIRO** A medida que as amostras de pesos aumentam é mais comum encontrar pessoas doentes.

- 3°) Pessoas com mais velhas são mais propensas a terem casos de doenças cardíaca

**VERDADEIRO** é notado uma crescente na quantidade pessoas doentes com mais de 50 anos.

- 4°) Há mais casos de doenças cardíacas para quem bebem do que para quem não bebem.

**FALSO** Conforme a base de dados mostra, não existe diferença significativa nessa afirmação.

# Desempenho do Modelo de Aprendizado de Máquina

O algoritmo com melhor performace foi o **LightGBM**

#### Precisão, Recall, F1 e Accuracy

Essas são as métricas obtidas do conjunto de teste.

| precision | recall  | f1\-score | accuracy |
|-----------|---------|-----------|----------|
| 0\.7578   | 0\.6840 | 0\.7190   | 0\.7343  |


# Resultados de Negócios

Utilizando o modelo proposto, vamos conseguir acertar 73% dos casos que irão aparecer, assim, quando um modelo sugerir que tal pessoa possua doença conseguiremos agilizar todo o seu processo e pular etapas para o seu melhor atendimento. Também, vamos conseguir diminuir a quantidade de exames realizados por ter uma modelo com uma capacidade previsão boa, portanto, reduzindo a quantidade de exames realizados. 