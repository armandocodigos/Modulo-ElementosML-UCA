### La actividad trata acerca de aplicar lo aprendido en un problema de interés personal.
El objetivo del trabajo final del módulo es entrenar un pequeño proyecto usando Machine Learning.
- Paso 1: **[Dataset]** Encontrar un problema que le llame la atención a usted a nivel personal/profesional. Se sugiere utilizar alguno de estos sitios:
    - https://archive.ics.uci.edu/
    - https://www.kaggle.com/datasets
    - https://paperswithcode.com/datasets
    - https://www.openml.org/
- Paso 2: **[Definición]** Evaluar si el problema es de regresión, clasificación, clusterización, o predicción de series temporales.
    - Explicar cuales son las variables independientes e dependientes.
- Paso 3: **[Pre-procesamiento]** Realizar todas las operaciones necesarias para que los datos esten listos para el modelaje.
   - Eliminar datos nulos, crear dummies o codificar datos categóricos.
   - Separar en subsets de entrenamiento y prueba.
- Paso 4: **[Modelado]** Entrenar varios modelos de ML, no hay requisito pero se anima a probar tantas combinaciones de hyper-parametros y modelos como usted desee
    - Redes neuronales [MLPRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPRegressor.html).
    - Máquinas de soporte vectorial [SVM](https://scikit-learn.org/stable/modules/svm.html).
    - Árboles de decisión [DecisionTree](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html).
    - Bosques aleatorios [RandomForest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html).
    - Métodos de ensamble [AdaBoost](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostClassifier.html) [GradientBoosting](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html).
- Paso 5: **[Output]** Seleccionar el mejor modelo en base a alguna métrica vista en el modulo y explicar porqué usted considera que es el mejor.

Se debe entregar el archivo ipynb (jupiter notebook) en el e-campus para el próximo lunes.

- Punto extra A: Utilizar un enfoque de train-validation-test en lugar de train-test.
- Punto extra B: Almacenar el modelo en un archivo binario "modelo.sav" y *utilizarlo* desde un script aparte "produccion.py".
