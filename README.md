**Mineração de Dados — Clusterização K-Means e Regras de Associação**

Este projeto realiza uma análise exploratória e preditiva utilizando técnicas de Mineração de Dados para identificar padrões relacionados às taxas de mortalidade, óbitos e internações nos estados brasileiros.

A base de dados contém registros por estado e faixa etária, que foram tratados, consolidados e analisados por meio de duas técnicas principais:

1. Objetivos do Projeto

Agrupar estados brasileiros com características semelhantes usando K-Means

Identificar padrões e relações frequentes entre variáveis usando Apriori

Verificar se algum estado apresenta comportamento fora da curva

Compreender diferenças regionais nos indicadores de saúde

2. Metodologia Resumida

Limpeza e padronização dos dados

Agregação das taxas por estado

Normalização dos valores numéricos

Clusterização com K-Means (K=3)

Transformação dos dados em faixas categóricas

Geração de regras de associação com Apriori

3. Principais Resultados

Identificação de 3 clusters distintos de estados

O estado de São Paulo foi classificado isoladamente em um cluster devido aos valores muito altos de internações e óbitos (outlier)

Relações frequentes mostraram correlação entre mortalidade, óbitos e internações

Estados do Norte e Nordeste concentraram o grupo com taxas mais elevadas

4. Tecnologias Utilizadas

Python

Pandas

Scikit-Learn

MLxtend

Matplotlib
