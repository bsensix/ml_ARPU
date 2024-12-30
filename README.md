# ml_ARPU
Modelo de machine learning para ofertar cupons de desconto a diferentes perfis de clientes.

# Problematica

O problema consiste em desenvolver um modelo de recomendação para ofertar cupons de desconto a diferentes perfis de clientes, utilizando dados de transações, perfis de clientes e ofertas de cupons. O objetivo é aumentar a taxa de aceitação das ofertas e, consequentemente, a receita.

## Estrutura do Repositório

- `data`
  - `offers.json`: Contém informações sobre as ofertas de cupons, incluindo canais, valor mínimo, duração, tipo de oferta e valor de desconto.
  - `profile.json`: Contém informações sobre os perfis dos clientes.
  - `transactions.json`: Contém informações sobre as transações realizadas pelos clientes.

- `models`
  - `-ifooddesafio-2.ipynb`: Notebook Jupyter com a análise e desenvolvimento do modelo de recomendação.
  - `modelo-de-recomendacao.ipynb`: Notebook Jupyter com a análise e desenvolvimento do modelo de recomendação.
  

## Metodologia

1. **Análise Exploratória de Dados (EDA)**:
   - Carregamento e visualização dos dados.
   - Análise de correlação entre as variáveis.
   - Limpeza e preparação dos dados.

2. **Desenvolvimento do Modelo**:
   - Separação dos dados em conjuntos de treino e teste.
   - Treinamento do modelo.
   - Avaliação dos modelos utilizando métricas como acurácia, F1 Score e AUC.

3. **Avaliação**:
   - Identificação dos principais fatores que afetam a conversão.
   - Cálculo da receita esperada por cliente e receita projetada.
