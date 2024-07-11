# IMDb Movies Data Analysis Project - Desafio Lighthouse 

## Descrição

Este projeto envolve a análise de um conjunto de dados de filmes do IMDb. O objetivo é explorar e analisar os dados para obter insights sobre diferentes aspectos dos filmes, como receita bruta, classificações do IMDb, duração, etc. Também inclui a construção de um modelo de previsão do IMDb de um filme com base em várias características.

## Estrutura do Projeto

- `data/`: Contém o conjunto de dados utilizado para o projeto.
- `notebooks/`: Contém notebooks Jupyter com as análises e modelagens realizadas.
- `scripts/`: Contém scripts Python para processamento e análise dos dados.
- `requirements.txt`: Lista de bibliotecas necessárias para reproduzir o ambiente do projeto.
- `README.md`: Descrição do projeto, estrutura, instruções de instalação e uso.

## Conjunto de Dados

O conjunto de dados utilizado neste projeto contém as seguintes colunas:

- `Series_Title`: Título do filme
- `Released_Year`: Ano de lançamento
- `Certificate`: Classificação indicativa
- `Runtime`: Duração do filme em minutos
- `Genre`: Gênero do filme
- `IMDB_Rating`: Classificação do IMDb
- `Overview`: Sinopse do filme
- `Director`: Diretor do filme
- `Star1`: Estrela principal
- `Star2`: Segunda estrela principal
- `Star3`: Terceira estrela principal
- `Star4`: Quarta estrela principal
- `No_of_Votes`: Número de votos no IMDb
- `Meta_score`: Pontuação do Metacritic
- `Gross_Revenue`: Receita bruta do filme

## Instalação

1. Clone o repositório para sua máquina local:
   ```sh
   git clone https://github.com/seu-usuario/imdb-movies-analysis.git
   cd imdb-movies-analysis
   ```

2. Crie um ambiente virtual:
   ```sh
   python -m venv venv
   source venv/bin/activate  # ou .\venv\Scripts\activate no Windows
   ```

3. Instale as dependências:
   ```sh
   pip install -r requirements.txt
   ```

## Utilização

1. Execute os notebooks Jupyter para visualizar as análises e modelagens:
   ```sh
   jupyter notebook
   ```

2. Vá até o diretório `notebooks` e abra os notebooks de interesse.

## Principais Análises Realizadas

- **Análise Exploratória de Dados (EDA)**: Exploração dos dados para entender suas características e distribuições.
- **Insights**: Construção e análises de perguntas relacionadas ao comportamento dos dados como, tendências, agrupamentos, correlações e análises de impacto.
- **Modelagem Preditiva**:
  - Regreção Linear, Random Forest, Lasso e XGBoost para prever a classificação do IMDb.

## Resultados

- Primeiramente foi possível a construção de uma EDA com análises estatísticas específicas sobre os atributos e a construção de insights sobre filmes, atores, diretores e o mercado de cinema no geral;
- Responder as questões estipuladas pelo time superior;
- Construir um modelo inicial de previsão de notas do IMDb;
- Prever a nota IMDB do filme: 'The Shawshank Redemption' de 1994.  

## Conclusão

Este projeto fornece uma visão abrangente dos dados de filmes do IMDb e demonstra como técnicas de ciência de dados podem ser aplicadas para extrair insights valiosos e construir modelos preditivos. Para estudos futuros estão a coleta de novos dados para abastecer o modelo e ampliar a capacidade de engenharia de features, a aplicação de novas ferramentas para melhorar os hiperparâmetros e adicionar etapas de cross validation para uma melhor precisão da análise. 

## Contribuições

Contribuições são bem-vindas!

## Ferramentas
Python, Jupyter Notebook
