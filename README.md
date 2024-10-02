# Introdução à Machine Learning com Scikit-Learn

Este repositório contém a implementação de um trabalho prático da disciplina **Introdução a Machine Learning**, utilizando a biblioteca **Scikit-Learn** em Python. O trabalho está dividido em duas partes, cada uma focada na aplicação de algoritmos de aprendizado de máquina em diferentes conjuntos de dados.

## Estrutura do Projeto

### Parte 1: Tutorial de Machine Learning
Nesta parte, reproduzimos um tutorial de Machine Learning utilizando os seguintes algoritmos:
- **Support Vector Machines (SVM)**
- **KNeighborsClassifier (KNN)**
- **RandomForestClassifier**

#### Conjuntos de dados utilizados:
- **Iris**: Um conjunto de dados clássico de classificação de flores de íris.
- **Digits**: Um conjunto de dados com imagens de dígitos manuscritos.

#### Resultados:
Foram avaliados os resultados dos algoritmos utilizando métricas como Matriz de Confusão, Precisão, Recall, F1-Score e Acurácia. A análise detalhada dos resultados está disponível no relatório em PDF.

Link para o notebook do Google Colaboratory:  
[Parte 1 - Notebook](https://colab.research.google.com/drive/1jxHvEeAaw3nURMsINRSAISLKohLn2ryG?usp=sharing)

### Parte 2: Classificação de Câncer de Mama
Na segunda parte, realizamos uma análise comparativa de quatro algoritmos de Machine Learning utilizando o conjunto de dados de **Câncer de Mama de Wisconsin**. Os algoritmos utilizados foram:
- **Support Vector Machines (SVM)**
- **KNeighborsClassifier (KNN)**
- **RandomForestClassifier**
- **Logistic Regression**

#### Resultados:
Os modelos foram avaliados em termos de desempenho de classificação, utilizando o conjunto de dados de câncer de mama. A técnica de PCA (Análise de Componentes Principais) foi utilizada para reduzir a dimensionalidade dos dados e visualizá-los em um espaço bidimensional.

Link para o notebook do Google Colaboratory:  
[Parte 2 - Notebook](https://colab.research.google.com/drive/1jk-15xcLiPwnOpTppei0cFScXxPHLakV?usp=sharing)

## Relatório
O relatório completo, com detalhes sobre a metodologia, algoritmos, conjunto de dados e os resultados obtidos, pode ser encontrado nos arquivos PDF incluídos neste repositório.

- [Relatório Completo - PDF](https://github.com/israelsilvap/IntroducaoMachineLearning/blob/main/Trabalho%20Introducao%20a%20Machine%20Learning.pdf)

## Tecnologias Utilizadas
- **Python**
- **Scikit-Learn**: Biblioteca de Machine Learning
- **Matplotlib**: Para visualização de dados
- **Pandas**: Para manipulação de dados
- **Google Colaboratory**: Para execução do código

## Como Executar
Os notebooks podem ser acessados diretamente via Google Colaboratory pelos links fornecidos acima. Alternativamente, você pode clonar este repositório e rodar os notebooks localmente, desde que tenha o ambiente Python configurado com as bibliotecas necessárias.

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
3. Abra os notebooks e execute as células.


## Referências

- [Scikit-Learn - Documentação Oficial](https://scikit-learn.org/stable/)
- [Matplotlib - Documentação](https://matplotlib.org/)
