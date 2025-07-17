# Projeto de Credit Score - Árvore de Decisão

Este projeto tem como objetivo prever o Credit Score de clientes utilizando algoritmos de Machine Learning, com foco em Árvores de Decisão. O trabalho faz parte do curso EBAC e utiliza dados fictícios para classificação de risco de crédito.

## Estrutura do Projeto

- `CREDIT_SCORE_M20.csv`: Base de dados utilizada para treinamento e teste dos modelos.
- `Profissao Cientista de Dados M21 Pratique.ipynb`: Notebook principal com todo o passo a passo do projeto.

## Etapas Realizadas

1. **Carregamento e tratamento dos dados**  
   - Remoção de colunas desnecessárias  
   - Transformação de variáveis categóricas

2. **Separação das bases de treino e teste**  
   - Utilização do `train_test_split` para garantir avaliação justa do modelo

3. **Balanceamento das classes**  
   - Aplicação do SMOTE apenas na base de treino para evitar viés

4. **Treinamento do modelo de Árvore de Decisão**  
   - Critério de Gini e random_state definido

5. **Avaliação do modelo**  
   - Relatórios de classificação e acurácia para treino e teste  
   - Comparação com modelo Naive Bayes

6. **Análise de importância das features**  
   - Identificação das variáveis mais relevantes para o modelo

## Como executar

1. Instale as dependências necessárias:
   ```sh
   pip install pandas numpy seaborn scikit-learn imbalanced-learn matplotlib
   ```

2. Abra o notebook `Profissao Cientista de Dados M21 Pratique.ipynb` no Jupyter ou VSCode.

3. Execute as células sequencialmente para acompanhar o fluxo do projeto.

## Principais Resultados

- O modelo de Árvore de Decisão apresentou alta acurácia tanto na base de treino quanto na de teste.
- As variáveis **Income** e **Home Ownership Code** foram as mais importantes para a classificação.
- O modelo é facilmente interpretável e visualizável.

## Autor

Projeto desenvolvido por Flaviano Astolfo Junior