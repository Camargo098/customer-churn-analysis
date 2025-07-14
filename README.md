# Previsão de Churn em Clientes Bancários #

Este projeto tem como objetivo prever a probabilidade de churn (evasão) de cliente de um banco, com base em caracteristicas demográficas, comportamentais e financeiras. A metodologia adotada segue o frmework CRISP-DM. amplamente utilizado em projetos de ciência de dados.

## Objetivo do Projeto ##
Construir um modelo de machine learning capz de prever a probabilidade de um cliente encerrar seu relacionamento com o banco, auxiliando a àrea de retenção proativa de clientes e redução da taxa de churn.

## Estrutura de Diretório ##

customer-churn-prediction/
|
|__  Data/
|   |--Raw/customer-churn-prediction/
│
├── data/                      # Base de dados original e tratada
│   ├── raw/                   # Dados brutos
│   └── processed/             # Dados pós-tratamento e engenharia de atributos
│
├── eda/                       # Notebooks e scripts de análise exploratória
│
├── models/                    # Treinamento, comparação e avaliação de modelos
│
├── outputs/                   # Imagens, gráficos e resultados finais
│
├── utils/                     # Funções auxiliares e scripts de suporte
│
│
├── README.md                 
├── requirements.txt           # Bibliotecas necessárias para reproduzir o projeto
└── churn_prediction.ipynb     # Notebook principal do projeto

## Metodologia (CRIP-DM)
1. Entendimento do Negócio
