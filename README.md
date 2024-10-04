# Análise do Bank Marketing Dataset

## Descrição do Projeto

Este projeto realiza uma análise do Bank Marketing Dataset, visando prever se um cliente irá subscrever um depósito a prazo com base em suas características pessoais e de interação com o banco. O objetivo é identificar os fatores que influenciam a decisão dos clientes e desenvolver um modelo preditivo usando regressão logística.

## Tabela de Conteúdos

- [Motivação](#motivação)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Conjunto de Dados](#conjunto-de-dados)
- [Análise Exploratória](#análise-exploratória)
- [Pré-processamento de Dados](#pré-processamento-de-dados)
- [Modelagem](#modelagem)
- [Resultados](#resultados)
- [Considerações Finais](#considerações-finais)

## Motivação

A captação e retenção de clientes é essencial para o sucesso de instituições financeiras. A análise deste dataset permite entender melhor o comportamento dos clientes em relação às campanhas de marketing e desenvolver estratégias mais eficazes para engajá-los.

## Tecnologias Utilizadas

- **Python**
- **Pandas**: Manipulação de dados
- **Matplotlib**: Visualização de dados
- **Seaborn**: Visualização de dados
- **Scikit-learn**: Algoritmos de aprendizado de máquina

## Conjunto de Dados

O conjunto de dados utilizado neste projeto está disponível no [Kaggle](https://www.kaggle.com/uciml/bank-marketing). Ele contém informações sobre clientes, campanhas de marketing e se o cliente subscreveu ou não um depósito a prazo.

## Análise Exploratória

- Visualização da distribuição de subscrições (variável alvo).
- Análise de características demográficas e financeiras dos clientes.
- Identificação de valores ausentes e tratamento.

## Pré-processamento de Dados
- Conversão de variáveis categóricas em numéricas usando one-hot encoding.
- Tratamento de valores ausentes.
- Normalização das variáveis, se necessário.

## Modelagem
- Divisão do conjunto de dados em treino e teste.
- Treinamento de um modelo preditivo (ex.: Regressão Logística).
- Avaliação do modelo usando matriz de confusão, acurácia, precisão e recall.

## Resultados
- Apresentação da matriz de confusão.
- Discussão sobre a importância das variáveis que influenciam a decisão de subscrição.
- Insights sobre o comportamento dos clientes e recomendações.

## Considerações Finais
A análise do Bank Marketing Dataset oferece insights valiosos sobre o comportamento dos clientes em relação às campanhas de marketing. Este projeto é um passo inicial na aplicação de técnicas de ciência de dados para resolver problemas do mundo real e aprimorar estratégias de marketing.


