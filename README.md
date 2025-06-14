# Projeto: Previsão de Diabetes

## 📝 Visão Geral do Projeto

Este projeto tem como objetivo analisar um conjunto de dados de pacientes para prever a probabilidade de diabetes e explorar a relação entre diversas variáveis de saúde. O notebook detalha as etapas de Análise Exploratória de Dados (EDA), pré-processamento de dados e aplicação de modelos de Machine Learning.

## 📊 Conjunto de Dados

O dataset utilizado neste projeto é o `diabetes_dataset.csv`, comumente encontrado em plataformas de aprendizado de máquina. Ele contém diversas características de saúde de pacientes.

## 🎯 Perguntas de Negócio Abordadas

Este projeto buscou responder às seguintes questões:
1.  A idade é um indicativo de diabetes?
2.  Diabetes gestacional anterior é um indicativo de diagnóstico atual de diabetes?
3.  Idade, IMC e nível de atividade física podem prever se uma pessoa tem diabetes?
4.  Ingestão de calorias e nível de atividade física podem prever diabetes?
5.  Existe uma relação entre GGT alto e consumo de álcool?

## 🚀 Metodologia

O projeto seguiu as seguintes etapas:
1.  **Carregamento e Inspeção Inicial dos Dados:** Verificação de tipos de dados, valores ausentes e estatísticas descritivas.
2.  **Tratamento de Valores Ausentes:** Tratamendo de NaN na coluna  `Alcohol_Consumption`, presente em muitos registros.
3.  **Análise Exploratória de Dados (EDA):** Visualizações e estatísticas para entender as distribuições e relações entre as variáveis.
4.  **Pré-processamento para Modelagem:** Normalização das features e divisão dos dados em conjuntos de treino e teste.
5.  **Modelagem Preditiva:**
    * Utilização de **Regressão Logística** para prever o `HbA1c` (diabetes).
    * Aplicação de **Regressão Linear** para analisar a relação entre GGT e consumo de álcool (com base em dados simulados ou inferidos).
6.  **Avaliação dos Modelos:** Análise de `classification_report`, `confusion_matrix`, R² e RMSE.


## 🛠️ Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels

## 📄 Como Rodar o Projeto

1.  Clone este repositório: `git clone https://github.com/marjoryebrito/previsao-diabetes.git`
2.  Navegue até o diretório do projeto: `cd previsao-diabetes`
3.  Instale as bibliotecas necessárias (se ainda não as tiver):
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
    ```
4.  Abra o notebook `Previsão de Diabetes.ipynb` em um ambiente como Jupyter Notebook ou Google Colab e execute as células.

## 💡 Próximos Passos / Melhorias Futuras

* Explorar outras técnicas de engenharia de features.
* Testar diferentes modelos de classificação (ex: Random Forest, Gradient Boosting).
* Realizar validação cruzada para uma avaliação mais robusta do modelo.

## 👩‍💻 Sobre o Desenvolvedor
Este é o meu primeiro projeto público em Data Science. Estou no início da minha carreira e construindo meu portfólio para aplicar os conhecimentos adquiridos e continuar aprendendo. O objetivo deste projeto foi explorar e aplicar as técnicas fundamentais de análise e modelagem. Qualquer feedback construtivo é muito bem-vindo!

## 🤝 Contato

Conecte-se comigo:
- [LinkedIn](www.linkedin.com/in/marjoryebrito)
- [marjorye.brito.ds@gmail.com](mailto:marjorye.brito.ds@gmail.com)
