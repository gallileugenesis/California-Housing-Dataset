# Kaggle Competition: Regression with a Tabular California Housing Dataset (em construção)

O objetivo desse projeto é explorar a competição Kaggle [Regression with a Tabular California Housing Dataset](https://www.kaggle.com/competitions/playground-series-s3e1/overview), implementando diversas variações de pré-processamento, extração de recursos e modelos. 

Essa competição usa o banco de dados [California Housing Dataset](https://inria.github.io/scikit-learn-mooc/python_scripts/datasets_california_housing.html), que fornece informações sobre os preços das casas em várias regiões da Califórnia. Ele contém características relacionadas a vários aspectos das casas e seus arredores. 

As principais informações contidas no conjunto de dados são:

- **MedHouseVal:** Valor mediano das casas em cada bloco .
- **MedInc:** Renda mediana dos habitantes em um bloco (em unidades de $10,000).
- **HouseAge:** Mediana da idade das casas em um bloco.
- **AveRooms:** Número médio de quartos por domicílio.
- **AveBedrms:** Número médio de quartos por família.
- **Population:** Número de pessoas que ocupam casas em um bloco.
- **AveOccup:** Número médio de membros do domicílio.
- **Latitude:** Latitude da localização da casa.
- **Longitude:** Longitude da localização da casa.

O objetivo da tarefa é prever o valor mediano (MedHouseVal) das casas em cada bloco (chamado de "target" ou "rótulo"). Este valor representa o valor médio da casa em unidades de $100,000.  

Os modelos testados foram os seguintes:
- **Linear Regression:** modelo mais simples, usado como baseline. Em seu melhor score obteve um RMSE de 1.35543. Para mais detalhes ver a pasta [Linear_Regression_Solution](https://github.com/gallileugenesis/California-Housing-Dataset/tree/main/Linear_Regression_Solution).