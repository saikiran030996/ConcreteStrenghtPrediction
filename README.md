# ConcreteStrenghtPrediction 

## Problem Statement
To build a regression model to predict the concrete compressive strength based on the different features in the training data. 

## Architecture

![](architecuture.jpg)

## Data Description
Given is the variable name, variable type, the measurement unit and a brief description. 
The concrete compressive strength is the regression problem. The order of this listing 
corresponds to the order of numerals along the rows of the database. 


| Name | Data Type | Measurement | Description |
| ------------- | ------------- | ------------- | ------------- |
|Cement (component 1)|	quantitative |	kg in a m3 mixture |	Input Variable  | 
| Blast Furnace Slag (component 2) |	quantitative |	kg in a m3 mixture	| Input Variable-- Blast furnace slag is a nonmetallic coproduct produced in the process. It consists primarily of silicates, aluminosilicates, and calcium-alumina-silicates  |
| Fly Ash (component 3) |	quantitative |	kg in a m3 mixture|Input Variable- it is a coal combustion product that is composed of the particulates (fine particles of burned fuel) that are driven out of coal-fired boilers together with the flue gases|
|Water (component 4)|quantitative	| kg in a m3 mixture	|Input Variable |
|Superplasticizer (component 5)	| quantitative	|kg in a m3 mixture	| Input Variable--Superplasticizers (SP's), also known as high range water reducers, are additives used in making high strength concrete. Their addition to concrete or mortar allows the reduction of the water to cement ratio without negatively affecting the workability of the mixture, and enables the production of self-consolidating concrete and high performance concrete|
|Coarse Aggregate (component 6) |	quantitative	| kg in a m3 mixture	|Input Variable-- construction aggregate, or simply "aggregate", is a broad category of coarse to medium grained particulate material used in construction, including sand, gravel, crushed stone, slag, recycled concrete and geosynthetic aggregates|
|Fine Aggregate (component 7)	|quantitative	|kg in a m3 mixture	|Input Variable—Similar to coarse aggregate, the constitution is much finer|
|Age	| quantitative	| Day (1~365)	| Input Variable |
|Concrete compressive strength	|quantitative|MPa	|Output Variable|

Apart from training files, we also require a "schema" file from the client, which contains all the relevant information about the training files such as:
Name of the files, Length of Date value in FileName, Length of Time value in FileName, Number of Columns, Name of the Columns, and their datatype.

