# IBM-Machine-Learning
Esse repositório contém os notebooks utilizados para a obtenção da Certificação IBM Machine Learning. Todos os notebooks foram avaliados por pares baseados em cinco critérios:
- Seção descrevendo os dados;
- Seção contendo os objetivos do notebook de forma clara; 
- Seção contendo diferentes modelos e definição do melhor;
- Seção contendo as principais observações da análise;
- Seção avaliando o projeto e um plano de ação para melhorar o projeto.

Abaixo há uma breve explicação sobre cada notebook. Obs: notebooks em inglês.

## Deep Learning (deep_learning_project)
- Objetivo: Classificação Estelar (Galáxia, Estrela ou Quasares).
- Modelos usados: Redes Neurais Densas com 0, 1 e 2 camadas ocultas.
- Bibliotecas: Pandas, Matplotlib, Seaborn, Numpy, Scikit-learn, Tensorflow e Keras.
- Melhor Modelo: Modelo sem Camadas Internas (1 camada densa de entrada com 128 neurônios e uma camada de saída com 3 neurônios).


## Classificação (ml_classification_project)
- Objetivo: Identificação do Nível de Estresse Humano (0 - baixo, 1 - médio/baixo, 2 - médio, 3 - médio/alto ou 4 - alto).
- Modelos usados: Logistic Regression, KNN e SVM.
- Bibliotecas: Pandas, Matplotlib, Seaborn, Numpy e Scikit-learn.
- Melhor Modelo: Os três modelos conseguiram identificar com 100% de precisão todas as classes. (Obs: É necessária a obtenção de uma maior quantidade de amostras).


## Clustering (ml_cluestering_project)
- Objetivo: Determinar os países que mais necessitam de ajuda humanitária baseado em índices socio-econômicos.
- Modelos usados: DBSCAN, Agglomerative Clustering e KMeans.
- Bibliotecas: Pandas, Matplotlib, Seaborn, Numpy, Scikit-learn e Plotly.
- Melhor Modelo: Modelo KMeans, que conseguiu obter 4 clusters. Foram identificados 47 países que necessitam de mais ajuda em comparação com o restante do mundo.

 
## Regressão (ml_regression_project)
- Objetivo: Criar um modelo de regressão para determinar o preço do aluguel de casas brasileiras.
- Modelos usados: Regressão Linear, Regressão Linear com Polynomial Features e Regressão Linear com penalidade Lasso.
- Bibliotecas: Pandas, Matplotlib, Seaborn, Numpy e Scikit-learn.
- Melhor Modelo: Modelo com Polynomial Features por obter o melhor valor de R2.

## Séries Temporais (time_series_project_arima_rnn_lstm)
- Objetivo: Criar um modelo de séries temporais para prever o preço histórico do ouro.
- Modelos usados: ARIMA, Simple RNN e LSTM.
- Bibliotecas: Pandas, Matplotlib, Seaborn, Numpy, Statsmodels, Pmdarima, Scikit-learn e Keras.
- Melhor Modelo: Simple RNN, que obteve o menor erro médio quadrático.
