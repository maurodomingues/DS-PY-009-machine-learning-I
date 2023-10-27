# Stroke Prediction
 Projeto de Machine Learning I - Data Science - Santander Coders 2023 - AdaTech


### **Descrição**

O objetivo deste projeto é aplicar técnicas de Machine Learning para determinar se o sujeito vai ter ou não avc a partir do conjunto de dados "Stroke Prediction Dataset", disponível no Kaggle: https://www.kaggle.com/competitions/playground-series-s3e2/data?select=train.csv.

Análise do Dataset:

1. Exploração inicial do conjunto de dados para entender suas características.
1. Identificação das variáveis relevantes para o problema de determinar o "Stroke".
1. Tratamento de dados ausentes ou inconsistentes, se necessário.

Escolha dos Algoritmos:

Algoritmos escolhidos para aplicação do problema de predição de AVC:
Árvore de Decisão, Random Forest, KNN, MLP e Regressão Logística.

Amostragem de Dados:

As seguintes técnicas de amostragem de dados foram utilizadas para preparar o conjunto de treinamento e teste:
K-Fold e Hold-Out.

Implementação:

Python com pacote do scikit-learn (sklearn), que oferece uma ampla variedade de algoritmos de Machine Learning.

Avaliação e Comparação dos Modelos:

Os modelos foram avaliados com base em métricas adequadas para problemas de classificação: acurácia, precisão, recall e F1-score.

<br>

## ⚙️Preparação do Ambiente

### **Conjunto de dados**

*Disponíveel no diretório `datasets`.*

Dataset obtido em:
https://www.kaggle.com/competitions/playground-series-s3e2/data?select=train.csv

### **Bibliotecas**

Este notebook foi desenvolvido em Jupiter e utiliza as bibliotecas abaixo:

```
from sklearn.tree import DecisionTreeClassifier
from sklearn.neighbors import KNeighborsClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.linear_model import LogisticRegression
from sklearn.neural_network import MLPClassifier
from sklearn.model_selection import train_test_split, GridSearchCV, RandomizedSearchCV
from sklearn.pipeline import Pipeline
from sklearn.metrics import recall_score, precision_score, accuracy_score, f1_score, confusion_matrix
from sklearn.model_selection import cross_val_predict, cross_val_score, StratifiedKFold

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

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
1. Exploração dos dados;
1. Escolha dos Algoritmos de Machine Learning;
1. Amostragem de Dados;
1. Avaliação e Comparação dos Modelos.

>O detalhamento de cada etapa, está comentado no notebook.

## 👨‍💻Autores

Ana Zanetti:  
https://github.com/anazanetti

Vagner Martins:  
https://github.com/manago13

Paula Capuano:  
https://github.com/paulacapuano

Mauro Domingues:  
https://github.com/maurodomingues  

