# Visualizao de Dados de Avaliaes de Alimentos da Amazon

Este projeto tem como objetivo aplicar tcnicas de visualizao de dados em um dataset de avaliaes de alimentos da Amazon. Ele foi desenvolvido como um trabalho acadmico para o curso de Cincia de Dados da Cruzeiro do Sul Virtual.

## Indice

  - [Introduo](https://www.google.com/search?q=%23introdu%C3%A7%C3%A3o)
  - [Dataset](https://www.google.com/search?q=%23dataset)
  - [Visualizaes](https://www.google.com/search?q=%23visualiza%C3%A7%C3%B5es)
      - [1. Grfico de Barras: Quantidade de Comentrios por Score](https://www.google.com/search?q=%231-gr%C3%A1fico-de-barras-quantidade-de-coment%C3%A1rios-por-score)
      - [2. Histograma: Distribuio de Sentimentos](https://www.google.com/search?q=%232-histograma-distribui%C3%A7%C3%A3o-de-sentimentos)
      - [3. Grfico de Disperso: Caracteres por Score](https://www.google.com/search?q=%233-gr%C3%A1fico-de-dispers%C3%A3o-caracteres-por-score)
  - [Tecnologias Utilizadas](https://www.google.com/search?q=%23tecnologias-utilizadas)
  - [Instalao e Uso](https://www.google.com/search?q=%23instala%C3%A7%C3%A3o-e-uso)

## Introduo

O projeto utiliza o dataset "Amazon-fine-foods-reviews", disponvel no Kaggle, que contm dados de avaliaes de usurios sobre produtos alimentcios finos vendidos na Amazon. O objetivo principal  explorar e aplicar trs tcnicas de visualizao de dados para extrair insights das avaliaes. Este trabalho reflete o interesse em Processamento de Linguagem Natural (PLN) e no desenvolvimento de modelos de linguagem e inteligncia artificial.

## Dataset

O dataset `Amazon-reviews-limpo.csv` foi previamente limpo e preparado para anlise. Ele possui 568.454 linhas e 4 colunas.

As colunas relevantes para este projeto so:

  - `ProfileName`: Nome do usurio responsvel pelo comentrio.
  - `Score`: Nota da avaliao do usurio (de 1 a 5).
  - `Summary`: Ttulo ou resumo do comentrio.
  - `Text`: Comentrio completo do usurio.

Link do dataset original no Kaggle: [Amazon-fine-foods-reviews](https://www.kaggle.com/datasets/thiagomustasheep/amazon-fine-foods-reviews).

## Visualizaes

### 1\. Grfico de Barras: Quantidade de Comentrios por Score

Este grfico mostra a distribuio das avaliaes de pratos finos na Amazon, categorizadas por notas de 1 a 5 estrelas e a frequncia de comentrios para cada nota. A maioria expressiva dos usurios (63,88%) atribuiu a nota mxima de 5 estrelas, indicando alta satisfao. Uma parcela considervel (14,19%) deu 4 estrelas, enquanto avaliaes neutras (3 estrelas) representam 7,50% do total. Avaliaes negativas (2 e 1 estrela) correspondem a 5,24% e 9,19%, respectivamente.

### 2\. Histograma: Distribuio de Sentimentos

A anlise de sentimentos, realizada com a ferramenta TextBlob, revelou uma polaridade majoritariamente positiva nos comentrios, mesmo em avaliaes com notas mais baixas. A polaridade se concentra na faixa de 0 a 0.4, sugerindo um sentimento favorvel, mas no intenso. Isso pode indicar que a insatisfao em avaliaes negativas est relacionada a aspectos especficos, e no a uma percepo geral negativa do produto. Outliers na coluna 'Sentiment' foram removidos usando o mtodo IQR para esta visualizao.

### 3\. Grfico de Disperso: Caracteres por Score

A mdia de caracteres por comentrio  de 355, e a mdia de palavras  de 80. O grfico de disperso, que relaciona a quantidade de caracteres ao score da avaliao, indica uma tendncia de comentrios mais extensos em avaliaes positivas (scores mais altos). Clientes satisfeitos tendem a detalhar mais suas experincias, enquanto avaliaes negativas so geralmente mais concisas.

## Tecnologias Utilizadas

  - Python
  - Pandas
  - Seaborn
  - Matplotlib
  - TextBlob
  - Kagglehub
