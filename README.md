# Projetos ADA Tech

**No repositório, você encontrará os projetos de cada módulo do curso de Data Science da AdaTech do programa Santander Coders.**

### Lógica de Programação II em Python
O primeiro projeto tem como objetivo desenvolver um algoritmo baseado em k-Nearest Neighbors (k-NN), 
também conhecido como "algoritmo do vizinho mais próximo", para classificar o perfil de investidores de clientes de uma empresa de investimentos. 
A ideia é utilizar os dados de clientes já classificados para estimar o perfil daqueles que ainda não foram categorizados. 
Os clientes são classificados como investidores Conservadores, Moderados ou Agressivos.
**Para desenvolver este projeto, não é permitido utilizar nenhuma biblioteca como numpy ou math. Deve-se utilizar apenas os objetos e 
fluxos vistos até o momento no curso, como funções e estruturas de controle.**

O projeto **Algoritmo  KNN** pode ser acessado [aqui](https://github.com/leticiadluz/projetos_ADA/blob/main/logica_programacao_II/KNN_projeto_carteira_investimentos.ipynb)

### Técnicas de Programação I em Python 

O objetivo do segundo projeto é conduzir uma análise exploratória de dados utilizando conjuntos de dados relacionados ao Brasil. Temos a liberdade de incluir quantas bases forem necessárias e filtrar as informações mais relevantes para a narrativa em questão. 
Nosso grupo selecionou dois conjuntos de dados para analisar os padrões de preferência de gêneros de filmes entre os brasileiros. Além disso, investigamos se essa preferência varia ao longo do tempo, como durante as férias escolares, por exemplo. Também buscamos insights sobre quais filmes permaneceram por mais tempo no TOP 10 (por mais de uma semana) e qual é a duração média dos filmes assistidos.

**Datasets utilizados:**
- all-weeks-countries.xlsx:
  - Descrição do Dataset: O primeiro conjunto de dados é fornecido pela Netflix e contém as listas semanais dos títulos mais assistidos na Netflix em todo o mundo, por país. A coleta de dados começou em 28 de junho de 2021 e foi atualizada pela última vez em 05/02/2024, antes deste projeto. Ele pode ser acessado [aqui](https://github.com/leticiadluz/projetos_ADA/blob/main/tecnicas_programacao/all-weeks-countries.xlsx).

- data.tsv
  - Descrição do Dataset: O segundo conjunto de dados, foi obtido do site da IMDb. Este conjunto contém uma lista de todos os filmes mundiais, juntamente com suas características mais relevantes. O conjunto pode ser acessado clicando [aqui](https://datasets.imdbws.com/title.basics.tsv.gz). Pode ser um arquivo muito grande não conseguimos armazená-lo no GitHub.

O projeto foi elaborado no Colab, e o primeiro notebook, onde realizamos a limpeza e transformação dos dados, é intitulado **"1_Netflix_limpeza_transformacao.ipynb".** Você pode acessá-lo clicando [aqui](https://github.com/leticiadluz/projetos_ADA/blob/main/tecnicas_programacao/1_Netflix_limpeza_transformacao.ipynb)
- Durante nosso processo de limpeza e transformação dos dados, criamos outro conjunto de dados para facilitar a análise exploratória. Você pode acessar o conjunto de dados limpo clicando
[aqui](https://github.com/leticiadluz/projetos_ADA/blob/main/tecnicas_programacao/filmes_netflix_corrigido.csv)

O segundo notebook foi elaborado com base no conjunto de dados já limpo e é intitulado **"2_Netflix_EDA.ipynb"** e pode ser acessado [aqui](https://github.com/leticiadluz/projetos_ADA/blob/main/tecnicas_programacao/2_Netflix_EDA.ipynb)

### Banco de Dados I

O objetivo deste terceiro projeto é conduzir uma análise exploratória de dados utilizando a linguagem SQL. Faremos uso de um dataset de nossa preferência, o qual será 
armazenado em um banco de dados PostgreSQL. Posteriormente, estabeleceremos uma conexão com Python para executar as queries necessárias.
Para esta tarefa, utilizaremos o Jupyter Notebook para conduzir nossa análise descritiva.  

**Datasets utilizados:**
- Amazon Top 50 Bestselling Books 2009 - 2022
  - Descrição do Dataset: Este conjunto de dados compila informações sobre os 50 livros mais vendidos na Amazon entre os anos de 2009 e 2022.
    Ele oferece uma visão abrangente dos livros populares durante esse período, destacando detalhes como o título do livro, o autor, a avaliação média, o número de avaliações,
    o preço, o ano de publicação e o gênero. Para acessar clique [aqui](https://www.kaggle.com/datasets/chriskachmar/amazon-top-50-bestselling-books-2009-2022)

- Books Dataset
  - Descrição do Dataset: Este conjunto de dados compreende informações coletadas do wonderbk.com, uma livraria online popular.
    O conjunto de dados contém detalhes de 103.063 livros, com atributos-chave como título, autores, descrição, categoria, editora, preço inicial e data de publicação.
    Para acessar clique [aqui](https://www.kaggle.com/datasets/elvinrustam/books-dataset)  

O projeto **Análise Exploratória de Dados Utilizando SQL e Python** pode ser acessado [aqui](https://github.com/leticiadluz/projetos_ADA/blob/main/banco_dados/Projeto_banco_dados.ipynb)

### Estatística

O propósito deste quarto projeto é responder cinco questões relativas ao conjunto de dados "Body Fat Prediction", utilizando os conceitos estatísticos aprendidos no módulo, tais como estatística descritiva, amostragem, distribuições de probabilidade e testes de hipóteses.

**Datasets utilizados:**
- Body Fat Prediction Dataset:
  - Descrição do Dataset: Apresenta estimativas do percentual de gordura corporal determinado por pesagem subaquática e várias medidas de circunferência corporal para 252 homens.
  - Para acessar clique [aqui](https://www.kaggle.com/datasets/fedesoriano/body-fat-prediction-dataset)
 
O projeto de **estatística** pode ser acessado [aqui](https://github.com/leticiadluz/projetos_ADA/blob/main/estatistica/projeto_estatistica.ipynb)

## Ferramentas utilizadas

* Google Colab
* Jupyter Notebook
  
## Linguagem utilizada

* Python


