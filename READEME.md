## Descrição do Projeto

Este projeto explora e compara três algoritmos populares de árvores de decisão: **ID3**, **C4.5** e **CART**. Além disso, o projeto abrange a construção de um Mini Akinator utilizando árvores de decisão para extração de regras do tipo SE...ENTÃO... a partir de uma base de dados de animais.

## Estrutura do Projeto

- **`Data/`**: Contém os seguintes arquivos:
  - **`class.csv`**: Base de dados que mapeia os tipos de classes para diferentes animais.
  - **`zoo.csv`**: Base de dados com 101 registros de animais, descritos por 17 atributos binários e categóricos.
  - **`Comparação entre ID3, C4.5 e CART.tex`**: Arquivo LaTeX contendo a descrição do processo de construção manual das árvores de decisão para cada algoritmo.

- **`Comparação entre ID3, C4.5 e CART.pdf`**: Relatório em PDF que apresenta a implementação manual dos algoritmos ID3, C4.5 e CART, construindo passo a passo as árvores de decisão e discutindo os resultados. Este relatório começa com a apresentação dos dados utilizados, encontrados em `Data/bank_data.json`.

- **`decision_tree_etropy_gini.ipynb`**: Jupyter Notebook que realiza a construção das árvores de decisão usando os dados de `Data/bank_data.json`, mas desta vez utilizando implementações prontas do scikit-learn. Este notebook foca na aplicação prática dos algoritmos com base em Entropia e Gini.

- **`data_mini_akinator.ipynb`**: Jupyter Notebook que constrói uma árvore de decisão utilizando os dados de `Data/class.csv` e `Data/zoo.csv` para extrair inferências do tipo SE...ENTÃO..., com o objetivo de criar um Mini Akinator.