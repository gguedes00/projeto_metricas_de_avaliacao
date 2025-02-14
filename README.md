# Cálculo de Métricas de Avaliação de Aprendizado

## Descrição do Projeto

Este projeto foi feito por conta de um desafio proposto plo bootcamp e calcula as principais métricas para avaliação de modelos de classificação de dados, incluindo acurácia, sensibilidade (recall), especificidade, precisão e F-score. Utiliza uma matriz de confusão como base para os cálculos, permitindo a análise do desempenho de modelos de machine learning.


## Fórmulas Utilizadas


### Sensibilidade

VP / (VP + FN)


### Especificidade

VN / (VN + FP)


### Acurácia

(VP + VN) / N


### Precisão

VP / (VP + FP)


### F-score

2 × (Precisão × Sensibilidade) / (Precisão + Sensibilidade)



## Estrutura do Código

O código segue os seguintes passos:

Definição da matriz de confusão.

Cálculo das métricas para cada classe.

Consolidação das métricas em um DataFrame.

Exibição dos resultados formatados.


## Requisitos

Python 3.x

Google Colab (ou Jupyter Notebook)

Bibliotecas: numpy, pandas, tensorflow


## Contribuição

Contribuições são bem-vindas! Para sugerir melhorias, abra uma issue ou envie um pull request.

## Licença

Este projeto está licenciado sob a MIT License.


