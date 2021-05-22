# bacteria-ID
Reto Identificación rápida de bacterias patógenas mediante espectroscopia Raman y aprendizaje profundo

- Hito 1:
  En el fichero IdentificacionBacterias.ipynb se muestran los distintos modelos entrenaos para la detección de bacterias patógenas:
    - Regresión Logística con PCA
    - Regresión logistica
    - TreeCalsifier con PCA
    - TreeCalsifier
    - RandomFores con PCA
    - RandomForest
    - SVM con PCA
    - SVM
    - ResNet
    - Tres modelos de CNN
  Los modelos se han entrenado en el dataset X_reference y se han refinado con el dataset X_finetune. Finalmente se muestran los resultados en el dataset de test X_test.
  
- Hito 2:
  En el fichero SVC_Model_Saved_intervalos_ruido.ipynb se muestran los resultados obtenidos al aplicar ruido en distintos intervalos, y con distinta intensidad, a partir de los datos del dataset X_reference y con SVC pre-entrenada, a los datos previamente se aplica PCA de 90 componentes.
  
  En el fichero Prueba_CNN_+_ruido.ipynb se muestran los resultados de aplicar intervalos de ruido con el modelo CNN
