[//]: # (Badges do projeto - 🡣)

[![image](https://img.shields.io/badge/tags-KAGGLE%20|%20DATASET%20|%20EXPLORATORY%20|%20DATA%20|%20ANALYSIS%20-red)]()
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/Pandas)]()
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)]()

[//]: # (🡡 - Badges do projeto)

![Logo](https://www.fiap.com.br/wp-content/themes/fiap2016/images/sharing/fiap.png)

# Checkpoint 1TDS

• Esta atividade deve ser realizada individualmente.


## Instalando alguns pacotes

Caso necessário faça a instalação das seguintes bibliotecas

```bash
    pip install numpy
    pip install pandas
    pip install matplotlib
    pip install scipy
```

## Atividades

- Realizar a leitura e analisar um famoso conjunto de dados, o dataset do Titanic

Acesse o link e faça o download do arquivo .csv. Para acessar pelo colab, faça o upload em seu Drive.
[Titanic - Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
Recomenda-se criar um perfil no Kaggle.

Utilize a biblioteca pandas para ler o dataset. Veja o exemplo:

```python
import pandas as pd

df_titanic = pd.read_csv("/meu_drive/meus_dados/Titanic-Dataset.csv")
df_titanic.head()
```

#### [10 pontos]
- Faça uma descrição do conjunto de dados. Indique os seguintes pontos:
    - Quantidade de Linhas x Colunas
    - Dados Faltantes (Null)

Responda no relatório: Quais são as colunas que possuem dados categóricos?

#### [20 pontos]
- Utilize as métricas descritivas para analisar o conjunto de dados:
    - Moda
    - Média
    - Mediana
    - Variância
    - Desvio Padrão

#### [20 pontos]
Responda no relatório:
- Qual é a moda, a média, a mediana, a variância e o desvio padrão das colunas Fare e Age?
- Qual é a quantidade de embarques de cada porto presente no dataset?
- Qual é a proporção de sobreviventes?
- Quais são os passageiros com a menor e a maior idade presentes nos registros?


#### [50 pontos]
- Utilize as bibliotecas Matplotlib, Seaborn e Plotly (opcional) para criar visualizações das análises realizadas:
    - Histograma
    - Scatter plot

Responda no relatório:
- Demonstre com um gráfico a quantidade de sobreviventes e não sobreviventes de acordo com classe de embarque.
- Demonstre com um gráfico a relação entre idade e valor pago na passagem de acordo com a coluna Sex.
- Demonstre com um gráfico a relação entre idade e valor pago na passagem de acordo com a coluna Survived.
- Demonstre com um gráfico a relação entre idade e valor pago na passagem de acordo com a coluna Embarked.
- Demonstre com um gráfico a relação entre idade e valor pago na passagem de acordo com a coluna Pclass.
- Demonstre com um gráfico a quantidade de Male e Female.
- Demonstre com um gráfico a quantidade de Survived 0 e 1.
- Demonstre com um gráfico a frequência de Age.
- Demonstre com um gráfico a frequência de Fare.
- Demonstre com um gráfico a frequência de Embarked.

### OBS.: Os gráficos devem conter a sua interpretação por escrito - em markdown.

• Esta atividade é baseada no conteúdo de estatística, manipulação de arquivos e visualização de dados.


## Deployment

Para entregar este projeto

```bash
Para entrega, o aluno deverá elaborar um único relatório (Jupyter Notebook) com os resultados das atividades solicitadas.
A entrega deve ser realizada pelo Teams da disciplina em um único arquivo no formato .ipynb identificado como
“RM_NOME_202402_CP4.ipynb”, onde “NOME” e "RM" devem ser substituídos pelos dados do aluno que elaborou o arquivo.
```

• As análises devem conter o código utilizado e suas respectivas considerações utilizando Markdown para explicar a análise das métricas descritivas e dos gráficos plotados.


## Authors

- [@ViniciusHolanda001](https://github.com/ViniciusHolanda001)


## Documentation

[![Kaggle](https://www.kaggle.com/)]()
[![Matplotlib](https://matplotlib.org/stable/index.html)]()
[![Numpy](https://numpy.org/doc/stable/)]()
[![Pandas](https://pandas.pydata.org/docs/)]()
[![Seaborn](https://seaborn.pydata.org/#)]()
[![Scipy](https://docs.scipy.org/doc/scipy/)]()


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Contato

Para contato, envie e-mail para profvinicius.cavalcante@fiap.com.br ou me procure pelo Teams.
