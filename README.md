# Proyecto_Sprint_15_Tripleten
## Modelo para Serie temporal de Machine Learning para predecir el numero de pedidos de taxis en la siguiente hora para un Aeropuerto

Para este caro practico del Bootcamp de Tripleten usaremos un dataset de la empresa Sweet Lift Taxi que tiene datos de Enero a Agosto sobre el pedido de taxis en un aeropuerto y entrenaremos modelos de prediccion para la siguiente hora.

### Objetivo
Crear un modelo de ML en donde RECM no sea superior a 48.

### Resultados
* Pudimos observar la tendencia ascendente en los pedidos en los meses de junio, julio y agosto ya que son temporadas donde se toman vacaciones.
* Identificamos con la estacionalidad que hay patrones donde sube o aumenta el pedido de taxis dependiendo de si es entre semana o fin de semana.
* Construimos un modelo con RandomForest donde cumplimos el objetivo y obtuvimos RECM= 42.44 aunque observamos que el modelo de XGBoost tambien es un opcion viable ya que tiene mayor velocidad de entrenamiento y la metrica RECM es muy parecida.
