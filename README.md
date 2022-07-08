# Proyectos de Aprendizaje Automático

## Equipo

1. [Antonio Badillo](https://github.com/abadillo)
2. [Daniel Bello](https://github.com/)
3. [José Di Pietro](https://github.com/JDevelop3r)

#

## [Proyecto 1](/docs/Informe_Proyecto1.pdf)

### 1. [Washington Homes for Sale](p1.1.ipynb)

Washington Homes for Sale es una empresa inmobiliaria que comercializa viviendas en Washington State, USA. La empresa cuenta con una base de datos que contiene los precios de venta de las viviendas vendidas en los últimos años en Washington, así como información acerca de estas casas y apartamentos como el número de cuartos, número de metros cuadrados, condición de la vivienda, entre otros. Usted ha sido contratado por la empresa para desarrollar un sistema de aprendizaje automático que permita predecir el precio de venta de una vivienda, a partir de los datos de esta vivienda. Dicho sistema le permitirá a la empresa tener un estimado del precio al cual se puede poner en venta cada vivienda, además, cuando un cliente propone vender su vivienda en cierta cantidad, la empresa podrá saber si este monto está por encima o por debajo del precio del mercado, y podrá orientar al cliente en este sentido.

### 2. [Santa Clara Winery](p1.2.ipynb)

Santa Clara Winery es un viñedo fundado en 1881 por la familia Miller, que a través de varias generaciones se ha dedicado a producir algunas de las variedades de Cabernet Sauvignon y Pinot Noir más reconocidas en California. El viñedo cuenta con una base de datos de calidad del vino que contiene información sobre los vinos producidos en el norte de California y sus variables fisicoquímicas, como la acidez, el ácido cítrico, el azúcar residual, los cloruros, entre otras, así como la calidad del vino, medida del 0 al 10. Usted ha sido contratado por el viñedo para generar un modelo predictivo que permita estimar la calidad del vino en base a sus variables fisicoquímicas. Esto le permitirá al viñedo probar nuevos procesos de producción del vino teniendo un estimado a piriori de la calidad del vino en función de sus valores fisicoquímicos.

#

## [Proyecto 2](/docs/Informe_Proyecto2.pdf)

### 1. [Detección de fraudes en tarjetas de crédito](p2.ipynb)

La empresa VISA lo ha contratado para construir un modelo predictivo de fraudes en transacciones de tarjetas de crédito. Para ello usted cuenta con un dataset de transacciones de tarjetas de crédito. Por razones de confidencialidad, las características V1, V2, ..., V28 son anónimas y no se conoce el significado original de la característica. Además se cuenta con el instante de tiempo de cada transacción (medido en segundos desde la transacción más temprana del dataset) y el monto de la transacción. La característica de salida es si la transacción es un fraude o no (1 si es un fraude, 0 en caso contrario).

Se cuenta con la siguiente información de cada transacción:

---

| Variable | Descripción                                                                                             |
| -------- | ------------------------------------------------------------------------------------------------------- |
| Time     | Instante de tiempo de la transacción (medido en segundos desde la transacción más temprana del dataset) |
| V1...V28 | Características anónimas obtenidas mediante PCA de las características originales                       |
| Amount   | Monto de la transacción                                                                                 |
| Class    | Fraude o no (1 si es un fraude, 0 en caso contrario)                                                    |

#

## Indicaciones

1. **Generar el conjunto de prueba. El conjunto de prueba se debe generar al comienzo y no volver a consultar hasta después de entonar el mejor modelo.** Se debe tomar una muestra estratificada del conjunto de datos.
2. **Explorar los datos para obtener ideas.** Usted debe ver las tendencias de los datos, distribución de los atributos, escala y rango de valores de cada característica, correlaciones, entre otros.
3. **Preparar los datos para exponer mejor los patrones de datos subyacentes a los algoritmos de aprendizaje automático.** Manejar los atributos que tienen categorías, hacer feature engineering, crear atributos combinados de ser necesario, manejar los atributos faltantes.
4. **Explorar muchos modelos diferentes y preseleccionar los mejores.** Debe usar validación cruzada para evaluar los modelos. Debe reportar el resultado de al menos tres modelos distintos y justificar su selección del mejor o de los mejores modelos.
5. **Afinar los modelos.** Entonar los hiperparámetros usando grid search o random search.
6. **Presentar la solución.** ¿Cuál es el mejor modelo? ¿Cómo se desempeña? ¿Puede mejorarse el desempeño? ¿Qué sería necesario hacer para mejorarlo?
