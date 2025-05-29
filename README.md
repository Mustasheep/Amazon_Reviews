# Visualização de Dados de Avaliações de Alimentos da Amazon

Este projeto tem como objetivo aplicar técnicas de visualização de dados em um dataset de avaliações de alimentos da Amazon. Ele foi desenvolvido como um trabalho acadêmico para o curso de Ciência de Dados da Cruzeiro do Sul Virtual.

## Introdução

O projeto utiliza o dataset "Amazon-fine-foods-reviews", disponível no Kaggle, que contém dados de avaliações de usuários sobre produtos alimentícios finos vendidos na Amazon. O objetivo principal é explorar e aplicar três técnicas de visualização de dados para extrair insights das avaliações. Este trabalho reflete o interesse em Processamento de Linguagem Natural (PLN) e no desenvolvimento de modelos de linguagem e inteligência artificial.

## Dataset

O dataset `Amazon-reviews-limpo.csv` foi previamente limpo e preparado para análise. Ele possui 568.454 linhas e 4 colunas.

As colunas relevantes para este projeto são:

  - `ProfileName`: Nome do usuário responsável pelo comentário.
  - `Score`: Nota da avaliação do usuário (de 1 a 5).
  - `Summary`: Título ou resumo do comentário.
  - `Text`: Comentário completo do usuário.

Link do dataset original no Kaggle: [Amazon-fine-foods-reviews](https://www.kaggle.com/datasets/thiagomustasheep/amazon-fine-foods-reviews).

<<<<<<< HEAD
## Visualizaes

### 1\. Grfico de Barras: Quantidade de Comentrios por Score

![barra](plots\barras.png)

Este grfico mostra a distribuio das avaliaes de pratos finos na Amazon, categorizadas por notas de 1 a 5 estrelas e a frequncia de comentrios para cada nota. A maioria expressiva dos usurios (63,88%) atribuiu a nota mxima de 5 estrelas, indicando alta satisfao. Uma parcela considervel (14,19%) deu 4 estrelas, enquanto avaliaes neutras (3 estrelas) representam 7,50% do total. Avaliaes negativas (2 e 1 estrela) correspondem a 5,24% e 9,19%, respectivamente.

### 2\. Histograma: Distribuio de Sentimentos

![hist](plots\histograma.png)

A anlise de sentimentos, realizada com a ferramenta TextBlob, revelou uma polaridade majoritariamente positiva nos comentrios, mesmo em avaliaes com notas mais baixas. A polaridade se concentra na faixa de 0 a 0.4, sugerindo um sentimento favorvel, mas no intenso. Isso pode indicar que a insatisfao em avaliaes negativas est relacionada a aspectos especficos, e no a uma percepo geral negativa do produto. Outliers na coluna 'Sentiment' foram removidos usando o mtodo IQR para esta visualizao.

### 3\. Grfico de Disperso: Caracteres por Score

![scatter](plots\dispersao.png)

A mdia de caracteres por comentrio  de 355, e a mdia de palavras  de 80. O grfico de disperso, que relaciona a quantidade de caracteres ao score da avaliao, indica uma tendncia de comentrios mais extensos em avaliaes positivas (scores mais altos). Clientes satisfeitos tendem a detalhar mais suas experincias, enquanto avaliaes negativas so geralmente mais concisas.

=======
>>>>>>> 16af526ee23ffbe83e5e0cc75390c6767e346690
## Tecnologias Utilizadas

  - Python
  - Pandas
  - Seaborn
  - Matplotlib
  - TextBlob
  - Kagglehub

## Visualizações

### 1\. Gráfico de Barras: Quantidade de Comentários por Score

Este gráfico mostra a distribuição das avaliações de pratos finos na Amazon, categorizadas por notas de 1 a 5 estrelas e a frequência de comentários para cada nota. A maioria expressiva dos usuários (63,88%) atribuiu a nota máxima de 5 estrelas, indicando alta satisfação. Uma parcela considerável (14,19%) deu 4 estrelas, enquanto avaliações neutras (3 estrelas) representam 7,50% do total. Avaliações negativas (2 e 1 estrela) correspondem a 5,24% e 9,19%, respectivamente.

### 2\. Histograma: Distribuição de Sentimentos

A análise de sentimentos, realizada com a ferramenta TextBlob, revelou uma polaridade majoritariamente positiva nos comentários, mesmo em avaliações com notas mais baixas. A polaridade se concentra na faixa de 0 a 0.4, sugerindo um sentimento favorável, mas não intenso. Isso pode indicar que a insatisfação em avaliações negativas está relacionada a aspectos específicos, e não a uma percepção geral negativa do produto. Outliers na coluna 'Sentiment' foram removidos usando o método IQR para esta visualização.

### 3\. Gráfico de Dispersão: Caracteres por Score

A média de caracteres por comentário é de 355, e a média de palavras é de 80. O gráfico de dispersão, que relaciona a quantidade de caracteres ao score da avaliação, indica uma tendência de comentários mais extensos em avaliações positivas (scores mais altos). Clientes satisfeitos tendem a detalhar mais suas experiências, enquanto avaliações negativas são geralmente mais concisas.

