# Proyecto 1 de Aprendizaje Automático

## Equipo

1. Antonio Badillo
2. Daniel Bello
3. José Di Pietro

## Problemas

### 1. Washington Homes for Sale

Washington Homes for Sale es una empresa inmobiliaria que comercializa viviendas en Washington State, USA. La empresa cuenta con una base de datos que contiene los precios de venta de las viviendas vendidas en los últimos años en Washington, así como información acerca de estas casas y apartamentos como el número de cuartos, número de metros cuadrados, condición de la vivienda, entre otros. Usted ha sido contratado por la empresa para desarrollar un sistema de aprendizaje automático que permita predecir el precio de venta de una vivienda, a partir de los datos de esta vivienda. Dicho sistema le permitirá a la empresa tener un estimado del precio al cual se puede poner en venta cada vivienda, además, cuando un cliente propone vender su vivienda en cierta cantidad, la empresa podrá saber si este monto está por encima o por debajo del precio del mercado, y podrá orientar al cliente en este sentido.

### 2. Santa Clara Winery

Santa Clara Winery es un viñedo fundado en 1881 por la familia Miller, que a través de varias generaciones se ha dedicado a producir algunas de las variedades de Cabernet Sauvignon y Pinot Noir más reconocidas en California. El viñedo cuenta con una base de datos de calidad del vino que contiene información sobre los vinos producidos en el norte de California y sus variables fisicoquímicas, como la acidez, el ácido cítrico, el azúcar residual, los cloruros, entre otras, así como la calidad del vino, medida del 0 al 10. Usted ha sido contratado por el viñedo para generar un modelo predictivo que permita estimar la calidad del vino en base a sus variables fisicoquímicas. Esto le permitirá al viñedo probar nuevos procesos de producción del vino teniendo un estimado a piriori de la calidad del vino en función de sus valores fisicoquímicos.

### 3. WHO stroke prevention program

La Organización Mundial de la Salud (OMS) se encuentra realizando un estudio para conocer cuáles son los factores de riesgo de padecer un Accidente Cerebrovascular (ACV). La OMS cuenta con una base de datos de pacientes con información sobre la salud de cada paciente y sus condiciones de riesgo de padecer un ACV, como hipertensión, enfermedad cardíaca, nivel promedio de glucosa sérica, índice de masa corporal, entre otros. Usted ha sido contratado por la OMS para desarrollar un modelo que permita predecir el riesgo de un paciente de padecer de un ACV en función de sus variables de riesgo. Esto le permitirá a la OMS educar a los pacientes sobre los factores de riesgo, así como recomendar medidas preventivas para los pacientes con riesgo de ACV que le permitan mejorar su condición y llevar una vida saludable.

## Indicaciones

1. **Generar el conjunto de prueba. El conjunto de prueba se debe generar al comienzo y no volver a consultar hasta después de entonar el mejor modelo.** Se debe tomar una muestra estratificada del conjunto de datos.
2. **Explorar los datos para obtener ideas.** Usted debe ver las tendencias de los datos, distribución de los atributos, escala y rango de valores de cada característica, correlaciones, entre otros.
3. **Preparar los datos para exponer mejor los patrones de datos subyacentes a los algoritmos de aprendizaje automático.** Manejar los atributos que tienen categorías, hacer feature engineering, crear atributos combinados de ser necesario, manejar los atributos faltantes.
4. **Explorar muchos modelos diferentes y preseleccionar los mejores.** Debe usar validación cruzada para evaluar los modelos. Debe reportar el resultado de al menos tres modelos distintos y justificar su selección del mejor o de los mejores modelos.
5. **Afinar los modelos.** Entonar los hiperparámetros usando grid search o random search.
6. \*\*Presentar la solución. ¿Cuál es el mejor modelo? ¿Cómo se desempeña? ¿Puede mejorarse el desempeño? ¿Qué sería necesario hacer para mejorarlo?
