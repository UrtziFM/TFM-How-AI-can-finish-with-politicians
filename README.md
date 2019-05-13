# TFM-How-AI-can-finish-with-politicians
Como la Inteligencia Artificial puede acabar con los Politicos

Más allá del título sensacionalista que he buscado para mi TFM y que seguro promete más de lo que yo por mis capacidades tecnicas actuales puedo llegar a conseguir, el objetivo principal de este TFM es poder analizar primero y ver si existe interelacionalidad despues entre los diferentes indicadores de sostenibilidad que estan descriptos y medidos por los organismos publicos vascos, para una vez descubierto patrones entre ellos, ver si la presencia, existencia o ausencia de ellos puede afectar en valores de participacion en las elecciones municipales, indicadores de satisfaccion general o de bienestar y en otras indicadores de sentimiento que pueda llevarnos a predecir actuaciones efecientes en la politica municipal pudiendo obtener reditos politicos por ello.

Hasta ahora todo lo relacionado con la inteligencia artificial y la politica se ha centrado en ejemplos negativos de influencia sobre el electorado, con escandalos como el de Facebook y Cambridge Analytics, Fake News en RRSS u muchos otros casos.

En cambio, el potencial y la ventaja de que nos da el Machine Learning, Deep Learning u otras tecnicas avanzadas de analisis de datos, no estan en impactar en el sentimiento de un elector gracias a influir en el con noticias o bulos, sino en la posibilidad de poder gestionar mas eficientemente sus recursos municipales que como se ha demostrado en muchas ocasiones en la politica municipal es mucho mas efectivo a largo plazo que cualquier titular de prensa.

No he utilizado ni he centrado mi estudio por casualidad en las Bases de Datos de Euskadi, ya que es un claro de ejemplo de que a pesar de la politizacion y polarizacion en muchos casos, los grandes gestores municipales (claros ejemplos, a la vez que antagonistas politicamente, fueron Iñaki Azcuna u Odon Elorza) siempre conseguieron aglutinar votantes sin tener en cuenta su signo politico.

Los Dataset que utilizare se pueden encontrar en:

- http://opendata.euskadi.eus/catalogo-datos/ 

Primeros pasos:

-1) Generar un tablon uniforme con las diferentes variables y por municipios.
· Mi idea es un utilizar pandas para generar este Dataframe, analizarlo y visualizarlo.
-2) Una vez generado los tres Dataframes principales y accesibles en la carpeta Data, utilizaremos tecnicas de aprendizaje automatico supervisado para comprobar si las variables que hemos definido pueden ayudarnos a predecir una necesidad que hasta ahora solo se podia calcular a traves de encuestas (variables explicitas) y que vamos comprobar si con variables implicitas tenemos margen de error.
-3) Utilizaremos diferentes metodos de Clasificacion de ML primero, para clasificar si un municipio es participativo o no (mediana), y luego utilzaremos de Regresion de ML para predecir el resultado de participacion electoral en cada municipio.

