# Classificação de Gatos vs Cachorros com Transfer Learning

Este projeto tem como objetivo aplicar **Transfer Learning** em uma rede de Deep Learning usando a linguagem **Python** no ambiente **Google Colab**. O foco é classificar imagens de **gatos** e **cachorros** com alta precisão a partir de um conjunto de dados pré-existente.

## 📚 Sobre Transfer Learning

**Transfer Learning** é uma técnica de aprendizado profundo onde um modelo previamente treinado em uma grande base de dados (como ImageNet) é adaptado para uma nova tarefa com menos dados, reduzindo tempo de treinamento e aumentando a acurácia.

Neste projeto, utilizamos essa técnica para reaproveitar o conhecimento de uma rede convolucional pré-treinada na tarefa de classificar imagens de gatos e cachorros.

## 🐱🐶 Dataset

O conjunto de dados utilizado é o [Kaggle Cats and Dogs Dataset](https://download.microsoft.com/download/3/e/1/3e1c3f21-ecdb-4869-8368-6deba77b919f/kagglecatsanddogs_5340.zip), fornecido pela Microsoft.

### Informações do dataset:

- Total aproximado de imagens: 25.000
- Classes: `cat`, `dog`
- Tamanho das imagens: variável
- Formato: `.jpg`

## ⚙️ Tecnologias e Ferramentas

- Python 3
- TensorFlow / Keras
- Google Colab
- Pandas / NumPy
- Matplotlib / Seaborn (visualização de dados)

## 🧪 Estrutura do Projeto

O projeto está estruturado em um notebook Jupyter com os seguintes tópicos:

1. **Importação das bibliotecas**
2. **Download e preparação dos dados**
3. **Visualização inicial das imagens**
4. **Pré-processamento e divisão do dataset**
5. **Carregamento do modelo pré-treinado (Transfer Learning)**
6. **Ajuste e treinamento do modelo**
7. **Avaliação de desempenho**
8. **Visualização dos resultados (matriz de confusão, acurácia, etc.)**

## 🚀 Execução

1. Acesse o [Google Colab](https://colab.research.google.com/).
2. Carregue o notebook `classification-cats-vs-dogs.ipynb`.
3. Execute as células sequencialmente:
   - O notebook fará o download e extração automática do dataset.
   - O modelo será treinado utilizando uma arquitetura pré-treinada (ex: `MobileNetV2`, `VGG16`, etc.)
4. Acompanhe os gráficos e métricas para avaliar o desempenho do modelo.

## 📈 Resultados Esperados

Com a aplicação de Transfer Learning, espera-se:

- Alta acurácia na classificação das imagens
- Redução do tempo de treinamento
- Boa generalização em dados de validação

## 📝 Autor

Projeto desenvolvido como parte de um desafio técnico de aprendizado de máquina com foco em Visão Computacional.

---

