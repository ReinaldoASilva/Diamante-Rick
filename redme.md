# README - Análise de Dados de Diamantes

Este código em Python realiza uma análise de dados de diamantes, utilizando diversas bibliotecas e técnicas de aprendizado de máquina.

## Funcionalidades do Código

O código realiza as seguintes etapas:

1. Importação de bibliotecas: O código importa as bibliotecas necessárias para a análise, incluindo pandas, numpy, matplotlib, seaborn, sklearn e statsmodels.

2. Visualização do arquivo: O código lê o arquivo CSV contendo os dados dos diamantes e exibe as primeiras linhas do DataFrame.

3. Verificação de valores nulos: O código verifica a quantidade de valores nulos em cada coluna do DataFrame.

4. Informações sobre o arquivo: O código exibe estatísticas descritivas sobre os dados, como média, desvio padrão, mínimo e máximo.

5. Tratamento de outliers: O código identifica e trata os outliers presentes nas colunas numéricas do DataFrame, substituindo-os por valores nulos (NaN).

6. Visualização de boxplots: O código exibe boxplots para cada coluna numérica do DataFrame, permitindo a identificação visual de outliers.

7. Tratamento de valores nulos: O código substitui os valores nulos (NaN) nas colunas numéricas pela média dos valores não nulos.

8. Codificação de variáveis categóricas: O código codifica as variáveis categóricas do DataFrame utilizando a técnica de Label Encoding.

9. Concatenação do DataFrame: O código concatena as colunas codificadas com o DataFrame original.

10. Visualização de gráficos: O código exibe gráficos de dispersão e uma matriz de correlação para analisar as relações entre as variáveis.

11. Divisão dos dados: O código divide os dados em conjuntos de treinamento e teste.

12. Treinamento de modelos: O código treina modelos de regressão linear e regressão de floresta aleatória nos dados de treinamento.

13. Avaliação dos modelos: O código avalia o desempenho dos modelos utilizando as métricas R² e erro médio quadrático (RMSE) nos dados de teste.

14. Otimização dos hiperparâmetros: O código realiza uma otimização dos hiperparâmetros do modelo de regressão de floresta aleatória utilizando uma busca aleatória.

15. Treinamento do modelo otimizado: O código treina um novo modelo de regressão de floresta aleatória utilizando os hiperparâmetros otimizados.

16. Avaliação do modelo otimizado: O código avalia o desempenho do modelo otimizado utilizando as métricas R² e RMSE nos dados de teste.

17. Salvamento dos dados: O código salva o DataFrame final em um arquivo CSV.

## Execução do Código

Para executar o código, é necessário ter as bibliotecas pandas, numpy, matplotlib, seaborn, sklearn e statsmodels instaladas em seu ambiente Python.

Certifique-se de ter o arquivo CSV contendo os dados dos diamantes no caminho especificado (`'/Users/reinaldoblack/Downloads/diamante/historico_diamonds.csv'`).

Após a execução do código, serão realizadas diversas etapas de análise e modelagem dos dados de diamantes, com a exibição de gráficos e resultados de métricas de avaliação.

