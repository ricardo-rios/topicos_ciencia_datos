# Pre-examen 

Sobre el siguiente dataset: 

https://raw.githubusercontent.com/ricardo-rios/topicos_ciencia_datos/master/ejercicios/ejercicio0001/datos.csv

Realizar lo siguiente: 

* Cargar el archivo usando la líbreria pandas (Capítulo 4). 
* Realizar análisis descriptivos a tus datos (Capítulo 5).
* Entender tus datos con visualizaciones (Capítulo 6).
* Crear un pipeline que realize lo siguiente: 
   * Escalar los datos para que tengan media cero y desviación típica 1, revisar lo siguiente: https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html
   * Usar feature union para agregar dos conjuntos de predictores o variables independientes las cuales resultan de usar selección univariada (sección 8.2) con 4 variables y componentes principales (sección 8.4) con 4 componentes.
* Usar Grid Search en un random forest con la siguiente combinación de hiperparametros: 

```
     'n_estimators': [200, 500],
     'max_features': ['auto', 'sqrt', 'log2'],
     'max_depth' : [4,5,6,7,8],
     'criterion' :['gini', 'entropy']

```
* Usando la métrica accuracy imprima el desempeño de la mejor
  combinación de hiperparámetros para el random forest. 
  
Sugerencia: podría ser de utilidad revisar el siguiente código:

https://scikit-learn.org/stable/tutorial/statistical_inference/putting_together.html

También, puede usar el buscador de google para búscar más recursos
que le ayuden a desarrollar los items.





