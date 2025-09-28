# MVP — Machine Learning & Analytics

**Nome:** Fábio Henrique Neves Reis Ribeiro

## Dataset:

O dataset UCI Adult Income (Census Income) é um conjunto de dados baixado do site *kaggle.com*. Ele contém atributos demográficos e relacionados ao trabalho de indivíduos do censo dos EUA de 1994. O objetivo é prever se uma pessoa ganha mais de 50K por ano com base em características pessoais e profissionais.

[UCI Adult Income (Census Income)](https://www.kaggle.com/datasets/mosapabdelghany/adult-income-prediction-dataset?resource=download)


## Predição de Renda Anual (>50K USD)

Este projeto aplica **Machine Learning e Analytics** para prever se um indivíduo possui renda anual superior a **50 mil dólares**, utilizando o dataset **UCI Adult Income (Census Income)**.

O trabalho segue um pipeline estruturado e reprodutível que inclui:

* Pré-processamento: imputação, padronização e codificação one-hot.
* Divisão estratificada em treino e teste.
* Avaliação de modelos baseline e candidatos (**Regressão Logística, Random Forest e Gradient Boosting**).
* Otimização de hiperparâmetros com validação cruzada estratificada.
* Métricas de desempenho: **Acurácia, F1 ponderado, ROC AUC e Average Precision (AP)**.
* Análise de calibração de probabilidades e de **justiça algorítmica** por sexo e raça.

### Principais resultados

* O modelo **Gradient Boosting** apresentou o melhor desempenho (**F1 ≈ 0,85 e ROC AUC ≈ 0,91**).
* Foram identificadas **disparidades entre grupos demográficos**, evidenciando a necessidade de mitigação de vieses e governança responsável.
