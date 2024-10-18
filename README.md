# Regressao Linear Multipla
Modelo de regressão linear múltipla para empresa de marketing.

## Introdução
Este repositório contém um desafio de análise de dados e construção de um modelo de regressão linear para uma campanha de marketing. O objetivo é compreender a relação entre os investimentos em plataformas de publicidade online e o retorno de vendas, e criar um modelo preditivo.

## Contexto
Uma empresa está investindo mensalmente em plataformas de publicidade online, como Youtube, Facebook e jornais, para a prospecção de leads. Para acompanhar o desempenho desses investimentos, todos os gastos e retornos de vendas gerados são registrados. A análise visa identificar os fatores que mais impactam na geração de leads e criar um modelo de predição para estimar o retorno de vendas a partir de um investimento em publicidade.

## Base de Dados
O dataset utilizado (MKT.csv) contém as seguintes colunas:

youtube: Investimento no Youtube

facebook: Investimento no Facebook

newspaper: Investimento em jornais

sales: Valor das vendas

## Etapas do Desafio
1. **Preparação dos Dados**
Importando o dataset utilizando bibliotecas de manipulação de dados.

Explorando as informações das variáveis presentes no dataset para identificar inconsistências, como valores ausentes e dados duplicados.

2. **Análise Descritiva**
Realizando uma análise descritiva utilizando a função describe para entender a distribuição dos dados.

Foi feita as análise de tipo de dado em cada variável, os valores e a distribuição dos dados.

3. **Análise Exploratória**
Utilizando gráficos e visualizações para identificar padrões, relações e tendências entre as variáveis.

Analisando as correlações entre os dados e a distribuição dos mesmos.

4. **Modelagem**
Construindo  um modelo simples de regressão para prever o retorno de vendas a partir dos investimentos em publicidade.

Foi utilizado técnicas e bibliotecas como sklearn para a criação do modelo.

5. **Cálculo de Predição**
Aplicando o modelo de regressão construído para realizar previsões de retorno de vendas baseadas nos investimentos em marketing.

Avaliando o impacto dos diferentes níveis de investimento nas vendas, auxiliando na tomada de decisões.

## Avaliação do modedelo
Análise Descritiva: Uso da função describe para analisar a distribuição do dataset. (25 pontos)

Análise Exploratória: Análise das variáveis para identificar correlações relevantes. (25 pontos)

Modelagem: Teste e treino do modelo de regressão para garantir previsões precisas. (25 pontos)

Cálculo de Predição: Realização do cálculo do coeficiente de determinação (r²) e utilização para fazer predições de vendas. (25 pontos)

**CONCLUSÃO**

Com a respectiva modelagem dos dados e treino da nossa base conseguimos chegar ao nosso objetibo e determinar que:


1.   Conseguimos um valor de coeficiente de determinação, o r², de 87,29%.
2.   Comparando o gráfico de Valores reais vs Predição, vimos que nossa predição de valores é bastante confiavel para estimar possiveis retornos de vendas em calculos posteriores que podem ser gerados a partir de determinados investimentos.
