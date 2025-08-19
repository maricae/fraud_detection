# Detecção de fraudes em transações de cartão de crédito: análise de modelos de machine learning.

> *Trabalho de Conclusão de Curso (TCC) apresentado e aprovado no MBA em Data Science e Analytics da USP/Esalq, com nota 9,5.*

O crescimento do uso de cartões de crédito aumentou a incidência de fraudes financeiras, tornando essencial o desenvolvimento de soluções eficazes para sua detecção. Este trabalho teve como objetivo desenvolver e avaliar modelos de aprendizado de máquina para identificar transações fraudulentas com maior eficiência e precisão. 

Para isso, foram utilizados os algoritmos K-Nearest Neighbors (KNN), Random Forest e Gradient Boosting, treinados e comparados por meio das métricas precisão, recall e F-score. A metodologia envolveu a seleção das variáveis preditoras mais relevantes, o balanceamento da base de dados para lidar com a desproporção entre transações fraudulentas e não fraudulentas, além da análise do impacto dessas estratégias no desempenho dos modelos. 

Os resultados demonstraram que os algoritmos Random Forest e KNN apresentaram um melhor equilíbrio entre precisão e recall, mostrando-se mais adequados para a detecção de fraudes. Conclui-se que abordagens baseadas em aprendizado de máquina podem aprimorar a segurança dos sistemas financeiros, reduzindo perdas e aumentando a eficiência na identificação de transações suspeitas.

## 🎲 Fonte dos Dados:

A base de dados utilizada neste estudo foi coletada pela Universidade Livre de Bruxelas (ULB) e contém transações com cartão de crédito realizadas por usuários europeus em setembro de 2013. O conjunto de dados é composto por 284.807 transações, das quais apenas 492 são fraudes, representando apenas 0,172% do total, o que torna o problema altamente desbalanceado.

A base de dados é composta por 31 colunas, das quais 28 são variáveis numéricas transformadas por Análise de Componentes Principais (PCA).

## 🧠 Tecnologias e Bibliotecas Utilizadas:

- **Linguagem**  
  - Python  

- **Manipulação e Análise de Dados**  
  - Pandas  
  - NumPy  

- **Visualização de Dados**  
  - Matplotlib  
  - Seaborn  

- **Pré-processamento**  
  - StandardScaler (Scikit-learn)  
  - RobustScaler (Scikit-learn)  

- **Testes Estatísticos**  
  - Shapiro-Wilk (SciPy)  
  - Kolmogorov-Smirnov (SciPy)  

- **Modelagem e Machine Learning**  
  - Train Test Split (Scikit-learn)  
  - Random Forest Classifier (Scikit-learn)  
  - Gradient Boosting Classifier (Scikit-learn)  
  - K-Nearest Neighbors Classifier (Scikit-learn)  

- **Métricas de Avaliação**  
  - Precision Score (Scikit-learn)  
  - Recall Score (Scikit-learn)  
  - F1-Score (Scikit-learn)  
