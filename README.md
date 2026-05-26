# Previsao-de-Fraudes-com-Modelos-de-Machine-Learning
Neste projeto foi criado alguns modelos de Machine Learning para previsão de fraudes utilizando [este banco de dados](https://github.com/mike-antunes/Previs-o-de-Fraudes-com-Modelos-de-Machine-Learning/blob/main/BaseDeDadosDoProjeto) 


## [Os atributos executados no projeto foram:](https://github.com/mike-antunes/Previs-o-de-Fraudes-com-Modelos-de-Machine-Learning/blob/main/ModeloPrevisaoFraude.ipynb)
- Conjunto de dados com mais de 80.000 registros   
- Analise exploratória de variáveis categóricas e numéricas  
- Analise e tratamento de valores missing (nulos)  
- Analise estatística de variáveis  
- Tratamento de Dados  
- Engenharia de Atributos  
- Gráficos  
- Outliers  
- Normalização e Padronização de Dados  
- Balanceamento da variável ALVO (TARGET)  
- OneHotEncoding  
- Criação, treino e teste dos modelos preditivos com 3 algoritmos diferentes (Random Forest, Suport Vector Machine e KNN  
- GridSearch para ajustes de hiperparametros automáticos e treino de mais de 1.000 modelos  
- Analise dos pesos das melhores variáveis  

## Resumo do projeto para compreenssão básica:
O projeto foi desenvolvido para praticar demonstrando as principais funções, fundamentos e conceitos para um bom tratamento de dados indo da sua
etapa inicial de análise e avaliação até os conceitos um pouco mais complexos de tratamento como limpeza, normalização, preparo dos dados para serem utilizados
em modelos de Machine Learning, entre outros atributos descritos na lista acima. O objetivo foi atingir o melhor resultado utilizando 3 modelos de Machine Learning
que foram (Random Forest, SVM, KNN).  
Desde o início do projeto o foco foi criar um modelo que pudesse prever possíveis fraudes presentes no banco de dados utilizado que contém as informações dos empréstimos de clientes.

## Resultados do projeto:
**Numero de modelos treinados**  
Random Forest (324 modelos treinados)  
SVM (192 modelos treinados)  
KNN (120 modelos treinados)

**Percentual de acerto nos testes**  
Random Forest 99.23%  
SVM 98.92%  
KNN 97.04%

**Poderia atingir resultados ainda melhores???**  
Sim, ajustando e testando novos hiperparâmetros de cada modelo poderíamos chegar em resultados ainda melhores. Porém, poderíamos chegar também em resultados
piores, o que define a melhora ou a piora dos resultados seriam maiores testes a serem feitos em cada modelo ajustando suas configurações e modificando
a prioridade de algumas colunas da base de dados a serem utilizados, além de outras possibilidades.

