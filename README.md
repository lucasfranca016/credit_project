# Projeto de análise e previsão do número de pacientes que irão para UTI no hospital Sírio-Libanês.

<p align="center"><img src=https://franquiaempresa.com/wp-content/uploads/2013/07/cr%C3%A9dito-banc%C3%A1rio.jpg </p> 

# **Introdução**

Realizei esse projeto para um case de uma entrevista de emprego, o tema era a análise de concessão de crédito e me foi dada uma base de dados de teste e uma base de dado para treino, ambas com valores faltantes e com outliers. Eu fiz uma análise exploratória e tratamento de dados focadas no tratamento dos problemas previamente citados e treinei alguns modelos de machine learning, prosseguindo com os que obtiveram o melhor resultado inicialmente.

Eu procurei otimizar os 2 modelos finais através de 2 métricas diferentes, contudo, por conta do tempo para o último modelo não realizei a otimização através da segunda métrica, entretanto, sendo ela uma métrica não muito eficiente para o problema em questão eu deixei passar para entregar o case a tempo.
  
# **Dados**

Os dados foram fornecidos pela empresa e estão disponíveis no repositório.

# **Estrutura do notebook:**

- Importação das bibliotecas usadas.

- Definição de Funções.
  
- Importação dos dados.

- Análise e Tratamento de Dados.

- Construção de um modelo preditivo

- Conclusão e previsão
  
No próprio notebook há uma análise de cada passo que foi dado e o porquê ele foi dado, desde a análise até a construção dos modelos, assim como uma breve descrição da utilização das funções empregadas.
  
## **Metodologia e resultado:**

- Eu comecei analisando 6 modelos amplamente usados para problemas de classificação de dados: GradientBoostingClassifier, AdaBoostClassifier, KNeighborsClassifier, RandomForestClassifier e MLPClassifier. Dado esses 6 modelos eu utilizei 3 parâmetros para os avaliar: a precisão, o ROC AUC Score e matrizes de confusão.
- Após uma primeira avaliação eu levei para frente os modelos de RandomForestClassifier e MLPClassifier a fim de fazer uma análise mais profunda, otimizando os hiperparâmetros através de duas métricas diferentes.
- A conclusão foi de que o modelo de MLPClassifier otimizado através da métrica de curva AUC Score foi o que melhor se sobressaiu e foi usado para a previsão.

## **Projeções futuras**

  - Esse projeto se limitou ao teste apenas de 6 modelos por questões de falta de tempo, assim, em um futuro trabalho essa análise pode ser extendida a outros modelos de classificação.
  - Um melhor estudo das métricas a serem utilizadas é bem vindo também, a fim de obtermos uma melhor avaliação para este problema específico, que exige uma atenção extra no número de falsos negativos por exemplo.
  
## **Contato**

Obrigado por conferir meu trabalho, me chamo Lucas França e atualmente sou graduando no curso de Física na Universidade Federal do Rio de Janeiro (UFRJ). Meu objetivo é continuar aprimorando minhas técnicas referentes à área de Data Science e implementar em projetos cada vez mais inovadores. =]

- Eu estou aberto para colaborações e ofertas de trabalho, então se você achou meu trabalho interessante e acha que eu tenho potencial para contribuir em seus projetos sinta-se livre para me mandar uma mensagem! Mesmo que você não tenha achado isso, mande-me uma mensagem de qualquer forma! Você pode me achar nos seguintes lugares:

<p>
  <a href="mailto:lucas.c.franca@gmail.com?Subject=From%20github">
    <img alt="Gmail" src="https://img.shields.io/badge/gmail-EA4335?logo=gmail&logoColor=white&style=for-the-badge" />
  </a>
  <a href="https://www.linkedin.com/in/lucas-fran%C3%A7a-83133016b/"><img alt="Linkedin" src="https://img.shields.io/badge/linkedin-0077B5?logo=linkedin&logoColor=white&style=for-the-badge" /></a>
</p>
  
