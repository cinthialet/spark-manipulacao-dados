# Manipulação de Dados com Spark - PySpark

## Objetivo
Este repositório representa um passo adiante na minha jornada de manipulação de dados. Enquanto o projeto anterior focava em usar Python com Pandas para processamento de dados, este projeto explora a capacidade do Spark através da interface PySpark para lidar com grande volume de dados - Big Data. Ambos os projetos usam o mesmo dataset e abordam as mesmas demandas de negócio, tornando-os perfeitos para comparação. Se você está interessado em entender as diferenças, desafios e benefícios de cada ferramenta, recomendo fortemente que acompanhe ambos os projetos em paralelo.

## Demandas da Área de Negócio
As demandas deste projeto refletem as do projeto anterior baseado em Python/Pandas. A ideia é replicar as mesmas análises, mas agora com a potência do processamento distribuído do PySpark.
Mais informações podem ser vistas no [**Projeto de Manipulação de Dados com Python**](https://github.com/cinthialet/python-manipulacao-dados)

## Pacotes e Módulos Utilizados
- **PySpark:** Framework principal utilizado para processamento distribuído de grandes conjuntos de dados.
  - **SparkSession:** Ponto de entrada para funcionalidades do Spark.
  - **Functions (F):** Conjunto de funções para operações e transformações em dataframes.
  - **Data Types (como FloatType):** Para definição e conversão de tipos de dados em colunas de dataframes.
  - **Window:** Para operações de funções de janela em dataframes.

## Sobre os Dados
- **Dataset:** [Gas Prices in Brazil](https://www.kaggle.com/matheusfreitag/gas-prices-in-brazil)
- **Descrição:** O conjunto de dados reflete os preços médios semanais dos combustíveis no Brasil de 2004 a 2019.

## Estrutura do Projeto
- **Notebook:** `manipulacao_dados_pyspark.ipynb`
  
- **output:** Arquivos gerados durante a execução do notebook.
  
- **dados:** O dataset base do projeto: `GasPricesinBrazil_2004-2019.csv`

## Projeto Paralelo em Python
Se você estiver interessado em comparar as abordagens deste projeto com a versão Python/Pandas, confira o [**Manipulação de Dados com Python**](https://github.com/cinthialet/python-manipulacao-dados). Este projeto anterior serve como base para este e é uma excelente maneira de entender os contrastes entre as ferramentas e suas aplicações em cenários práticos.
