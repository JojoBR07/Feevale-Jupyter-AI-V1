# Classificador de Diabetes

Este projeto utiliza técnicas de aprendizado de máquina para classificar casos de diabetes com base em dados clínicos. O fluxo de trabalho inclui pré-processamento dos dados, treinamento de modelos, avaliação e análise dos resultados.

## Estrutura do Projeto

- **diabetes_preprocess.ipynb**: Pré-processamento dos dados, análise exploratória e preparação dos conjuntos de treino e teste.
- **diabetes_process.ipynb**: Treinamento dos modelos (Árvore de Decisão, Random Forest, MLP) e geração das predições.
- **diabetes_analysis.ipynb**: Avaliação dos modelos, geração de métricas e análise dos resultados.
- **Dataset/**: Contém o dataset original.
- **Files/**: Armazena arquivos intermediários, conjuntos de treino/teste e predições.
- **Model/**: Modelos treinados salvos em formato `.pkl`.

## Como Executar

1. **Pré-processamento**  
   Execute o notebook `diabetes_preprocess.ipynb` para preparar os dados e gerar os arquivos necessários em `Files/`.

2. **Treinamento**  
   Execute o notebook `diabetes_process.ipynb` para treinar os modelos e salvar as predições e modelos em `Files/` e `Model/`.

3. **Análise**  
   Execute o notebook `diabetes_analysis.ipynb` para avaliar o desempenho dos modelos e visualizar métricas como acurácia, matriz de confusão e relatório de classificação.

## Requisitos

- Python 3.x
- Bibliotecas: jupyter

Instale a dependência com:

```sh
pip install jupyterlab