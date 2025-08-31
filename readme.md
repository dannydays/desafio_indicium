# Desafio Técnico de Data Science

## Descrição do Projeto
Este projeto realiza uma análise exploratória de dados (EDA) e modelagem preditiva em um conjunto de dados de filmes. O objetivo principal é prever a nota do IMDb com base em diversas características dos filmes, como gênero, elenco, diretor, entre outros.

## Estrutura do Projeto
- **Desafio-Tecnico-Data-Science.ipynb**: Notebook contendo todo o processo de análise, limpeza, engenharia de variáveis e modelagem.
- **modelo_imdb_final.pkl**: Arquivo contendo o modelo final treinado e salvo.
- **requirements.txt**: Lista de dependências necessárias para executar o projeto.
- **input/desafio_indicium_imdb.csv**: Conjunto de dados utilizado para a análise.

## Requisitos
Certifique-se de ter o Python instalado em sua máquina. As bibliotecas necessárias estão listadas no arquivo `requirements.txt`.

## Instalação e Execução
1. Clone este repositório:
   ```bash
   git clone https://github.com/dannydays/desafio_indicium
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd desafio_indicium
   ```
3. Inicie um ambiente virtual:
   ```bash
   python -m venv venv
   ```
4. Ative o ambiente:
   ```bash
   .\venv\Scripts\activate
   ```
5. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
6. Execute o Jupyter Notebook para visualizar o processo completo:
   ```bash
   jupyter notebook .\LH_CD_DANIELDIASJANOVICCI.ipynb
   ```

## Relatórios
Os relatórios de análise e EDA estão disponíveis no notebook `Desafio-Tecnico-Data-Science.ipynb`. Eles incluem:
- Análise exploratória de dados (EDA)
- Gráficos e insights
- Modelagem preditiva

## Modelo Treinado
O modelo final treinado está salvo no arquivo `modelo_imdb_final.pkl`. Ele pode ser carregado e utilizado para previsões futuras.
