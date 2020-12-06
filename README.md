# :gem:  diamonds-project  :gem:

## INDICE
### 1. PROYECTO :exploding_head: :sunglasses:
### 2. ESTRUCTURA :skull:
### 3. OBJETIVO :woman-lifting-weights: :checkered_flag:
### 4. RECURSOS :page_with_curl: :linked_paperclips:

![fotodeportada](https://github.com/leticia-sobrino/diamonds-project/blob/main/imagen/diamante-todo-lo-que-tienes-que-saber-sobre-los-diamantes.jpg)


## 1. PROYECTO :exploding_head: :sunglasses:
Este proyecto consiste en la limpieza y análisis de dos datasets para poder predecir el precio de los diamantes dadas unas variables características de estos. Esta predicción se realizará mediante modelos estadísticos de Machine Learning y cuyo objetivo será predecir el mejor modelo que se acerque a la relidad.
Tras ser proporcionados dos dataframes:

   1. train.csv --> Dataframe en dónde nos encotramos tanto las variables características (denominadas X) como el precio de los diamantes (denominado y). 
   Este csv ha sido trabajado de la siguiente manera:

        a) Descargado de la siguiente plataforma: "https://www.kaggle.com/"

        b) Analizado y limpiado

        c) Entrenado con diferentes modelos estadísticos para llegar a la mejor predicción posible.

        d) Una vez han sido prácticados los diferentes modelos de machine learning se han puesto a prueba en el otro dataframe (test.csv) para ver si conseguiamos sacar el precio real o por lo menos aproximarnos a él de la mejor manera posible.

   2. test.csv --> Dataframe en dónde solamente nos econtamos las variables características de los diamantes (la variable X) pero NO nos encontramos el precio (la variable y).
   En este archivo hemos tenido que seguir unos pasos similares que en el anterior:

        a) Descargado de la siguiente plataforma: "https://www.kaggle.com/"

        b) Analizado y limpiado para poder aplicarle los modelos estadísticos.

        d) Y, en este tercer paso es dónde se diferencia del train.csv, hemos aplicado "a ciegas" los modelos estadísticos entrenados con el otro dataframe para así poder participar en una competición de kaggle : "https://www.kaggle.com/c/diamonds-datamad1020-rev/overview"



## 2. ESTRUCTURA :skull:
Este proyecto está organizado de la sigyinete manera:
 1. Una carpeta de data, escondida en el .gitignore por su peso, en donde se encontrará los datasets originales, los dataset finalies limpios y, las predicciones realizadas por cinco modelos estadísticos diferentes que han sido submiteadas a la competición de kaggle.
   
 2. Una carpeta de notebooks:

    2.1 Análisis dataframe FINAL:

    En este se encontrá los dos datasets originales manipulados, estudiados, analizados y limpiados para la futura aplicación de modelos de machine learning.

    2.2 Entrenamientos:
    En este notebook se encontrará los diferentes entrenamientos de modelos de machine learning sobre el dataset de train limpio.
    Para la aplicación de estos modelos se han seguido los siguietes pasos:

     - Train-test-split method ✓
     - LinearRegression ✓
     - DecisionTreeRegressor ✓
     - KNeighborsRegressor ✓
     - GradientBoostingRegressor ✓
     - RandomForestRegressor ✓
  
    2.3 Modelos
    Este notebook es el notebook final en dónde podrás encontrar los modelos entrenados sobre el dataframe de test, con el fin de sacar las mejores predicciones posibles sobre el precio y aproximarnos mucho al precio real de los diamantes o conseguir el mínimo error posible de acierto.

3. Una carpeta de images: en la cual se encuentra guardada la foto de la pantalla.
   
4. un archivo .gitignore, en donde se encuentra guardada la carpeta de data para evitar problemas a la hora de subir el proyecto a la plataforma de GitHub.
   
5. DIAPOSITIVA RESUMEN


## 3. OBJETIVO :woman-lifting-weights: :checkered_flag:
El objetivo del proyecto ha sido utilizar los conocimientos adquiridos durante la semana pasada de Machine Learning para poder ponerme a prueba sobre lo entendido, y qué ,ejor enfrentándome a un caso real.
El fin de este proyecto por tanto ha sido encontrar los mejores modelos posibles que se acercaran al precio real de los diamantes dependiendo de todas las variables dadas. Y, finalmente he participado en una competición de kaggle privada con mis resultados encontrados.


## 4. RECURSOS :page_with_curl: :linked_paperclips:

En este apartado dejaré los recursos que me han ayudado  para el desarrollo de este proyecto:

- Proporción de datos:
  
  https://www.kaggle.com/c/diamonds-datamad1020-rev/data

- Desarrollo del proyecto:
  
  https://github.com/leticia-sobrino/datamad1020-rev
  
  https://github.com/leticia-sobrino/teaching-ironhack-data-madrid-2020

  https://devdocs.io/scikit_learn-compose/



  
