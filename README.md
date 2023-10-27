# Stroke Prediction
 Projeto de Machine Learning I - Data Science - Santander Coders 2023 - AdaTech


### **Descrição**

Este notebook contém a análise exploratória proposta pelo projeto do módulo de Técnicas de programação I.

O objetivo deste projeto é aplicar técnicas de Machine Learning para determinar se o sujeito vai ter ou não avc a partir de uma base de dados fornecida. O conjunto de dados utilizado para este projeto é "Stroke Prediction Dataset", disponível no Kaggle: https://www.kaggle.com/competitions/playground-series-s3e2/data?select=train.csv.

Análise do Dataset:

Exploração inicial do conjunto de dados para entender suas características.
Identificação das variáveis relevantes para o problema de determinar o "Stroke".
Tratamento de dados ausentes ou inconsistentes, se necessário.

Escolha dos Algoritmos:

É necessário escolher no mínimo três algoritmos para aplicar ao problema de predição de AVC.
Alguns exemplos de algoritmos que podem ser escolhidos: Árvore de Decisão, Random Forest, KNN, MLP, Regressão Linear ou Regressão Logística.
Deve haver justificativa para a escolha do(s) algoritmo(s) com base na adequação dos algoritmos para o problema em questão.

Amostragem de Dados:

Qualquer técnica de amostragem de dados pode ser utilizada para preparar o conjunto de treinamento e teste.
Exemplos de técnicas de amostragem incluem divisão aleatória, validação cruzada, bootstrap ou leave-one-out.
A escolha da técnica de amostragem deve ser explicada e justificada.

Implementação:

A implementação do projeto deve ser feita utilizando a linguagem de programação Python.
O pacote obrigatório a ser utilizado é o scikit-learn (sklearn), que oferece uma ampla variedade de algoritmos de Machine Learning.
Os demais pacotes utilizados ficam a critério dos alunos, podendo escolher livremente.
O ambiente de execução do script python pode ser escolhido livremente (Google Colab, Jupyter Notebook, local...)

Avaliação e Comparação dos Modelos:

Deve haver treinamento e teste para os modelos escolhidos utilizando os dados amostrados.
Os modelos devem ser avaliados com base em métricas adequadas para problemas de classificação, como acurácia, precisão, recall e F1-score.
Os resultados dos modelos devem ser comparados e discutidos, identificando qual apresenta o melhor desempenho na tarefa de determinar a classe.

Apresentação dos Resultados:

Os alunos devem preparar uma apresentação final (podem escolher livremente como fazê-la) que inclua uma descrição do projeto, as etapas realizadas, os algoritmos escolhidos, os resultados obtidos e as conclusões alcançadas.
É importante destacar os desafios encontrados durante o projeto e possíveis melhorias ou próximos passos que podem ser realizados.
<br>

## ⚙️Preparação do Ambiente

### **Conjunto de dados**

*Disponíveis no diretório `datasets`.*

Para fazer esta análise exploratória, utilizamos os dados da ANP (Agência Nacional do Petróleo, Gás Natural e Biocombustíveis do Brasil), contendo a série histórica dos preços dos combustíves de 2013 a 2023 e a série histórica do IPCA(Índice Nacional de Preços ao Consumidor Amplo) disponibilizada pelo IBGE(Instituto Brasileiro de Geografia e Estatística)

 >Obs.:Os arquivos cujos tamanhos excedem 100Mb estão compactados. Caso deseje clonar este repositório, será necessário descompactar estes arquivos  dentro do diretório`datasets`.

### **Bibliotecas**

Este notebook foi desenvolvido em Jupiter e utiliza as bibliotecas abaixo:

```
 os
 numpy as np
 pandas as pd
 openpyxl 
 plotly.express as px
 plotly.io as pio
 matplotlib.pyplot as plt
 seaborn as sns

 ```

Para instalá-las, caso não estejam, utilize o comando:

```sh
 pip install -nome da biblioteca-
```

## ⚒️Passo a Passo

1. Obtenção dos dados;
1. Compreensão dos dados;
1. Carregamento dos dados;
1. Limpeza e tratamento dos dados;
1. Montagem dos dados para análise;
1. Exploração dos dados.

>O detalhamento de cada etapa, está comentado no notebook.

## 👨‍💻Autores

Ana Zanetti:  
https://github.com/anazanetti  

Mauro Domingues:  
https://github.com/maurodomingues  

