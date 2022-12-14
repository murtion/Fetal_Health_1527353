# Práctica Kaggle APC UAB 2022-23
### Nom: Iván Jiménez Ramos ### DATASET: Fetal_Health
### URL: [kaggle](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification)
## Resum
El dataset utilitza datos sobre la salud del feto, cuenta con 2126 entradas de 22 atributos cada uno. Los atributos son de tipo float y siguen una distribución normal.
### Objectivos del dataset 
El objetivo del dataset  es buscar los mejores atributos y el mejor algoritmo para predecir la salud del feto.
## Experimentos
Durante la práctica se han escalado los datos y se ha observado entre varios algoritmos cual accierta mas.
### Preprocesado
Quines proves hem realitzat que tinguin a veure amb el pre-processat? com han afectat als resultats?
Para el procesado primero se han observado los tipos de valores y si existian valores nulos.
Despues se ha observado la corelación y la distribucion de los datos. Se han obserbado los rangos y se han escalado, no se han eliminado ningun tipo de dato para no afectar al resultado debido a que no afectaba mucho.
## Conclusions
He podido observar que para esta base de datos el mejor algoritmo dentro de los elegidos ha sido GradientBoostingClassifier.
Teniendo en cuenta los valores obtenido y el algoritmo utilizado podemos ver que se puede obtener un resultado acertado en la mayoria de veces, de este modo es posible bajar la mortalidad infantil y las muertes durante el parto si se toman las decisiones correctas.

Tras obserbar varios ejemplos he podido observar que el procedimiento sigue la misma estructura de tratado de datos, así como las misma elecciones de entrenamiento.
## Idees per treballar en un futur
La tecnologia, la ciencia y la medicina estan en continuo avance, creo que seria conveniente actualizar la base de datos segun se obtengan nuevos resultados.
Tambien seria pisble que en un futuro se tengan que tener en cuenta mas variables nuevas para obtener un mejor resultado.
## Llicencia
El projecte se ha desarrollado con la licència de GoogleColab
