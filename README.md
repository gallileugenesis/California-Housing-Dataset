# Kaggle Competition: Regression with a Tabular California Housing Dataset (em construção)

O objetivo desse projeto é explorar a competição Kaggle [Regression with a Tabular California Housing Dataset](https://www.kaggle.com/competitions/playground-series-s3e1/overview), implementando diversas variações de pré-processamento, extração de recursos e modelos. 

Essa competição usa o banco de dados [California Housing Dataset](https://inria.github.io/scikit-learn-mooc/python_scripts/datasets_california_housing.html), que é frequentemente usado em tarefas de regressão e fornece informações sobre os preços das casas em várias regiões da Califórnia. Ele contém características relacionadas a vários aspectos das casas e seus arredores. 

As principais informações contidas no conjunto de dados são:

- MedInc (Renda Média): A renda média dos habitantes em um bloco de casas (em unidades de $10,000).
- HouseAge (Idade da Casa): A mediana da idade das casas em um bloco.
- AveRooms (Média de Quartos): A média de quartos nas casas em um bloco.
- AveBedrms (Média de Quartos para Dormir): A média de quartos para dormir nas casas em um bloco.
- Population (População): O número de pessoas que ocupam casas em um bloco.
- AveOccup (Média de Ocupação): A média de ocupantes por casa em um bloco.
- Latitude (Latitude): Latitude da localização da casa.
- Longitude (Longitude): Longitude da localização da casa.

O objetivo da tarefa é prever o valor médio das casas em cada bloco (chamado de "target" ou "rótulo"). Este valor representa o valor médio da casa em unidades de $100,000.  
