# Modelo Preditivo para Previsão de Custos Médicos de Seguro de Saúde

Este projeto tem como objetivo desenvolver um modelo preditivo de regressão para prever o valor dos custos médicos individuais cobrados por seguros de saúde, com base em variáveis demográficas e comportamentais.

## Descrição do Projeto

O desafio proposto envolve a criação de um modelo capaz de prever os encargos médicos a partir de características como:

- **Idade**
- **Gênero**
- **Índice de Massa Corporal (IMC)**
- **Número de filhos**
- **Status de fumante**
- **Região**

A base de dados utilizada inclui registros similares ao seguinte exemplo:
idade, gênero, imc, filhos, fumante, região, encargos
56, feminino, 29.77, 2, sim, sudoeste, 31109.88
46, masculino, 25.85, 1, não, nordeste, 26650.70
32, masculino, 23.01, 0, não, sudoeste, 21459.03


### Etapas do Projeto

1. **Exploração de Dados**
   - Carregamento da base de dados e análise exploratória.
   - Estatísticas descritivas e visualização das distribuições.

2. **Pré-processamento de Dados**
   - Limpeza dos dados (tratamento de valores ausentes, se necessário).
   - Conversão de variáveis categóricas em formatos adequados para modelagem.

3. **Modelagem**
   - Construção de um modelo de regressão (ex.: Regressão Linear, Árvores de Decisão).
   - Divisão do conjunto de dados em treinamento e teste.

4. **Treinamento e Avaliação**
   - Treinamento do modelo com o conjunto de treinamento.
   - Avaliação utilizando métricas estatísticas como p-value e intervalos de confiança.

5. **Validação e Resultados**
   - Visualização dos resultados (gráficos de previsões vs. valores reais).
   - Relatório detalhado com insights, análise dos resultados e validação estatística.

### Objetivo

O objetivo é construir um modelo confiável para prever os custos médicos individuais, proporcionando uma base para análises financeiras e de seguros.

## Como Executar

1. Clone este repositório.
2. Execute o script de análise e predição dos custos médicos.
